---
description: Xuất dự thảo văn bản (.md) ra Word theo thể thức, kèm PDF nếu cần
---

Xuất văn bản: $ARGUMENTS

1. Xác định file dự thảo `.md` (trong `ho-so/…`). Chưa rõ → hỏi.
2. Rà nhanh dự thảo: còn chỗ trống `{{…}}`/`[…]` không; còn mục
   "THÔNG TIN CÒN THIẾU" không; số liệu có kèm mốc thời gian, đơn vị không.
   Báo cho người dùng trước khi xuất.
3. Chạy `python cong-cu/xuat_van_ban.py <file.md>`; thêm `--pdf` nếu người dùng
   cần PDF; thêm `--bo-muc-nhap` khi xuất bản để trình ký (bỏ mục ghi chú nội bộ).
4. Báo đường dẫn file Word/PDF và các lưu ý công cụ in ra. Nhắc: văn bản là dự
   thảo — văn thư điền số, ngày, hoàn thiện thể thức và phát hành trên iOffice.
