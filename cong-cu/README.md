# Công cụ xử lý file — dùng cùng Claude Code

Các script nhỏ để Claude Code (hoặc cán bộ) **đọc, cập nhật sổ Excel và xuất
văn bản Word/PDF** ngay trên máy, không cần máy chủ, không cần phần mềm mới.

Nguyên tắc: **số liệu do script tính** (dư nợ, tuổi nợ, nhóm nợ, tổng hợp) —
Claude chỉ dùng kết quả script để dựng văn bản, không tự cộng trừ.

## Cài đặt (một lần trên mỗi máy đầu mối)

Cần: Python 3.10+; LibreOffice (chỉ khi muốn xuất PDF tự động).

```bash
python -m venv .venv
# Linux/macOS:
.venv/bin/pip install -r cong-cu/requirements.txt
# Windows:
.venv\Scripts\pip install -r cong-cu\requirements.txt
```

Dưới đây viết `python` — hiểu là `.venv/bin/python` (Linux/macOS) hoặc
`.venv\Scripts\python` (Windows).

## Các công cụ

| Script | Việc | Có sửa file gốc? |
|---|---|---|
| `tao_so_mau.py` | Tạo sổ theo dõi vốn ứng trống (.xlsx) có định dạng, sheet Nhật ký, Hướng dẫn | Tạo mới |
| `cap_nhat_so.py` | Sửa một khoản / thêm khoản mới vào sổ; bắt buộc ghi lý do, chứng từ | **Có** — tự sao lưu + ghi Nhật ký |
| `tuoi_no.py` | Tính dư nợ, số ngày quá hạn, nhóm nợ A–F theo mốc chốt; xuất báo cáo Excel; in tóm tắt JSON | Không (trừ khi `--ghi-vao-so`) |
| `xuat_van_ban.py` | Chuyển dự thảo `.md` → Word theo thể thức; `--pdf` thêm PDF | Tạo file mới |
| `so_von_ung.py` | Định nghĩa cột, khung nhóm nợ, hàm dùng chung | — |

Ví dụ:

```bash
# Ghi nhận khoản hoàn trả 2 tỷ (cộng dồn vào "Đã thu hồi")
python cong-cu/cap_nhat_so.py ho-so/so-theo-doi-von-ung.xlsx --ma UV-2026-001 \
    --cong da_thu_hoi=2000000000 --ly-do "UNC số 123 ngày 15/10/2026" --nguoi "Nguyễn Văn A"

# Tính tuổi nợ đến 30/9/2026, xuất báo cáo Excel và cập nhật cột tính trong sổ
python cong-cu/tuoi_no.py ho-so/so-theo-doi-von-ung.xlsx --ngay-chot 30/09/2026 \
    --xuat ho-so/2026/BC-quy-3/bang-tuoi-no-30-09-2026.xlsx --ghi-vao-so --nguoi "Nguyễn Văn A"

# Xuất công văn ra Word + PDF, bỏ mục ghi chú nội bộ ở cuối
python cong-cu/xuat_van_ban.py ho-so/2026/UV-001-.../cong-van-don-doc-v1.md --pdf --bo-muc-nhap
```

Trong Claude Code, không cần nhớ lệnh — dùng slash command:
`/theo-doi-no-von-ung`, `/cap-nhat-so-von-ung`, `/xuat-van-ban`.

## An toàn dữ liệu

- Sổ thật đặt trong `ho-so/` (không commit). `bieu-mau/` chỉ chứa sổ **trống**.
- Trước khi ghi, công cụ kiểm tra file có đang mở trên Excel không (file khóa
  `~$…`) — đang mở thì dừng, tránh ghi đè lẫn nhau.
- Mỗi lần ghi đều sao lưu vào thư mục `sao-luu/` cạnh sổ và ghi sheet `Nhat ky`.
- Văn bản Word xuất ra là **dự thảo**: chỗ trống `{{…}}` được tô vàng; văn thư
  hoàn thiện thể thức (số, ngày, chữ ký) và phát hành trên iOffice.
- Thông số thể thức (lề, cỡ chữ) ở `THE_THUC` trong `xuat_van_ban.py` — cần đối
  chiếu quy định thể thức văn bản hiện hành `[CẦN KIỂM TRA]`.
