---
description: Rà soát tuổi nợ, phân loại nợ vốn ứng và dựng công văn đôn đốc (đầu việc I.3)
---

Thực hiện đầu việc **I.3 — Theo dõi, đôn đốc thu hồi vốn ứng**.

Yêu cầu / file số liệu: $ARGUMENTS

Trình tự:

1. Đọc `01-nghiep-vu-quy-phat-trien-dat/03-theo-doi-thu-hoi-von-ung/README.md`.
2. Đọc file theo dõi vốn ứng (mặc định
   `bieu-mau/01-nghiep-vu-von-ung/bang-theo-doi-von-ung.csv`, hoặc file người
   dùng chỉ ra). Nêu rõ **mốc chốt số liệu** đang dùng.
3. Tính số ngày quá hạn cho từng khoản so với `han_hoan_tra`, phân nhóm nợ
   A–F theo khung trong README. Nếu thiếu `han_hoan_tra` → báo thiếu, không tự suy luận.
4. Lập bảng tổng hợp: số khoản và dư nợ theo từng nhóm; danh sách khoản
   **sắp đến hạn (≤ 90 ngày)** và danh sách khoản **quá hạn**.
5. Dựng công văn đôn đốc cho từng khoản nhóm C trở lên, theo
   `bieu-mau/01-nghiep-vu-von-ung/mau-cong-van-don-doc-thu-hoi.md`.
   Với nhóm D trở lên, thêm đoạn cảnh báo báo cáo HĐQL Quỹ và UBND tỉnh.
6. Nêu các khoản cần ưu tiên kiểm tra hiện trường trong kỳ.
7. Kết thúc bằng danh sách việc cần làm, kèm hạn.

Không điều chỉnh số liệu trong file theo dõi nếu người dùng không yêu cầu.
