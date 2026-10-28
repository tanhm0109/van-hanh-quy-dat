# Vận hành Quỹ phát triển đất Nghệ An

Không gian làm việc nghiệp vụ cho 4 nhóm việc / 13 đầu việc của Quỹ phát triển
đất Nghệ An, khởi tạo từ `Bảng các đầu công việc Quỹ`.

## Bắt đầu từ đâu

| Bạn muốn | Đọc file |
|---|---|
| Hiểu cách Claude làm việc trong repo này | [`CLAUDE.md`](CLAUDE.md) |
| Xem toàn bộ 13 đầu việc, input/output | [`00-tai-lieu-chung/danh-muc-dau-viec.md`](00-tai-lieu-chung/danh-muc-dau-viec.md) |
| Xem mốc thời hạn tháng/quý/năm | [`00-tai-lieu-chung/lich-cong-viec-dinh-ky.md`](00-tai-lieu-chung/lich-cong-viec-dinh-ky.md) |
| Tra văn bản pháp lý cần đối chiếu | [`00-tai-lieu-chung/can-cu-phap-ly.md`](00-tai-lieu-chung/can-cu-phap-ly.md) |
| Biết cách soạn, đặt tên văn bản | [`00-tai-lieu-chung/quy-uoc-van-ban.md`](00-tai-lieu-chung/quy-uoc-van-ban.md) |
| Lấy biểu mẫu | [`bieu-mau/`](bieu-mau/) |

## Bốn nhóm việc

| Nhóm | Nội dung | Thư mục |
|---|---|---|
| **I** | Nghiệp vụ Quỹ phát triển đất — kế hoạch ứng vốn, thẩm định hồ sơ ứng vốn, thu hồi vốn ứng | [`01-nghiep-vu-quy-phat-trien-dat/`](01-nghiep-vu-quy-phat-trien-dat/) |
| **II** | Quỹ nhà ở & dự án NOXH — khảo sát khu đất, thẩm tra thiết kế–dự toán, xét duyệt thuê & vận hành | [`02-quy-nha-o-va-du-an-noxh/`](02-quy-nha-o-va-du-an-noxh/) |
| **III** | Tổ chức, Hành chính — đề án VTVL/tự chủ/quy chế, mua sắm tài sản công, báo cáo định kỳ, báo cáo đột xuất | [`03-to-chuc-hanh-chinh/`](03-to-chuc-hanh-chinh/) |
| **IV** | Công tác Đảng & Đoàn thể — sinh hoạt Chi bộ, báo cáo viên, kiểm tra giám sát & xếp loại đảng viên | [`04-cong-tac-dang-doan-the/`](04-cong-tac-dang-doan-the/) |

Mỗi thư mục đầu việc có `README.md` ghi đủ: **căn cứ · đầu vào (checklist) ·
quy trình từng bước · đầu ra · thời hạn · rủi ro thường gặp**.

## Dùng với Claude Code

Lệnh có sẵn (gõ `/` trong Claude Code):

| Lệnh | Việc |
|---|---|
| `/tham-dinh-ung-von` | Thẩm định hồ sơ đề nghị ứng vốn (đầu việc I.2) |
| `/theo-doi-no-von-ung` | Rà soát tuổi nợ, phân loại nợ, dựng công văn đôn đốc (I.3) |
| `/bao-cao-dinh-ky` | Dựng báo cáo tháng/quý/6 tháng/năm (III.3) |
| `/bao-cao-dot-xuat` | Xử lý văn bản yêu cầu báo cáo của Sở, Ngành (III.4) |
| `/sinh-hoat-chi-bo` | Chuẩn bị nghị quyết, biên bản sinh hoạt Chi bộ (IV.1) |
| `/bao-cao-vien` | Dựng Báo cáo viên tháng — hạn ngày 25 (IV.2) |

Ví dụ cách yêu cầu trực tiếp:
- "Thẩm định hồ sơ ứng vốn của Ban QLDA huyện X, hồ sơ đính kèm."
- "Rà soát bảng theo dõi vốn ứng, liệt kê khoản quá hạn và dựng công văn đôn đốc."
- "Dựng báo cáo định kỳ quý III/2026, số liệu ở file này."

## Ba điều Claude sẽ luôn làm trong repo này
1. **Không bịa số liệu** — thiếu dữ liệu thì để `{{…}}` và liệt kê ở mục
   "Thông tin còn thiếu".
2. **Không bịa căn cứ pháp lý** — chỉ dẫn chiếu `can-cu-phap-ly.md`, mục nào
   chưa xác minh thì đánh dấu `[CẦN KIỂM TRA]`.
3. **Chạy checklist trước khi xuất văn bản** với hồ sơ ứng vốn và NOXH, và
   báo rõ mục nào còn thiếu.

## ⚠️ Lưu ý quan trọng

- **Danh mục pháp lý trong repo là bản tham khảo cần xác minh**, do Claude lập.
  Pháp luật đất đai, nhà ở, đấu thầu thay đổi nhanh — người phụ trách phải tự
  đối chiếu số hiệu và hiệu lực trước khi trích dẫn vào văn bản trình ký.
- **Biểu mẫu trong `bieu-mau/` là mẫu nội bộ để thống nhất cách làm**, không
  thay thế biểu mẫu bắt buộc của cơ quan có thẩm quyền. Khi Sở, Ngành hoặc
  Đảng ủy yêu cầu dùng biểu mẫu của họ thì dùng biểu mẫu đó.
- **Dữ liệu cá nhân** (hồ sơ thuê NOXH, hồ sơ đảng viên, nhân sự) lưu trong
  `ho-so/` và **không commit** khi chưa được yêu cầu — xem `.gitignore`.
