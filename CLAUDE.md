# CLAUDE.md — Vận hành Quỹ phát triển đất Nghệ An

Tài liệu hướng dẫn cho Claude khi làm việc trong repo này. Đọc file này trước
khi xử lý bất kỳ đầu việc nào.

## 1. Bối cảnh

Repo là **không gian làm việc nghiệp vụ** (không phải repo lập trình) của Quỹ
phát triển đất Nghệ An — đơn vị sự nghiệp công lập trực thuộc UBND tỉnh Nghệ An,
hoạt động theo mô hình Hội đồng quản lý Quỹ (HĐQL Quỹ) + Ban Giám đốc.

Nội dung repo: quy trình, checklist, biểu mẫu và hồ sơ thực tế cho 4 nhóm việc:

| Nhóm | Tên nhóm việc | Thư mục |
|---|---|---|
| I | Nghiệp vụ Quỹ phát triển đất (ứng vốn) | `01-nghiep-vu-quy-phat-trien-dat/` |
| II | Quỹ nhà ở & Dự án NOXH | `02-quy-nha-o-va-du-an-noxh/` |
| III | Tổ chức, Hành chính | `03-to-chuc-hanh-chinh/` |
| IV | Công tác Đảng & Đoàn thể | `04-cong-tac-dang-doan-the/` |

Nguồn gốc danh mục: `00-tai-lieu-chung/Bang-cac-dau-cong-viec-Quy.xlsx`.
Bản đã chuẩn hoá: `00-tai-lieu-chung/danh-muc-dau-viec.md`.

## 2. Nguyên tắc làm việc bắt buộc

1. **Ngôn ngữ**: toàn bộ sản phẩm (văn bản, báo cáo, tên file, commit message)
   viết bằng **tiếng Việt**, văn phong hành chính nhà nước.
2. **Không bịa số liệu**. Nếu thiếu dữ liệu đầu vào, để placeholder rõ ràng
   dạng `[…]` hoặc `{{SỐ_LIỆU_CẦN_BỔ_SUNG}}` và liệt kê ở cuối văn bản mục
   "Thông tin còn thiếu". Tuyệt đối không điền số ước đoán vào tờ trình,
   báo cáo thẩm định hay quyết định.
3. **Không bịa căn cứ pháp lý**. Chỉ dẫn chiếu văn bản có trong
   `00-tai-lieu-chung/can-cu-phap-ly.md`. Nếu cần căn cứ ngoài danh mục đó,
   ghi rõ `[CẦN KIỂM TRA HIỆU LỰC]` bên cạnh và nhắc người dùng xác minh.
   Văn bản pháp luật về đất đai/nhà ở thay đổi nhanh — luôn coi danh mục là
   bản tham khảo cần đối chiếu, không phải chân lý.
4. **Theo đúng quy trình trong README của từng đầu việc**. Mỗi thư mục đầu việc
   có `README.md` ghi: căn cứ, input, các bước, output, thời hạn, rủi ro.
   Khi được yêu cầu làm một đầu việc, đọc README đó trước tiên.
5. **Checklist trước khi xuất văn bản**: với hồ sơ ứng vốn và NOXH, bắt buộc
   chạy checklist pháp lý tương ứng trong `bieu-mau/` và báo cáo mục nào
   thiếu/chưa đạt. Không được bỏ qua bước này để "ra sản phẩm cho nhanh".
6. **Phân biệt rõ vai trò văn bản**: *Báo cáo thẩm định* là đánh giá của bộ phận
   chuyên môn; *Tờ trình* là đề xuất trình cấp có thẩm quyền; *Quyết định* là
   văn bản của người có thẩm quyền. Không trộn lẫn ba loại này.
7. **Bảo mật**: không đưa dữ liệu cá nhân (CCCD, số điện thoại, địa chỉ cư trú
   của người đăng ký thuê NOXH, danh sách đảng viên) ra ngoài repo, không gửi
   lên dịch vụ bên ngoài. Hồ sơ chứa dữ liệu cá nhân đặt trong `ho-so/` và
   không commit nếu chưa được yêu cầu.

## 3. Cấu trúc repo

```
CLAUDE.md                        — file này
README.md                        — giới thiệu & cách dùng
00-tai-lieu-chung/
  danh-muc-dau-viec.md           — 13 đầu việc, input/output
  can-cu-phap-ly.md              — danh mục văn bản pháp lý tham chiếu
  lich-cong-viec-dinh-ky.md      — mốc báo cáo tháng/quý/6 tháng/năm
  quy-uoc-van-ban.md             — thể thức, cách đặt tên file, số văn bản
  Bang-cac-dau-cong-viec-Quy.xlsx — file gốc do đơn vị cung cấp
01..04-<nhóm việc>/<đầu việc>/README.md   — quy trình từng đầu việc
bieu-mau/                        — biểu mẫu, checklist, bảng theo dõi
ho-so/                           — hồ sơ vụ việc thực tế (theo năm/mã hồ sơ)
.claude/commands/                — slash command cho các đầu việc hay dùng
```

## 4. Quy ước đặt tên

- Thư mục/file: không dấu, không khoảng trắng, dùng `-`, chữ thường.
- Hồ sơ vụ việc: `ho-so/<năm>/<nhóm>-<mã>-<tên-ngắn>/`
  ví dụ `ho-so/2026/UV-001-gpmb-dien-chau/`.
- Mã loại hồ sơ: `UV` ứng vốn · `TD` thẩm định · `NOXH` nhà ở xã hội ·
  `HC` hành chính · `BC` báo cáo · `DA` công tác Đảng.
- Văn bản dự thảo: `<loại>-<chủ-đề>-v<số>.md`, ví dụ
  `to-trinh-ke-hoach-ung-von-2026-v1.md`.

## 5. Khi người dùng yêu cầu một đầu việc

Trình tự xử lý mặc định:

1. Xác định đầu việc thuộc nhóm nào → mở `README.md` của thư mục đó.
2. Liệt kê input đang có và input còn thiếu (đối chiếu checklist).
3. Nếu thiếu input **mang tính quyết định** (ví dụ: chưa có QĐ phê duyệt
   phương án bồi thường thì không thể thẩm định ứng vốn) → báo rõ, không
   dựng văn bản giả định.
4. Nếu input đủ ở mức làm được → tạo dự thảo output vào thư mục hồ sơ tương
   ứng, theo biểu mẫu trong `bieu-mau/`.
5. Kết thúc bằng: danh sách việc người dùng cần làm tiếp (lấy thêm hồ sơ gì,
   trình ai, hạn nào).

## 6. Lưu ý chuyên môn thường gặp

- **Ứng vốn**: vốn ứng từ Quỹ là *ứng* — luôn gắn với nguồn hoàn trả và thời
  hạn hoàn trả. Mọi hồ sơ ứng vốn phải trả lời được: hoàn trả từ nguồn nào
  (tiền đấu giá đất, tiền sử dụng đất, ngân sách), khi nào, ai chịu trách nhiệm.
- **Nợ quá hạn**: phân loại theo tuổi nợ, không gộp chung trong/quá hạn.
- **NOXH**: điều kiện và đối tượng thuê theo Luật Nhà ở — khi chấm điểm phải
  nêu rõ tiêu chí và điểm từng tiêu chí, không kết luận "đủ điều kiện" suông.
- **Mua sắm, sửa chữa**: tách rõ các bước chủ trương → dự toán → KHLCNT →
  hợp đồng → nghiệm thu → thanh quyết toán. Không nhảy bước.
- **Báo cáo viên**: hạn nộp **ngày 25 hàng tháng** — mốc cố định, xem
  `00-tai-lieu-chung/lich-cong-viec-dinh-ky.md`.

## 7. Git

- Nhánh phát triển hiện tại: `ccr-99a4fd06-m0n658`.
- Commit message tiếng Việt, dạng `<nhóm>: <việc đã làm>`,
  ví dụ `ung-von: them checklist tham dinh ho so GPMB`.
- Không commit file chứa dữ liệu cá nhân chưa được duyệt.
