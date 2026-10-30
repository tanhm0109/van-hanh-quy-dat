# I.3 — Theo dõi, kiểm tra và đôn đốc thu hồi vốn ứng

## Mục đích
Bảo toàn và quay vòng nguồn vốn của Quỹ: theo dõi từng khoản vốn ứng từ lúc
giải ngân đến khi thu hồi đủ, phát hiện sớm nguy cơ quá hạn và xử lý.

## Căn cứ
Hợp đồng ứng vốn và Quyết định ứng vốn từng hồ sơ (I.2); Quy chế ứng vốn và
hoàn trả vốn ứng của tỉnh; `00-tai-lieu-chung/can-cu-phap-ly.md` mục A.

## Đầu vào (Input)
- [ ] Báo cáo giải ngân định kỳ của đơn vị nhận vốn
- [ ] Hồ sơ quyết toán kinh phí bồi thường, GPMB
- [ ] Kết quả đấu giá quyền sử dụng đất / chứng từ thu tiền sử dụng đất
- [ ] Chứng từ hoàn trả vốn ứng (ủy nhiệm chi, giấy nộp tiền)
- [ ] Hợp đồng ứng vốn (để đối chiếu mốc hoàn trả)

## Công cụ theo dõi
Sổ Excel `bieu-mau/01-nghiep-vu-von-ung/so-theo-doi-von-ung.xlsx` (bản trống —
copy sang `ho-so/` để dùng thật) — mỗi khoản ứng một dòng, cập nhật tối thiểu
**hằng tháng**. Cập nhật và tính tuổi nợ bằng công cụ trong `cong-cu/`
(`/cap-nhat-so-von-ung`, `/theo-doi-no-von-ung`): mọi thay đổi có sao lưu và
nhật ký kèm chứng từ. Bản `.csv` cũ vẫn đọc được.

Trường dữ liệu: mã hồ sơ · đơn vị nhận vốn · dự án · số QĐ ứng vốn · số hợp
đồng · số tiền ứng · đã giải ngân · đã thu hồi · dư nợ · hạn hoàn trả theo hợp
đồng · số ngày quá hạn · nhóm nợ · nguồn hoàn trả · tình trạng dự án · ghi chú.

## Phân loại nợ theo tuổi nợ (khung đề xuất — Quỹ cần ban hành chính thức)

| Nhóm | Tình trạng | Hành động tối thiểu |
|---|---|---|
| A | Trong hạn, còn > 90 ngày | Theo dõi thường xuyên |
| B | Trong hạn, còn ≤ 90 ngày | Công văn nhắc trước hạn |
| C | Quá hạn ≤ 90 ngày | Công văn đôn đốc lần 1; làm việc trực tiếp |
| D | Quá hạn 91 – 180 ngày | Công văn đôn đốc lần 2; kiểm tra hiện trường; báo cáo HĐQL |
| E | Quá hạn 181 – 365 ngày | Báo cáo UBND tỉnh; đề xuất biện pháp xử lý; tạm dừng xem xét ứng vốn mới |
| F | Quá hạn > 365 ngày / khó thu hồi | Báo cáo UBND tỉnh và HĐQL; đề xuất phương án xử lý theo quy định |

> Khung trên là đề xuất nghiệp vụ, **không thay thế** quy định phân loại nợ
> trong Quy chế của tỉnh. Khi có quy chế chính thức, cập nhật lại bảng này.

## Quy trình

| Bước | Nội dung | Tần suất |
|---|---|---|
| 1 | Cập nhật số liệu giải ngân, thu hồi vào bảng theo dõi | Hằng tháng |
| 2 | Tính số ngày quá hạn, phân nhóm nợ | Hằng tháng |
| 3 | Lập danh sách khoản sắp đến hạn (≤ 90 ngày) → công văn nhắc trước hạn | Hằng tháng |
| 4 | Lập danh sách khoản quá hạn → công văn đôn đốc theo nhóm nợ | Hằng tháng |
| 5 | Kiểm tra hiện trường việc sử dụng vốn và tiến độ GPMB | Tối thiểu hằng quý, ưu tiên nhóm C–F |
| 6 | Lập biên bản kiểm tra, ghi nhận cam kết của đơn vị | Theo đợt kiểm tra |
| 7 | Báo cáo tình hình vốn ứng và nợ quá hạn cho HĐQL Quỹ, UBND tỉnh | Theo kỳ báo cáo III.3 |
| 8 | Đối chiếu công nợ với từng đơn vị nhận vốn (xác nhận bằng biên bản) | Tối thiểu 6 tháng/lần |

## Đầu ra (Output)
- **Bảng theo dõi tuổi nợ, phân loại nợ vốn ứng** (trong hạn / quá hạn)
- **Công văn đôn đốc thu hồi vốn ứng**
  (mẫu: `bieu-mau/01-nghiep-vu-von-ung/mau-cong-van-don-doc-thu-hoi.md`)
- **Biên bản kiểm tra hiện trường**
  (mẫu: `bieu-mau/01-nghiep-vu-von-ung/mau-bien-ban-kiem-tra-hien-truong.md`)
- Số liệu đầu vào cho báo cáo định kỳ (III.3) và cho cân đối kế hoạch (I.1)

## Nguyên tắc
- **Không để khoản nợ "im lặng"**: mọi khoản nhóm C trở lên phải có văn bản
  trong kỳ, lưu hồ sơ đầy đủ — đây là căn cứ khi phải xử lý trách nhiệm sau này.
- Nợ đã quá hạn mà đơn vị vẫn đề nghị ứng mới → ghi rõ trong báo cáo thẩm định
  ở I.2, không bỏ qua.
- Mọi lần làm việc, cam kết của đơn vị phải lập **biên bản có chữ ký**, không
  dừng ở trao đổi miệng/điện thoại.

## Rủi ro thường gặp
- Dự án dừng/thay đổi quy hoạch sau khi đã ứng vốn → mất nguồn hoàn trả. Phát
  hiện qua kiểm tra hiện trường, phải báo cáo ngay chứ không chờ đến hạn.
- Tiền đấu giá QSDĐ đã thu nhưng chưa hoàn trả Quỹ → đối chiếu với cơ quan thu.
- Số liệu theo dõi lệch với kế toán → bắt buộc đối chiếu định kỳ với bộ phận
  kế toán trước khi lên báo cáo.
