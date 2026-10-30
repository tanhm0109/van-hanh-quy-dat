---
description: Rà soát tuổi nợ, phân loại nợ vốn ứng và dựng công văn đôn đốc (đầu việc I.3)
---

Thực hiện đầu việc **I.3 — Theo dõi, đôn đốc thu hồi vốn ứng**.

Yêu cầu / file sổ / mốc chốt: $ARGUMENTS

Trình tự:

1. Đọc `01-nghiep-vu-quy-phat-trien-dat/03-theo-doi-thu-hoi-von-ung/README.md`
   và `cong-cu/README.md`.
2. Xác định **file sổ** (sổ thật trong `ho-so/`, dạng .xlsx hoặc .csv) và **mốc
   chốt số liệu**. Thiếu một trong hai → hỏi người dùng, không tự chọn.
3. Chạy công cụ tính (Python trong `.venv`):
   `python cong-cu/tuoi_no.py <sổ> --ngay-chot <dd/mm/yyyy> --xuat ho-so/<năm>/BC-.../bang-tuoi-no-<ngày>.xlsx`
   Chỉ thêm `--ghi-vao-so --nguoi "<tên>"` khi người dùng yêu cầu cập nhật sổ.
4. **Dùng nguyên số liệu trong kết quả JSON của công cụ** — không tự cộng trừ,
   không làm tròn khác đi. Nếu có `canh_bao` → nêu đầu tiên, đề nghị người
   dùng kiểm tra chứng từ/đối chiếu kế toán trước khi dùng số liệu.
5. Trình bày: bảng tổng hợp theo nhóm A–F, **cộng trong hạn và cộng quá hạn tách
   riêng**; danh sách sắp đến hạn (nhóm B); danh sách quá hạn (C–F).
6. Dựng công văn đôn đốc cho từng khoản nhóm C trở lên theo
   `bieu-mau/01-nghiep-vu-von-ung/mau-cong-van-don-doc-thu-hoi.md` (nhóm D trở
   lên thêm đoạn cảnh báo báo cáo HĐQL Quỹ và UBND tỉnh), lưu `.md` vào thư mục
   hồ sơ của khoản đó. Thông tin không có trong sổ (số TK, công văn trước…) để `{{…}}`.
7. Xuất Word (và PDF nếu người dùng cần):
   `python cong-cu/xuat_van_ban.py <file.md> [--pdf]`.
8. Nêu các khoản cần ưu tiên kiểm tra hiện trường trong kỳ.
9. Kết thúc bằng danh sách việc cần làm, kèm hạn, và đường dẫn các file đã tạo.

Không sửa số liệu trong sổ nếu người dùng không yêu cầu; muốn sửa dùng `/cap-nhat-so-von-ung`.
