---
description: Cập nhật sổ theo dõi vốn ứng (Excel) từ chứng từ — hoàn trả, giải ngân, gia hạn, khoản mới — có sao lưu và nhật ký
---

Cập nhật **sổ theo dõi vốn ứng** (đầu việc I.3).

Nội dung cần cập nhật / chứng từ / file sổ: $ARGUMENTS

Trình tự:

1. Đọc `cong-cu/README.md`. Xác định file sổ (.xlsx trong `ho-so/`); chưa rõ → hỏi.
2. Đọc chứng từ người dùng đưa (ủy nhiệm chi, giấy nộp tiền, QĐ ứng vốn, phụ
   lục hợp đồng gia hạn… — file PDF/Word/ảnh hoặc nội dung gõ vào). Trích:
   mã hồ sơ, trường cần sửa, giá trị, **số hiệu và ngày chứng từ**.
3. **Trình bày bảng thay đổi dự kiến** (mã hồ sơ · trường · giá trị cũ · giá trị
   mới · chứng từ) và **chờ người dùng xác nhận** trước khi ghi. Giá trị cũ lấy
   bằng cách đọc sổ, không đoán.
   - Thiếu số hiệu chứng từ → không ghi, yêu cầu bổ sung.
   - Số tiền trên chứng từ không rõ, hoặc mã hồ sơ không khớp → hỏi lại.
4. Ghi bằng công cụ (mỗi khoản một lệnh):
   - Cộng dồn khoản thu hồi/giải ngân:
     `python cong-cu/cap_nhat_so.py <sổ> --ma <mã> --cong da_thu_hoi=<số tiền> --ly-do "<chứng từ>" --nguoi "<tên>"`
   - Đặt giá trị (gia hạn, sửa thông tin): `--dat han_hoan_tra=<dd/mm/yyyy>`
   - Khoản mới: `--them --dat ma_ho_so=... --dat ...`
   Không sửa tay file Excel, không sửa cột Dư nợ / Số ngày quá hạn / Nhóm nợ.
5. Chạy `python cong-cu/tuoi_no.py <sổ> --ngay-chot <hôm nay hoặc mốc người dùng nêu> --ghi-vao-so --nguoi "<tên>"`
   để cập nhật dư nợ, nhóm nợ.
6. Báo lại: thay đổi đã ghi, file sao lưu, cảnh báo (nếu có), khoản nào đổi nhóm nợ.
