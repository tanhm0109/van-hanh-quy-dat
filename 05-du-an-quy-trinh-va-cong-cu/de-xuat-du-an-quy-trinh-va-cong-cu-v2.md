# ĐỀ XUẤT DỰ ÁN

## Chuẩn hóa quy trình làm việc và triển khai công cụ hỗ trợ quản lý công việc tại Quỹ phát triển đất Nghệ An

| | |
|---|---|
| **Kính gửi** | Ban Giám đốc Quỹ phát triển đất Nghệ An |
| **Đơn vị/người đề xuất** | `[Tên đơn vị / cá nhân đề xuất]` |
| **Phiên bản** | v2 — dự thảo để trao đổi, ngày ___/___/2026. Bổ sung so với v1: các phương án triển khai theo bậc, ưu tiên phương án đơn giản, ít chi phí (mục 5.5) |
| **Tài liệu kèm theo** | Bộ câu hỏi trao đổi, khảo sát (`cau-hoi-trao-doi-khao-sat-v1.md`); Đánh giá tính năng iOffice (`danh-gia-tinh-nang-ioffice-v1.md`) |

---

## 1. Sự cần thiết

Quỹ phát triển đất Nghệ An (sau đây gọi là Quỹ) đang thực hiện **13 đầu việc thuộc 4 nhóm**:

| Nhóm | Nội dung | Số đầu việc |
|---|---|---|
| I | Nghiệp vụ Quỹ phát triển đất: kế hoạch ứng vốn, thẩm định hồ sơ ứng vốn, theo dõi thu hồi vốn ứng | 3 |
| II | Quỹ nhà ở và dự án nhà ở xã hội (NOXH): khảo sát khu đất, thẩm tra thiết kế – dự toán, xét duyệt thuê và vận hành | 3 |
| III | Tổ chức, hành chính: đề án vị trí việc làm (VTVL), tự chủ, quy chế; mua sắm, sửa chữa tài sản công; báo cáo định kỳ và đột xuất | 4 |
| IV | Công tác Đảng, đoàn thể: sinh hoạt Chi bộ, báo cáo viên, kiểm tra giám sát và xếp loại đảng viên | 3 |

Hệ thống quản lý văn bản và điều hành **iOffice (VNPT)** đang được dùng hiệu quả cho văn bản đến, văn bản đi, luân chuyển, giao xử lý và ký số. Tuy vậy, qua rà soát sơ bộ, vẫn còn một số khoảng trống mà iOffice không được thiết kế để giải quyết:

1. **Hồ sơ nghiệp vụ nhiều bước khó theo dõi.** Một hồ sơ ứng vốn đi qua 6–7 bước, từ tiếp nhận, thẩm định, trình duyệt, quyết định, hợp đồng, giải ngân đến thu hồi, và phát sinh nhiều văn bản. iOffice theo dõi được từng văn bản nhưng chưa cho thấy **cả hồ sơ đang ở bước nào, ai đang giữ, còn thiếu gì**.
2. **Số liệu nghiệp vụ phân tán.** Số liệu vốn ứng, tuổi nợ và NOXH nằm rải rác trong file của từng cá nhân. Mỗi kỳ báo cáo phải tổng hợp thủ công và dễ lệch số giữa các báo cáo.
3. **Quy trình, biểu mẫu chưa được chuẩn hóa thành văn bản dùng chung.** Thời gian đào tạo người mới phụ thuộc vào kinh nghiệm của người cũ.
4. **Khối lượng soạn thảo lớn và lặp lại.** Báo cáo tháng, quý, năm; báo cáo đột xuất theo yêu cầu các Sở, ngành; Báo cáo viên hạn ngày 25 hằng tháng.

> **Lưu ý:** các nhận định trên được rút ra từ danh mục đầu việc do Quỹ cung cấp. Đề nghị Quỹ xác nhận hoặc điều chỉnh tại buổi trao đổi (xem bộ câu hỏi kèm theo).

## 2. Mục tiêu

### 2.1. Mục tiêu chung

Chuẩn hóa quy trình cho 13 đầu việc và triển khai bộ công cụ hỗ trợ **vận hành song song, bổ trợ cho iOffice**. Các công cụ này giúp Quỹ theo dõi hồ sơ, quản lý số liệu tập trung và giảm thời gian soạn thảo, đồng thời bảo đảm an toàn dữ liệu.

### 2.2. Mục tiêu cụ thể

| TT | Mục tiêu | Chỉ số đo (giá trị hiện trạng sẽ đo trong giai đoạn khảo sát) |
|---|---|---|
| 1 | 100% đầu việc có quy trình, checklist và biểu mẫu thống nhất | Số đầu việc có quy trình được Giám đốc ban hành / 13 |
| 2 | Theo dõi được trạng thái mọi hồ sơ ứng vốn, NOXH, mua sắm | Tỷ lệ hồ sơ có trạng thái cập nhật; số hồ sơ trễ hạn |
| 3 | Số liệu vốn ứng và tuổi nợ có **một nguồn duy nhất** | Số lần lệch số liệu giữa các báo cáo trong kỳ |
| 4 | Rút ngắn thời gian lập báo cáo định kỳ | Số giờ công cho một báo cáo quý: hiện trạng `[…]` → mục tiêu `[…]` |
| 5 | Không để lộ dữ liệu cá nhân và dữ liệu Đảng | Số sự cố an toàn dữ liệu = 0 |

## 3. Phạm vi

**Trong phạm vi:**
- Chuẩn hóa quy trình cho cả 13 đầu việc.
- Triển khai công cụ **theo giai đoạn**, thí điểm trước ở nhóm I (vốn ứng) và đầu việc III.3 (báo cáo định kỳ).

**Ngoài phạm vi:**
- Thay thế hoặc sửa đổi iOffice.
- Thay đổi quy trình ký số và phát hành văn bản.
- Phần mềm kế toán.
- Mọi việc xử lý tài liệu mật.

## 4. Nguyên tắc thiết kế

1. **iOffice là nguồn văn bản chính thức duy nhất.** Mọi văn bản phát hành, ký số và lưu trữ chính thức vẫn đi trên iOffice. Công cụ mới chỉ ghi trạng thái và trích dẫn số, ký hiệu văn bản iOffice; không phát hành văn bản song song.
2. **Con người quyết định, công cụ hỗ trợ.** Công cụ trí tuệ nhân tạo (AI) chỉ dựng dự thảo, rà checklist và tổng hợp số liệu. Chuyên viên chịu trách nhiệm kiểm tra; người có thẩm quyền ký.
3. **Không bịa số liệu, không bịa căn cứ pháp lý.** Số tiền và tuổi nợ được tính bằng chương trình từ dữ liệu gốc. Dự thảo phải chừa chỗ trống rõ ràng cho thông tin còn thiếu, và căn cứ pháp lý phải được người phụ trách đối chiếu hiệu lực.
4. **Dữ liệu nằm trong nước, do Quỹ kiểm soát.** Máy chủ và cơ sở dữ liệu đặt tại Quỹ hoặc trung tâm dữ liệu trong nước.
5. **Phân loại dữ liệu trước khi đưa vào công cụ:**

   | Loại dữ liệu | Cách xử lý |
   |---|---|
   | Văn bản hành chính thông thường, quy trình, số liệu tổng hợp | Được dùng với công cụ AI (khi lãnh đạo chấp thuận) |
   | Hồ sơ đăng ký thuê NOXH có thông tin cá nhân | Xử lý tại máy chủ nội bộ. Chỉ đưa ra ngoài dữ liệu **đã che danh tính** |
   | Hồ sơ đảng viên, tài liệu nội bộ của Đảng, tài liệu mật | **Không đưa vào công cụ AI.** Lưu riêng, chỉ Chi ủy truy cập |

6. **Không bắt mọi người dùng công cụ kỹ thuật.** Phân tầng người dùng theo vai trò (mục 5.3).

## 5. Giải pháp đề xuất

### 5.1. Mô hình tổng thể: 3 lớp

> Đây là **mô hình đích**, không phải việc phải làm ngay. Quỹ triển khai dần theo các bậc ở mục 5.5. Phần lớn nhu cầu có thể được giải quyết ở các bậc đầu mà chưa cần máy chủ hay phần mềm mới.

```
┌───────────────────────────────────────────────────────────────┐
│ LỚP 1 — iOffice (VNPT)                                        │
│ Văn bản đến/đi · giao xử lý · hạn xử lý · ký số · lưu trữ     │
└───────────────────────────┬───────────────────────────────────┘
                            │ số/ký hiệu văn bản làm khóa liên kết
┌───────────────────────────▼───────────────────────────────────┐
│ LỚP 2 — Hệ thống theo dõi hồ sơ & số liệu nghiệp vụ           │
│ (máy chủ nội bộ của Quỹ)                                      │
│ • Sổ hồ sơ: trạng thái từng bước, người phụ trách, hạn        │
│ • Sổ theo dõi vốn ứng, tuổi nợ, phân loại nợ                  │
│ • Dữ liệu NOXH (che danh tính khi khai thác)                  │
│ • Lịch việc định kỳ (báo cáo tháng/quý/năm, ngày 25)          │
│ • Nhật ký thao tác: ai sửa gì, khi nào                        │
└───────────────────────────┬───────────────────────────────────┘
┌───────────────────────────▼───────────────────────────────────┐
│ LỚP 3 — Sổ tay quy trình & trợ lý soạn thảo                   │
│ • Quy trình, checklist, biểu mẫu 13 đầu việc                  │
│ • Trợ lý AI (Claude Code) kết nối Lớp 2: rà checklist,        │
│   dựng dự thảo tờ trình/báo cáo/công văn, xuất file Word      │
└───────────────────────────────────────────────────────────────┘
```

### 5.2. Các thành phần

| Thành phần | Chức năng | Ghi chú kỹ thuật (chi tiết tại Phụ lục A) |
|---|---|---|
| Sổ tay quy trình | Quy trình, checklist, biểu mẫu cho 13 đầu việc | Đã có bản khung; cần Quỹ góp ý và ban hành |
| Cơ sở dữ liệu nghiệp vụ | Hồ sơ, khoản ứng, trạng thái, nhật ký | Đặt trên máy chủ nội bộ |
| Màn hình nhập liệu đơn giản | Để chuyên viên cập nhật số liệu và trạng thái | Giao diện web tiếng Việt hoặc Excel mẫu |
| Bộ kết nối dữ liệu | Cho trợ lý AI đọc dữ liệu **theo đúng quyền** của từng người | Công nghệ MCP; tự che dữ liệu cá nhân |
| Trợ lý soạn thảo | Dựng dự thảo, rà checklist, tổng hợp báo cáo | Claude Code, chỉ cài cho đầu mối được phân công |
| Kết nối iOffice | Lấy danh sách văn bản đến và hạn xử lý | Qua API của VNPT nếu có, nếu không thì qua file xuất định kỳ |

### 5.3. Phân tầng người dùng

| Tầng | Đối tượng | Công cụ sử dụng | Nhiệm vụ |
|---|---|---|---|
| 1 | Ban Giám đốc, HĐQL Quỹ | **iOffice** (như hiện nay) và báo cáo tổng hợp | Chỉ đạo, cho ý kiến, ký |
| 2 | Đầu mối số của mỗi phòng (1–2 người) | Trợ lý soạn thảo và hệ thống theo dõi | Dựng dự thảo, tổng hợp số liệu |
| 3 | Chuyên viên | Màn hình nhập liệu | Nhập số liệu gốc, cập nhật trạng thái hồ sơ |
| 4 | Quản trị hệ thống (kiêm nhiệm) | Máy chủ, phân quyền | Cấp và thu hồi quyền, sao lưu, cập nhật quy trình |

### 5.4. Ví dụ luồng hồ sơ ứng vốn sau khi triển khai

```
Văn bản đề nghị đến qua iOffice
  → Chuyên viên mở hồ sơ trên hệ thống theo dõi (gắn số văn bản iOffice)
  → Trợ lý rà checklist pháp lý, liệt kê giấy tờ còn thiếu
  → Hệ thống trả dư nợ, nợ quá hạn hiện có của đơn vị đề nghị
  → Trợ lý dựng dự thảo Báo cáo thẩm định → chuyên viên kiểm tra, chỉnh sửa
  → Trình trên iOffice → lãnh đạo cho ý kiến, ký số
  → Cập nhật số Quyết định → hệ thống tự theo dõi hạn hoàn trả, tuổi nợ
```

### 5.5. Các phương án triển khai theo bậc

**Nguyên tắc:**
- Làm từ **đơn giản, ít tốn kém** đến phức tạp.
- Bậc sau xây trên kết quả của bậc trước, không bỏ đi việc đã làm.
- **Chỉ lên bậc khi bậc hiện tại không còn đáp ứng**, theo tiêu chí chuyển bậc tại mục 5.5.3.

#### 5.5.1. Mô tả các phương án

**Phương án 0 — Chuẩn hóa quy trình và khai thác hết iOffice.** Không mua sắm, không thêm công nghệ.
- Ban hành sổ tay quy trình, checklist, biểu mẫu cho 13 đầu việc. Sổ tay ở dạng file Word/PDF, lưu ở thư mục dùng chung và đính kèm trên iOffice.
- Thống nhất cách dùng iOffice:
  - mỗi hồ sơ nghiệp vụ có một "Hồ sơ công việc" đặt tên theo mã thống nhất, ví dụ `UV-2026-001`;
  - văn bản quan trọng được đưa vào "Văn bản theo dõi", ghi đủ hạn xử lý;
  - dùng lịch công tác hoặc phân hệ công việc (nếu có) để nhắc các mốc định kỳ, ví dụ báo cáo tháng, quý và Báo cáo viên ngày 25.
- Ban hành bảng phân công chủ trì, phối hợp, phê duyệt cho từng đầu việc.
- **Giải quyết:** quy trình chưa thống nhất; gom văn bản theo hồ sơ; nhắc hạn.

**Phương án 1 — Thêm sổ theo dõi bằng Excel dùng chung.** Dùng phần mềm văn phòng sẵn có.
- Lập 3 sổ Excel mẫu, có công thức tính sẵn và khóa các ô công thức:
  1. **Sổ theo dõi hồ sơ:** mỗi dòng một hồ sơ, gồm mã hồ sơ, bước hiện tại, người đang xử lý, hạn, số văn bản iOffice liên quan;
  2. **Sổ theo dõi vốn ứng:** khoản ứng, số tiền, ngày ứng, hạn hoàn trả, đã thu; công thức tự tính tuổi nợ và phân loại trong hạn/quá hạn;
  3. **Lịch việc định kỳ:** báo cáo, người phụ trách, hạn, tình trạng.
- Lưu trên **thư mục dùng chung trong mạng nội bộ**, dùng tính năng chia sẻ thư mục có sẵn của Windows trên một máy cơ quan.
- Quy tắc vận hành:
  - **mỗi sổ có một người chủ sổ** được quyền sửa, người khác chỉ xem;
  - các phòng gửi số liệu cho chủ sổ theo mẫu;
  - sao lưu hằng tuần ra ổ cứng rời.
- **Giải quyết thêm:** số liệu vốn ứng có một nguồn duy nhất; biết hồ sơ đang ở bước nào; báo cáo định kỳ lấy số từ sổ thay vì đi hỏi từng phòng.

**Phương án 2 — Thêm trợ lý AI cho 1–2 đầu mối.** Không cần máy chủ.
- Cài Claude Code trên máy của 1–2 đầu mối, ví dụ Phòng Nghiệp vụ và Phòng HC-TH.
- Trợ lý đọc sổ tay quy trình và sổ Excel (chỉ phần dữ liệu được phép), rồi:
  - rà checklist hồ sơ;
  - dựng dự thảo báo cáo thẩm định, tờ trình, báo cáo định kỳ, công văn đôn đốc;
  - xuất file Word để đưa lên iOffice trình ký.
- Số liệu như tuổi nợ, tổng hợp kỳ được **tính bằng công thức Excel hoặc chương trình nhỏ chạy trên máy**, trợ lý không tự tính.
- **Điều kiện bắt buộc:** Ban Giám đốc chấp thuận phạm vi dữ liệu (câu hỏi 6.1). Dữ liệu NOXH có thông tin cá nhân và dữ liệu Đảng **không** dùng ở phương án này.
- **Giải quyết thêm:** giảm thời gian soạn thảo các văn bản lặp lại.

**Phương án 3 — Máy chủ nhỏ nội bộ.** Chỉ triển khai khi sổ Excel không còn đáp ứng.
- Một máy tính để bàn hoặc thiết bị lưu trữ mạng chạy liên tục tại Quỹ, đặt cơ sở dữ liệu thay cho các sổ Excel.
- Có màn hình nhập liệu đơn giản, phân quyền theo phòng và nhật ký thao tác.
- Trợ lý AI kết nối dữ liệu dùng chung qua bộ kết nối (MCP) theo đúng quyền của từng người. Dữ liệu NOXH được che danh tính.
- **Giải quyết thêm:** nhiều người cùng cập nhật không bị ghi đè; phân quyền; truy vết.

**Phương án 4 — Kết nối iOffice, mở rộng toàn Quỹ.** Phụ thuộc VNPT.
- Tự động lấy danh sách văn bản đến và hạn xử lý từ iOffice qua API hoặc LGSP (nếu VNPT hỗ trợ).
- Mở màn hình nhập liệu cho toàn bộ chuyên viên. Mở rộng sang nhóm II (NOXH).

#### 5.5.2. So sánh các phương án

| Tiêu chí | PA 0 | PA 1 | PA 2 | PA 3 | PA 4 |
|---|---|---|---|---|---|
| Chi phí mua sắm | Không | Không (dùng Office sẵn có); ổ cứng sao lưu nếu chưa có | Thuê bao trợ lý AI cho 1–2 tài khoản `[…]` | Thiết bị máy chủ `[…]` và công xây dựng `[…]` | Phí kết nối của VNPT (nếu có) `[…]` và công xây dựng `[…]` |
| Công nghệ mới phải học | Không | Không | Trợ lý AI (chỉ đầu mối) | Máy chủ, cơ sở dữ liệu (người quản trị) | Kết nối hệ thống |
| Thủ tục mua sắm | Không | Không hoặc rất nhỏ | Có (thuê dịch vụ) | Có | Có |
| Thời gian bắt đầu được | Ngay | Ngay | Sau khi có chấp thuận 6.1 và thủ tục mua | Sau khảo sát, có dự toán | Sau khi VNPT xác nhận |
| Cần người kỹ thuật | Không | Không | Không (có hướng dẫn) | Có (kiêm nhiệm hoặc thuê) | Có, kèm VNPT |
| Quy trình thống nhất | ✅ | ✅ | ✅ | ✅ | ✅ |
| Gom văn bản theo hồ sơ | ✅ (trên iOffice) | ✅ | ✅ | ✅ | ✅ |
| Biết hồ sơ ở bước nào | ❌ | ✅ (thủ công) | ✅ (thủ công) | ✅ | ✅ (một phần tự động) |
| Số liệu vốn ứng tập trung | ❌ | ✅ | ✅ | ✅ | ✅ |
| Giảm thời gian soạn thảo | ❌ | ❌ | ✅ | ✅ | ✅ |
| Nhiều người cùng cập nhật an toàn | — | ⚠️ một người chủ sổ | ⚠️ một người chủ sổ | ✅ | ✅ |
| Phân quyền chi tiết, nhật ký | — | ❌ | ❌ | ✅ | ✅ |
| Rủi ro chính | Quy trình ban hành nhưng không được áp dụng | Ghi đè file, mất dữ liệu nếu không sao lưu | Dữ liệu gửi ra nước ngoài; dự thảo sai nếu không kiểm tra | Phụ thuộc người quản trị | Phụ thuộc nhà cung cấp |

#### 5.5.3. Tiêu chí chuyển bậc

| Chuyển | Khi nào nên chuyển |
|---|---|
| PA 0 → PA 1 | Ngay sau khi ban hành quy trình. PA 1 gần như không tốn chi phí và giải quyết vấn đề số liệu phân tán |
| PA 1 → PA 2 | Đã có chấp thuận phạm vi dữ liệu (câu 6.1); sổ Excel đã được cập nhật đều; khối lượng soạn thảo lặp lại còn lớn |
| PA 2 → PA 3 | Có **từ hai dấu hiệu trở lên**: nhiều người cần cùng sửa một sổ và thường xảy ra ghi đè, lệch số; cần phân quyền theo phòng; cần nhật ký truy vết; số hồ sơ, khoản ứng vượt mức quản lý được bằng Excel (ngưỡng cụ thể `[…]`, chốt sau thí điểm) |
| PA 3 → PA 4 | VNPT xác nhận bằng văn bản có API hoặc kết nối LGSP, với chi phí và thủ tục chấp nhận được |

#### 5.5.4. Phương án đề xuất lựa chọn: PA 0 + PA 1 + PA 2

Gọi tắt là phương án **"iOffice + file văn phòng + trợ lý Claude Code"**.

1. **Triển khai ngay PA 0 và PA 1.** Không cần mua sắm, không phát sinh công nghệ, mà đã giải quyết được phần lớn khoảng trống nêu tại mục 1 (quy trình, gom hồ sơ, số liệu tập trung, nhắc hạn).
2. **Thí điểm PA 2 ở 1 đầu mối** trong 1–2 tháng nếu Ban Giám đốc chấp thuận phạm vi dữ liệu. Trợ lý xử lý trực tiếp trên file Excel, Word, PDF của Quỹ (mục 5.6). Đo thời gian lập báo cáo trước và sau để quyết định có nhân rộng không.
3. **PA 3 và PA 4 chưa đưa vào kế hoạch kinh phí năm đầu.** Chỉ đề xuất khi đạt tiêu chí chuyển bậc, có số liệu thí điểm làm căn cứ.

### 5.6. Mô hình làm việc của phương án được chọn

#### 5.6.1. Trợ lý làm gì với file

| Việc | Đầu vào | Trợ lý thực hiện | Đầu ra |
|---|---|---|---|
| Cập nhật sổ theo dõi | Chứng từ (ủy nhiệm chi, giấy nộp tiền, QĐ, phụ lục hợp đồng) dạng PDF, Word, ảnh hoặc nội dung gõ vào | Đọc chứng từ, trích số liệu, **trình bảng thay đổi để chuyên viên xác nhận**, rồi mới ghi vào sổ Excel | Sổ Excel đã cập nhật; bản sao lưu; dòng nhật ký ghi rõ chứng từ |
| Tính tuổi nợ, phân loại nợ | Sổ theo dõi vốn ứng, mốc chốt số liệu | Chạy công cụ tính (chương trình nhỏ, không phải AI tự tính), kiểm tra dữ liệu bất thường | Bảng tuổi nợ (Excel); danh sách khoản sắp đến hạn, quá hạn; cảnh báo dữ liệu |
| Dựng văn bản | Kết quả tính, biểu mẫu, checklist, văn bản đến từ iOffice (bản tải về) | Dựng dự thảo theo biểu mẫu của Quỹ, chừa trống thông tin còn thiếu | Dự thảo Word (chỗ trống tô vàng), PDF nếu cần |
| Báo cáo định kỳ, đột xuất | Các sổ theo dõi, biểu số liệu các phòng gửi (Excel), đề cương của Sở, ngành | Tổng hợp số liệu, đối chiếu giữa các nguồn, dựng báo cáo theo đề cương | Báo cáo Word kèm biểu Excel |
| Rà soát hồ sơ | Hồ sơ đề nghị (PDF, Word) | Đối chiếu checklist pháp lý, liệt kê giấy tờ thiếu | Phiếu rà soát checklist |

#### 5.6.2. Quy trình một vòng làm việc

```
iOffice ──tải văn bản/chứng từ về──► Thư mục hồ sơ trên máy đầu mối
                                       │
                         Chuyên viên gọi lệnh trợ lý
                         (/cap-nhat-so-von-ung, /theo-doi-no-von-ung, /xuat-van-ban…)
                                       │
                  ┌────────────────────┼─────────────────────┐
                  ▼                    ▼                     ▼
          Sổ Excel cập nhật     Bảng tính tuổi nợ      Dự thảo Word/PDF
          (sao lưu + nhật ký)   (Excel)                (chỗ trống tô vàng)
                                       │
                         Chuyên viên kiểm tra, hoàn thiện
                                       │
iOffice ◄──────── trình ký, ký số, phát hành ─────────┘
```

#### 5.6.3. Kiểm soát

- **Số liệu do chương trình tính** theo quy tắc cố định (ví dụ khung phân nhóm nợ A–F). Trợ lý AI không tự cộng trừ. Khi Quỹ ban hành quy chế phân loại nợ chính thức, chỉ cần sửa một chỗ.
- **Không ghi vào sổ khi chưa được xác nhận.** Mỗi lần ghi bắt buộc có số hiệu chứng từ, tự sao lưu và ghi nhật ký. Nếu file đang có người mở trên Excel thì công cụ dừng lại, tránh ghi đè.
- **Mỗi sổ một người chủ sổ.** Sổ đặt trên thư mục dùng chung; người khác chỉ xem.
- **Văn bản xuất ra luôn là dự thảo.** Việc ký và phát hành vẫn đi trên iOffice.
- **Phạm vi dữ liệu theo mục 4.5.** Không dùng trợ lý với hồ sơ NOXH có thông tin cá nhân và tài liệu Đảng.

#### 5.6.4. Hiện trạng chuẩn bị

Đã có bản chạy thử cho đầu việc I.3 (theo dõi thu hồi vốn ứng):
- sổ theo dõi vốn ứng mẫu dạng Excel;
- công cụ cập nhật sổ có nhật ký;
- công cụ tính tuổi nợ, xuất bảng tổng hợp;
- công cụ xuất văn bản Word/PDF.

Các công cụ này đã được kiểm tra trên dữ liệu giả lập. Sau khảo sát sẽ điều chỉnh theo sổ sách thực tế của Quỹ, rồi mở rộng sang báo cáo định kỳ (III.3) và thẩm định ứng vốn (I.2).

**Yêu cầu máy tính đầu mối:**
- Windows hoặc macOS, có Internet;
- Python (miễn phí);
- LibreOffice (miễn phí, chỉ cần khi muốn xuất PDF tự động);
- tài khoản trợ lý Claude.

## 6. Nội dung công việc và sản phẩm bàn giao

| Giai đoạn | Nội dung | Sản phẩm |
|---|---|---|
| **0. Khảo sát** | Làm việc với Ban Giám đốc và các phòng; khảo sát iOffice, hạ tầng CNTT; thu thập biểu mẫu, quy chế hiện hành; đo hiện trạng các chỉ số tại mục 2.2 | Báo cáo khảo sát hiện trạng; danh mục yêu cầu đã thống nhất |
| **1. Chuẩn hóa quy trình** | Hoàn thiện quy trình, checklist, biểu mẫu cho 13 đầu việc; phân công chủ trì, phối hợp, phê duyệt | Bộ quy trình trình Giám đốc ban hành; ma trận phân công |
| **2. Thí điểm (PA 0, PA 1, PA 2)** | Áp dụng quy ước dùng iOffice; đưa vào sử dụng 3 sổ Excel dùng chung cho nhóm I và đầu việc III.3; thí điểm trợ lý AI ở 1 đầu mối (nếu được chấp thuận); đào tạo; chạy song song với cách làm cũ | Quy ước dùng iOffice; bộ sổ Excel mẫu; tài liệu hướng dẫn; báo cáo đánh giá thí điểm kèm đề xuất có lên bậc hay không |
| **3. Mở rộng (PA 3, PA 4, chỉ khi đạt tiêu chí mục 5.5.3)** | Máy chủ nội bộ thay sổ Excel; mở rộng sang nhóm II (có che dữ liệu), III.2 và III.4; kết nối iOffice | Hệ thống đầy đủ; báo cáo nghiệm thu |
| **4. Chuẩn hóa vận hành** | Dự thảo Quy chế sử dụng hệ thống và bảo vệ dữ liệu; bàn giao quản trị | Quy chế; hồ sơ bàn giao; kế hoạch duy trì |

**Thời gian dự kiến:** `[…]` tháng. Sẽ chốt sau giai đoạn khảo sát, tùy thuộc hạ tầng và phản hồi của VNPT.

## 7. Tổ chức thực hiện

| Bên | Trách nhiệm |
|---|---|
| **Ban Giám đốc Quỹ** | Phê duyệt chủ trương, phạm vi dữ liệu được dùng với công cụ AI; cử Tổ triển khai; ban hành quy trình và quy chế |
| **Tổ triển khai của Quỹ** (đề nghị gồm đại diện Ban Giám đốc, mỗi phòng 1 đầu mối, 1 người kiêm quản trị) | Cung cấp thông tin, góp ý quy trình, tham gia thí điểm, nghiệm thu |
| **Đơn vị/người đề xuất** | Khảo sát, thiết kế, xây dựng, đào tạo, hỗ trợ vận hành giai đoạn đầu |
| **VNPT Nghệ An** | Cung cấp thông tin và hỗ trợ kết nối iOffice (nếu có API hoặc chức năng xuất dữ liệu) |
| **Sở Khoa học và Công nghệ** (nếu cần) | Hướng dẫn về nền tảng dùng chung của tỉnh và yêu cầu an toàn thông tin |

## 8. Kinh phí dự kiến

Chưa đủ cơ sở để lập dự toán. Kinh phí được tách theo phương án để Quỹ chỉ chi khi cần lên bậc. Các khoản sẽ được lượng hóa sau khảo sát.

| Khoản mục | Phương án | Ghi chú |
|---|---|---|
| Công khảo sát, chuẩn hóa quy trình, lập sổ Excel mẫu, đào tạo | PA 0, PA 1 | `[…]`; tùy hình thức hợp tác (câu hỏi 7.1) |
| Ổ cứng rời để sao lưu (nếu chưa có) | PA 1 | `[…]` |
| Thuê bao trợ lý AI cho 1–2 đầu mối (gói dành cho tổ chức) | PA 2 | `[…]` |
| Thiết bị máy chủ nội bộ, hoặc thuê máy chủ ảo trong nước | PA 3 | `[…]`; chưa đưa vào năm đầu |
| Công xây dựng cơ sở dữ liệu, màn hình nhập liệu, bộ kết nối | PA 3 | `[…]`; chưa đưa vào năm đầu |
| Chi phí kết nối iOffice (nếu VNPT tính phí) | PA 4 | `[…]`; chưa đưa vào năm đầu |
| Duy trì, vận hành hằng năm | PA 2 trở lên | `[…]` |

Việc mua sắm hoặc thuê dịch vụ sẽ thực hiện theo trình tự chủ trương → dự toán → kế hoạch lựa chọn nhà thầu (KHLCNT) → hợp đồng → nghiệm thu → thanh quyết toán, phù hợp quy định về đấu thầu và tài sản công.

## 9. Rủi ro và biện pháp

| Rủi ro | Biện pháp |
|---|---|
| Lộ dữ liệu cá nhân hoặc dữ liệu Đảng | Phân loại dữ liệu (mục 4.5); chặn kỹ thuật ở cấp hệ thống; che danh tính; nhật ký truy cập; quy chế sử dụng |
| Phát sinh "hai luồng" song song với iOffice, gây nhập liệu trùng | Chỉ ghi trạng thái và số văn bản, không phát hành song song; nhập liệu tối thiểu |
| AI dựng dự thảo sai số liệu hoặc sai căn cứ | Số liệu tính bằng chương trình; căn cứ chỉ lấy từ danh mục đã xác minh; chuyên viên bắt buộc kiểm tra |
| Cán bộ không sử dụng | Phân tầng người dùng; thí điểm hẹp; chọn đầu mối có thiện chí; đào tạo kèm cặp |
| Phụ thuộc một người quản trị | Tài liệu hóa; đào tạo ít nhất 2 người; hợp đồng hỗ trợ |
| VNPT không hỗ trợ kết nối iOffice | Dùng phương án file xuất định kỳ; không tự động thao tác trên giao diện iOffice |
| Quy định pháp luật về dữ liệu, AI trong khu vực công thay đổi | Rà soát định kỳ; xin ý kiến cơ quan chuyên môn trước khi mở rộng |

## 10. Đề nghị

Kính đề nghị Ban Giám đốc Quỹ:

1. **Đồng ý chủ trương** triển khai giai đoạn 0 (khảo sát), giai đoạn 1 (chuẩn hóa quy trình), và áp dụng **Phương án 0 và Phương án 1** (mục 5.5). Hai phương án này không phát sinh mua sắm, không phát sinh công nghệ mới.
2. **Bố trí buổi làm việc** với Ban Giám đốc và các phòng để trao đổi theo bộ câu hỏi kèm theo. Thời gian đề nghị: `[…]`.
3. **Cử Tổ triển khai** và đầu mối liên hệ của từng phòng.
4. **Cho ý kiến về phạm vi dữ liệu** được phép sử dụng với công cụ AI (mục 4.5), làm cơ sở để quyết định thí điểm Phương án 2.

---

## Phụ lục A. Ghi chú kỹ thuật (dành cho bộ phận CNTT / VNPT)

- **Máy chủ nội bộ:** hệ điều hành Linux. Cơ sở dữ liệu PostgreSQL, sao lưu hằng ngày ra thiết bị riêng.
- **Bộ kết nối dữ liệu:** dùng chuẩn Model Context Protocol (MCP), chạy trên máy chủ nội bộ qua HTTP trong mạng LAN. Mỗi người dùng một khóa truy cập riêng. Hệ thống phân quyền theo vai trò, ghi nhật ký mọi thao tác ghi, và che danh tính dữ liệu NOXH trước khi trả kết quả.
- **Trợ lý soạn thảo:** Claude Code cài trên máy đầu mối, dùng cấu hình quản lý tập trung (managed settings) để chặn truy cập thư mục dữ liệu cá nhân và dữ liệu Đảng.
  - **Lưu ý:** nội dung trợ lý AI xử lý được gửi tới máy chủ của nhà cung cấp ở nước ngoài. Vì vậy chỉ dữ liệu đã được phân loại "được dùng" mới đi qua lớp này.
- **Kho quy trình:** quản lý phiên bản bằng Git trên máy chủ nội bộ (Gitea). Chỉ quản trị viên và đầu mối thao tác trực tiếp.
- **Kết nối iOffice**, theo thứ tự ưu tiên:
  1. API chính thức hoặc kết nối qua nền tảng tích hợp, chia sẻ dữ liệu (LGSP) của tỉnh;
  2. file Excel xuất định kỳ từ sổ văn bản đến;
  3. **không** dùng tự động hóa thao tác trên giao diện.

## Phụ lục B. Hiện trạng đã chuẩn bị

Bản khung đã dựng trong không gian làm việc gồm:
- danh mục 13 đầu việc kèm đầu vào, đầu ra;
- quy trình (README) cho từng đầu việc;
- checklist, biểu mẫu;
- lịch công việc định kỳ;
- quy ước soạn thảo văn bản;
- 8 lệnh trợ lý cho các đầu việc thường dùng: thẩm định ứng vốn, theo dõi nợ, báo cáo định kỳ, báo cáo đột xuất, sinh hoạt Chi bộ, Báo cáo viên, cập nhật sổ vốn ứng, xuất văn bản Word/PDF;
- bộ công cụ xử lý file: sổ vốn ứng Excel mẫu, cập nhật sổ có nhật ký, tính tuổi nợ, xuất Word/PDF (mục 5.6.4).

Bản khung này là **điểm xuất phát để Quỹ góp ý**, chưa phải quy trình chính thức.

---

## THÔNG TIN CÒN THIẾU / CẦN NGƯỜI PHỤ TRÁCH XÁC MINH

1. Tên đơn vị/cá nhân đề xuất, thông tin liên hệ.
2. Cơ cấu phòng ban, số lượng nhân sự từng phòng của Quỹ.
3. Hiện trạng các chỉ số tại mục 2.2 (đo ở giai đoạn khảo sát).
4. Thời gian thực hiện và kinh phí (mục 6, mục 8).
5. Các chức năng iOffice đang dùng và khả năng kết nối, xuất dữ liệu (cần VNPT xác nhận).
6. Hạ tầng CNTT hiện có của Quỹ.
7. Ý kiến của Ban Giám đốc về phạm vi dữ liệu được dùng với công cụ AI.
8. Ngưỡng định lượng để chuyển từ sổ Excel lên máy chủ nội bộ (mục 5.5.3), chốt sau thí điểm.
9. Quỹ đã có bản quyền Microsoft Office và một máy tính có thể chia sẻ thư mục trong mạng nội bộ chưa (điều kiện của PA 1).

## CĂN CỨ PHÁP LÝ CẦN ĐỐI CHIẾU HIỆU LỰC

Các văn bản dưới đây **chưa có trong danh mục `00-tai-lieu-chung/can-cu-phap-ly.md`**. Cần xác minh trước khi đưa vào văn bản chính thức:

1. Luật Bảo vệ dữ liệu cá nhân và văn bản hướng dẫn; Nghị định 13/2023/NĐ-CP về bảo vệ dữ liệu cá nhân `[CẦN KIỂM TRA HIỆU LỰC]`.
2. Luật An ninh mạng; Nghị định 53/2022/NĐ-CP hướng dẫn Luật An ninh mạng (quy định lưu trữ dữ liệu tại Việt Nam) `[CẦN KIỂM TRA HIỆU LỰC]`.
3. Quy định về bảo đảm an toàn hệ thống thông tin theo cấp độ `[CẦN KIỂM TRA HIỆU LỰC]`.
4. Quy định về thuê dịch vụ công nghệ thông tin sử dụng ngân sách nhà nước `[CẦN KIỂM TRA HIỆU LỰC]`.
5. Quy định của Đảng về bảo vệ bí mật và quản lý tài liệu, hồ sơ đảng viên `[CẦN KIỂM TRA HIỆU LỰC]`.
6. Kế hoạch, chương trình chuyển đổi số của UBND tỉnh Nghệ An đang có hiệu lực `[CẦN BỔ SUNG BẢN THỰC TẾ]`.
7. Luật Đấu thầu; Luật Quản lý, sử dụng tài sản công. Đã có trong danh mục, trạng thái `[CẦN KIỂM TRA]`.
