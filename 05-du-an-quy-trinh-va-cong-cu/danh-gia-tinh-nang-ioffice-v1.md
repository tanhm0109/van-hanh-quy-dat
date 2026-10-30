# ĐÁNH GIÁ TÍNH NĂNG VNPT iOffice ĐỐI VỚI NHU CẦU CỦA QUỸ

Phục vụ: Đề xuất dự án (`de-xuat-du-an-quy-trinh-va-cong-cu-v2.md`), mục 5. Lập ngày 29/10/2026.

## 1. Nguồn thông tin và mức độ tin cậy

VNPT **không công bố tài liệu kỹ thuật hoặc API của iOffice ra công chúng**. Bản đánh giá này tổng hợp từ các nguồn công khai sau:

| Nguồn | Loại | Độ tin cậy |
|---|---|---|
| Hướng dẫn sử dụng VNPT-iOffice 4.0, vai trò văn thư và lãnh đạo (đăng trên cổng Sở KH&CN Phú Thọ) | Tài liệu hướng dẫn của VNPT | **Cao**: mô tả chức năng thực tế |
| Tham luận "Hệ thống quản lý văn bản VNPT iOffice 5.0" của VNPT An Giang, 02/2025 | Tài liệu giới thiệu của nhà cung cấp | Trung bình: mang tính quảng bá |
| Báo chí (SGGP, Viettimes, Báo Đầu tư), trang ứng dụng trên App Store | Truyền thông | Thấp – trung bình |

Ký hiệu cột "Xác minh" trong các bảng dưới đây:
- ✅ có trong hướng dẫn sử dụng;
- 🟡 chỉ có trong tài liệu quảng bá hoặc báo chí;
- ❓ chưa tìm thấy thông tin.

**Về Nghệ An:** theo báo chí, tỉnh triển khai VNPT-iOffice từ năm 2017 và đưa Trục liên thông văn bản nội tỉnh vào sử dụng từ 01/8/2018. **Chưa xác định được phiên bản Quỹ đang dùng (4.x hay 5.0)**; các tính năng mục 2.3 chỉ có nếu đã lên 5.0.

## 2. Tính năng theo phân hệ

### 2.1. Quản lý văn bản (lõi)

| Tính năng | Mô tả | Xác minh |
|---|---|---|
| Văn bản đến | Nhập văn bản đến, vào sổ (số đến nhảy tự động theo sổ), quét từ máy scan qua plugin, đính kèm file, ghi **hạn xử lý**, chuyển xử lý cho cá nhân hoặc đơn vị | ✅ |
| Văn bản đi | Dự thảo → chờ xử lý → đã xử lý → đã ban hành; xem **lịch sử xử lý** | ✅ |
| Văn bản theo dõi, văn bản đánh dấu | Theo dõi riêng các văn bản người dùng quan tâm | ✅ |
| Văn bản xem để biết | Văn bản gửi để biết, không cần xử lý | ✅ |
| Ủy quyền xử lý | Ủy quyền văn bản đến, văn bản đi hoặc toàn bộ. *Lưu ý: nhật ký ghi tên **người ủy quyền**, không ghi tên người thực hiện* | ✅ |
| Tra cứu | Theo số ký hiệu, trích yếu, cơ quan ban hành, hình thức, độ khẩn, hạn xử lý, trạng thái | ✅ |
| Hồ sơ công việc / hồ sơ cá nhân | Lưu văn bản vào hồ sơ do người dùng tự tạo để theo dõi | ✅ (chưa rõ có chia sẻ giữa các phòng được không) |
| Quản trị sổ văn bản | Cấu hình sổ văn bản đến, sổ văn bản đi | ✅ |
| Chỉnh sửa trực tuyến Word, Excel | Không cần tải file về máy | 🟡 |
| Ký số | Hỗ trợ chữ ký số của Ban Cơ yếu Chính phủ, VNPT, Viettel, MISA… | 🟡 (bản 4.1 trở lên) |
| Liên thông văn bản | Gửi, nhận qua Trục liên thông văn bản quốc gia và trục nội tỉnh | 🟡 |
| Ứng dụng di động | iOS, Android; xử lý và ký số trên điện thoại | 🟡 |

### 2.2. Điều hành, công việc

| Tính năng | Mô tả | Xác minh |
|---|---|---|
| Quản lý công việc, nhắc việc | Có được nêu trong danh sách tính năng. Chi tiết (giao việc nhiều bước, việc lặp lại, checklist) không có tài liệu | 🟡 / ❓ |
| Lịch công tác | Lịch cơ quan, lịch lãnh đạo. Bản 5.0 đồng bộ với Google Calendar, có nhắc lịch | 🟡 |
| Phân hệ Chỉ đạo điều hành | Theo dõi nhiệm vụ UBND tỉnh giao cho các Sở, ngành; **cảnh báo tự động khi đến hạn, quá hạn**; báo cáo tổng hợp tình hình thực hiện | 🟡 (thiết kế cho cấp tỉnh giao nhiệm vụ cho đơn vị) |
| Thống kê, báo cáo tình hình xử lý văn bản | Có được nhắc tới. **Khả năng xuất Excel chưa xác minh** | ❓ |
| Thông tin điều hành, nhắn tin nội bộ | Thông báo nội bộ | 🟡 |

### 2.3. Tính năng mới của bản 5.0 (theo tham luận của VNPT, 2025)

| Tính năng | Mô tả | Xác minh |
|---|---|---|
| ChatBot Gen AI | Tra cứu, tìm văn bản bằng câu hỏi tự nhiên. Do VNPT tự phát triển | 🟡 |
| OCR | Tự nhận dạng số ký hiệu, trích yếu, ngày ban hành, cơ quan ban hành từ văn bản giấy để giảm nhập tay | 🟡 |
| Phân loại tự động | Tự phân loại văn bản, cảnh báo văn bản khẩn | 🟡 |
| Bảo mật | Phân quyền chi tiết, lưu vết mọi thao tác, mã hóa dữ liệu, xác thực hai lớp | 🟡 |
| Tích hợp | Với hệ thống một cửa điện tử, hệ thống theo dõi nhiệm vụ của Văn phòng Chính phủ, đồng bộ hệ thống quản lý hồ sơ | 🟡 (không công bố đặc tả) |

## 3. Mức đáp ứng nhu cầu của Quỹ

| Nhu cầu | Đầu việc | iOffice đáp ứng | Ghi chú |
|---|---|---|---|
| Tiếp nhận, vào sổ, luân chuyển văn bản đề nghị | Tất cả | ✅ **Đầy đủ** | Giữ nguyên |
| Theo dõi hạn xử lý **từng văn bản** | Tất cả | ✅ **Đầy đủ** | Giữ nguyên |
| Dự thảo → trình → ký số → ban hành | Tất cả | ✅ **Đầy đủ** | Giữ nguyên |
| Gom các văn bản của **một hồ sơ** (ví dụ UV-001) | I.2, II.3, III.2 | 🟡 **Một phần** | Dùng "Hồ sơ công việc". Cần kiểm tra khả năng chia sẻ giữa các phòng |
| Biết hồ sơ **đang ở bước nào** trong quy trình nhiều bước | I.2, II.2, III.2 | ❌ **Không** | iOffice theo dõi theo văn bản, không theo bước nghiệp vụ |
| Sổ theo dõi khoản ứng, tuổi nợ, phân loại nợ | I.3 | ❌ **Không** | Cần lớp số liệu riêng |
| Chấm điểm xét duyệt thuê NOXH | II.3 | ❌ **Không** | Cần lớp số liệu riêng, có che dữ liệu cá nhân |
| Nhắc việc định kỳ (báo cáo tháng, quý, ngày 25) | III.3, IV.2 | 🟡 **Một phần** | Nếu phân hệ công việc hoặc lịch hỗ trợ việc lặp lại. Cần kiểm tra |
| Tổng hợp số liệu từ các phòng cho báo cáo | III.3, III.4 | ❌ **Không** | |
| Quy trình, checklist, biểu mẫu chuẩn | Tất cả | ❌ **Không** | Chỉ lưu được file, không quản lý quy trình |
| Dựng dự thảo văn bản bằng AI | Tất cả | ❌ **Không** | ChatBot 5.0 chỉ tra cứu, không soạn thảo (theo thông tin công bố) |
| Tra cứu văn bản cũ bằng ngôn ngữ tự nhiên | Tất cả | 🟡 **Có nếu đã lên 5.0** | Không cần làm trùng bằng Claude |
| Truy vết ai làm gì | Tất cả | ✅ cho văn bản | Lưu ý giới hạn ở chức năng ủy quyền (mục 2.1) |
| Kết nối dữ liệu với hệ thống khác | — | ❓ | Không có API công khai, phải làm việc với VNPT |

## 4. Kết luận và tác động đến đề xuất

1. **iOffice mạnh ở lớp văn bản, yếu ở lớp hồ sơ nghiệp vụ và số liệu.** Điều này khớp với mô hình 3 lớp trong đề xuất. Lớp 2 (theo dõi hồ sơ, số liệu) **không trùng** với iOffice.
2. **Tận dụng iOffice trước khi xây mới:**
   - Thống nhất dùng "Hồ sơ công việc" đặt tên theo mã hồ sơ (`UV-001`…) để gom văn bản.
   - Dùng "Văn bản theo dõi" và hạn xử lý cho văn bản.
   - Dùng phân hệ công việc và lịch (nếu có) để nhắc việc định kỳ.

   Nếu các chức năng này đáp ứng tốt, phạm vi Lớp 2 thu hẹp xuống còn **sổ số liệu** (vốn ứng, NOXH) và **trạng thái hồ sơ nhiều bước**.
3. **Nếu Nghệ An đã lên bản 5.0:** việc tra cứu văn bản nên dùng ChatBot của iOffice, dữ liệu nằm tại VNPT trong nước. Claude chỉ nên dùng cho dựng dự thảo và tổng hợp, hạn chế gửi nội dung văn bản ra nước ngoài.
4. **Kết nối:** chưa có API công khai, nên giai đoạn đầu dùng **file xuất định kỳ** (nếu iOffice xuất được). Kết nối tự động chỉ làm khi VNPT xác nhận bằng văn bản. Không dùng tự động hóa thao tác trên giao diện.
5. **Lưu ý kiểm soát nội bộ:** ở chức năng ủy quyền, nhật ký ghi tên người ủy quyền, nên khi cần truy vết phải đối chiếu thêm văn bản ủy quyền.

## 5. Câu hỏi cần VNPT Nghệ An xác nhận

Các câu hỏi này đã bổ sung vào Phần 5 của `cau-hoi-trao-doi-khao-sat-v1.md`, từ câu 5.10.

1. Quỹ đang dùng phiên bản iOffice nào? Nghệ An có lộ trình nâng cấp lên 5.0 không, khi nào, có phát sinh chi phí cho Quỹ không?
2. Phân hệ quản lý công việc có hỗ trợ giao việc nhiều bước, việc lặp lại định kỳ, checklist không?
3. "Hồ sơ công việc" có chia sẻ được giữa nhiều người, nhiều phòng không?
4. Danh sách văn bản đến, văn bản đi và báo cáo thống kê có **xuất được ra Excel** không, gồm những cột nào?
5. Có API, webhook hoặc kết nối qua LGSP để hệ thống khác **đọc** danh sách văn bản và hạn xử lý không? Điều kiện, thủ tục, chi phí?
6. Quỹ có đang nhận nhiệm vụ của UBND tỉnh qua phân hệ Chỉ đạo điều hành không?
7. ChatBot AI và OCR của bản 5.0 xử lý dữ liệu ở đâu: máy chủ VNPT trong nước, hay có gọi dịch vụ AI bên ngoài?

## Nguồn tham khảo

- [Tham luận Hệ thống quản lý văn bản VNPT iOffice 5.0 — VNPT An Giang (2025)](https://dti.angiang.gov.vn/sites/default/files/2025-02/TLHN/TL/Tham%20luan-trien%20khai%20he%20thong%20QLVB-iOffice%205.0-VNPT.pdf)
- [Hướng dẫn sử dụng VNPT-iOffice 4.0 — vai trò văn thư (Sở KH&CN Phú Thọ)](https://sokhoahoccongnghe.phutho.gov.vn/Uploads/files/phu%20luc%201_%20qlvbdh-vanthu.pdf)
- [Hướng dẫn sử dụng VNPT-iOffice 4.0 — vai trò lãnh đạo (Sở KH&CN Phú Thọ)](https://sokhoahoccongnghe.phutho.gov.vn/Uploads/files/phu%20luc%203_%20qlvbdh-lanhdao.pdf)
- [Hướng dẫn sử dụng cho văn thư — An Giang (2025)](https://angiang.gov.vn/sites/default/files/2025-05/HDSD%20-%20VanThu.pdf)
- [VNPT iOffice phát huy hiệu quả tại thị trường trong nước và nước ngoài — SGGP](https://www.sggp.org.vn/vnpt-ioffice-phat-huy-hieu-qua-tai-thi-truong-trong-nuoc-va-nuoc-ngoai-post692092.html)
- [VNPT đồng hành cùng Nghệ An xây dựng Smart City — Báo Đầu tư](https://baodautu.vn/batdongsan/vnpt-dong-hanh-cung-nghe-an-xay-dung-smart-city-d68593.html)
- [VNPT Digital Workplace — case study](https://global.vnpt.vn/en/case-studies/digital-workplace)
- [VNPT iOffice 4.1 — App Store](https://apps.apple.com/vn/app/id1532166133)
