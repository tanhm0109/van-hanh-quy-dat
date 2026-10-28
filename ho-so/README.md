# Hồ sơ vụ việc

Thư mục lưu hồ sơ thực tế. **Nội dung thư mục này không được commit mặc định**
(xem `.gitignore`) vì có thể chứa dữ liệu cá nhân: hồ sơ đăng ký thuê NOXH,
hồ sơ đảng viên, thông tin nhân sự.

Muốn đưa một hồ sơ cụ thể vào git: `git add -f ho-so/<đường-dẫn>` — và chỉ làm
khi đã rà soát không có dữ liệu cá nhân, hoặc được người phụ trách yêu cầu.

## Cấu trúc

```
ho-so/<năm>/<mã>-<tên-ngắn>/
```

Mã loại hồ sơ:

| Mã | Loại | Đầu việc |
|---|---|---|
| `UV` | Ứng vốn (hồ sơ đề nghị, thẩm định, quyết định, hợp đồng) | I.1, I.2, I.3 |
| `NOXH` | Khu đất / dự án NOXH; đợt xét duyệt thuê | II.1, II.2, II.3 |
| `HC` | Mua sắm, sửa chữa tài sản công; đề án, quy chế | III.1, III.2 |
| `BC` | Báo cáo định kỳ và báo cáo đột xuất | III.3, III.4 |
| `DA` | Công tác Đảng | IV.1, IV.2, IV.3 |

Ví dụ:

```
ho-so/2026/UV-001-gpmb-dien-chau/
  ├── 01-ho-so-nhan/            (công văn đề nghị, tài liệu pháp lý đơn vị gửi)
  ├── 02-tham-dinh/             (checklist đã điền, báo cáo thẩm định)
  ├── 03-trinh-duyet/           (tờ trình, quyết định, hợp đồng)
  └── 04-theo-doi/              (báo cáo giải ngân, biên bản kiểm tra, công văn đôn đốc)

ho-so/2026/BC-quy-3/
ho-so/2026/DA-bao-cao-vien/
```

## Nguyên tắc lưu hồ sơ
- Mỗi vụ việc một thư mục, **không trộn nhiều vụ việc**.
- Lưu kèm **số liệu gốc** đã dùng để lập báo cáo, phục vụ đối chiếu kỳ sau.
- Văn bản đã phát hành lưu bản cuối cùng, kèm bằng chứng đã gửi.
- Bản nháp đặt hậu tố `-v1`, `-v2`; giữ bản cuối, có thể xoá nháp trung gian.
