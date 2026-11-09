# Team — BunRieuTopMo

## Thông tin nhóm

- Tên nhóm: **BunRieuTopMo**
- Đề tài chính: **Khôi phục mạch viết báo cáo sau khi bị gián đoạn**.
- Candidate problem nhóm chọn: Khi quay lại báo cáo sau khi lướt thread, bạn An muốn nhớ đúng ý đang viết và bước tiếp theo để tiếp tục công việc mà không mất nhiều thời gian dò lại nội dung.
- Người đề xuất: **Trịnh Thanh Tùng — 2A202603456**.
- Nguồn đề tài: **Problem Card #1** trong [báo cáo cá nhân của Tùng](report/individual/2A202603456_TrinhThanhTung.md).
- Quyết định hiện tại: **Not Yet đối với việc xây công cụ**; ưu tiên kiểm chứng cách ghi chú thủ công trước khi quyết định triển khai.
- Báo cáo chung: [report/team/group_report.md](report/team/group_report.md).

### Phạm vi và mục tiêu

| Nội dung | Thống nhất cho đề tài |
|---|---|
| Người chịu ảnh hưởng chính | Bạn An, trong tình huống viết báo cáo nộp quản lý được ghi ở CP1 của Tùng |
| Quy trình xuất phát | Đang viết → lướt thread → dừng lướt nhưng chưa viết tiếp → quét lại nội dung → viết tiếp |
| Điểm nghẽn tập trung | Khoảng từ lúc dừng lướt đến lúc viết tiếp, gồm lấy lại mạch và quét lại nội dung |
| Mốc tham chiếu ban đầu | Khoảng 5–7 phút/lần theo lời kể, cần bấm giờ để xác lập baseline trước phép thử |
| Mục tiêu thử nghiệm | Thời gian khôi phục ≤3 phút/lần; công sức tạo ghi chú không vượt thời gian tiết kiệm |
| Phép đo chính | Ghi thời điểm dừng lướt và thời điểm viết tiếp; so sánh trung vị trước/sau khi dùng ghi chú |
| Phép đo bổ sung | Thời gian tạo ghi chú, số lần có ghi chú dùng được, tần suất gián đoạn và mức độ giữ đúng mạch nội dung |
| Ranh giới | Tập trung hỗ trợ quay lại công việc; theo dõi riêng 10–15 phút lướt theo lời kể; bạn An kiểm soát nội dung và việc gửi báo cáo |
| Cách thử đầu tiên | No AI: ghi một dòng “đang làm gì / bước tiếp theo” ở cuối đoạn hoặc trước khi chủ động rời tài liệu |
| Điều kiện cân nhắc AI | Cách thủ công còn một bước khó xử lý; có nội dung phù hợp để thử; người dùng kiểm tra được độ đúng với công sức hợp lý |

**Kế hoạch kiểm chứng:** ghi nhận 5 lần gián đoạn tự nhiên trước khi dùng ghi chú và 5 lần có dùng ghi chú, khi người tham gia đồng ý. Ghi thêm độ khó báo cáo và những lần gián đoạn bất ngờ không có điểm đánh dấu để giải thích khác biệt giữa các lần. Đây là phép thử nhỏ nhằm hỗ trợ quyết định của nhóm, không dùng để suy rộng cho mọi người viết báo cáo.

**Điều kiện quyết định tiếp theo:** tiếp tục áp dụng trong phạm vi nhỏ nếu đạt mục tiêu, tiết kiệm thời gian sau khi tính công sức bổ sung và người dùng duy trì được cách làm. Điều chỉnh hoặc dừng nếu thời gian khôi phục vốn ngắn, tình huống hiếm, ghi chú khó duy trì hoặc không giúp giữ mạch viết. Kết quả này là đầu vào cho kết luận CP6.

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Trịnh Thanh Tùng | 2A202603456 | Nhóm trưởng; phụ trách đề tài, kiểm chứng và Problem Statement | TgTrh06 |
| 2 | Nguyễn Hoàng | 2A202603447 | Phản biện; research cách xử lý hiện có; so sánh mức can thiệp AI | gauronaldo |
| 3 | Nguyễn Phú Nam | 2A202603501 | Ghi chép; tổng hợp quy trình, bảng trước/sau và tiêu chí đánh giá | Manny402 |

## Phân công theo checkpoint

Bảng dưới đây là phân công thực hiện theo đề tài đã chọn. Sản phẩm nhóm được tổng hợp trong [báo cáo chung](report/team/group_report.md); tài liệu hỗ trợ đặt tại [report/assets/](report/assets/).

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm cần bàn giao | Nơi tổng hợp |
|---|---|---|---|---|
| CP3 — Hội tụ nhóm | Trịnh Thanh Tùng | Nguyễn Hoàng, Nguyễn Phú Nam | Cluster, cây OST, bảng so sánh candidate và lý do chọn card #1 | Báo cáo nhóm, mục 2 |
| CP4 — Kiểm chứng | Trịnh Thanh Tùng | Nguyễn Phú Nam | Assumption map, câu hỏi về tình huống gần nhất, snapshot và log thời gian | Báo cáo nhóm, mục 3.1–3.2; tài liệu hỗ trợ trong report/assets/ |
| CP4 — Research | Nguyễn Hoàng | Trịnh Thanh Tùng | Bảng research có link; so sánh ghi chú thủ công, nhắc việc và hỗ trợ AI theo đúng phạm vi khôi phục | Báo cáo nhóm, mục 3.3 |
| CP5 — Quy trình trước/sau | Nguyễn Phú Nam | Trịnh Thanh Tùng | Quy trình hiện tại, quy trình có ghi chú, bảng before/after và vị trí cần đo | Báo cáo nhóm, mục 4 |
| CP5 — Problem Statement v0 | Trịnh Thanh Tùng | Nguyễn Hoàng | Actor, bối cảnh, pain, baseline, target và boundary | Báo cáo nhóm, mục 5 |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Hoàng | Trịnh Thanh Tùng, Nguyễn Phú Nam | Ma trận lựa chọn, so sánh mức can thiệp, AI Canvas, kế hoạch đánh giá và Problem Statement v1; nêu rõ phần không áp dụng nếu giữ No AI | Báo cáo nhóm, mục 6–7 |
| CP6 — Quyết định | Trịnh Thanh Tùng | Nguyễn Hoàng, Nguyễn Phú Nam | Bốn rủi ro, cách giảm thiểu, kết luận Go / Not Yet / No-Go và điều kiện xem lại | Báo cáo nhóm, mục 8 |

### Nguyên tắc bàn giao

- Người chính tổng hợp đầu ra của checkpoint; người hỗ trợ kiểm tra logic, số liệu và khả năng đối chiếu nguồn.
- Phân biệt số phút theo lời kể, số đo thực tế và mục tiêu thử nghiệm trong bảng đánh giá.
- Khi ghi đóng góp đã hoàn thành, dẫn tới nội dung, tài liệu hoặc commit tương ứng.
- Đánh giá bốn rủi ro sát đề tài: tần suất pain thấp; khó duy trì ghi chú; công sức bổ sung vượt lợi ích; ghi chú hoặc gợi ý làm mất mạch nội dung. Nếu thử AI, bổ sung việc kiểm tra dữ liệu đưa vào và độ đúng của đầu ra.

## Cá nhân

Các phần dưới đây xác định trách nhiệm và sản phẩm cần bàn giao. Bằng chứng đã có được tách khỏi nơi sẽ tổng hợp sản phẩm để tiện cập nhật tiến độ. Mỗi thành viên bổ sung đóng góp thực tế và điều học được sau khi thực hiện phần việc.

### Trịnh Thanh Tùng - 2A202603456

**Phần việc phụ trách:**

- Điều phối tiến độ, giữ phạm vi đề tài và tổng hợp quyết định của nhóm.
- Chủ trì CP3, CP4 kiểm chứng, CP5 Problem Statement v0 và CP6 quyết định.
- Hỗ trợ research, đối chiếu quy trình và hoàn thiện Problem Statement v1.

**Đóng góp cụ thể và sản phẩm cần bàn giao:**

- Đầu vào đã có trong báo cáo cá nhân: 10 hướng vấn đề, top 3 Problem Card, ba sơ đồ, card ưu tiên và kế hoạch kiểm chứng card #1.
- Đề tài card #1 được chọn làm đề tài chính của nhóm trong TEAM.md.
- Cần tổng hợp cluster, cây OST và lý do chọn candidate; chuẩn bị câu hỏi, tổ chức ghi log và tổng hợp kết quả kiểm chứng.
- Cần hoàn thiện Problem Statement v0 và kết luận CP6 dựa trên đầu ra của cả nhóm.

**Bằng chứng và nơi bàn giao:**

- [Báo cáo cá nhân Trịnh Thanh Tùng](report/individual/2A202603456_TrinhThanhTung.md), mục 2–3: các candidate, Problem Card và sơ đồ đã có.
- [Báo cáo nhóm](report/team/group_report.md), mục 2, 3.1–3.2, 5 và 8: nơi bàn giao phần việc được phân công.
- [report/assets/](report/assets/): nơi lưu snapshot và log sau khi thực hiện kiểm chứng.

**Trọng tâm tự đánh giá sau phần nhóm:**

- Việc tách thời gian lướt khỏi thời gian khôi phục ảnh hưởng thế nào đến cách chọn metric?
- Kết quả kiểm chứng có làm thay đổi phạm vi problem hoặc quyết định Not Yet không?

### Nguyễn Hoàng - 2A202603447

**Phần việc phụ trách:**

- Chủ trì CP4 research và CP6 lựa chọn mức can thiệp, hoàn thiện Problem Statement v1.
- Phản biện phạm vi, cách đo và giá trị của việc hỗ trợ khôi phục mạch viết.
- Hỗ trợ Tùng viết Problem Statement v0 và cùng nhóm đánh giá rủi ro.

**Sản phẩm cần bàn giao:**

- Bảng research có nguồn kiểm tra được, so sánh cách ghi chú thủ công, nhắc việc và hỗ trợ AI theo cùng một nhu cầu.
- Lập luận chọn mức can thiệp dựa trên độ khó của bước cần xử lý, độ đúng và công sức sử dụng.
- Ma trận, AI Canvas và kế hoạch đánh giá phù hợp với lựa chọn; Problem Statement v1 phản ánh kết quả kiểm chứng.
- Phản biện điều kiện cần để chuyển từ cách thủ công sang Workflow có AI.

**Nơi bàn giao bằng chứng:**

- [Báo cáo nhóm](report/team/group_report.md), mục 3.3, 6 và 7: bảng research, mức can thiệp và Problem Statement v1.
- Nguồn research dẫn trực tiếp trong từng dòng so sánh; tài liệu hỗ trợ bổ sung tại [report/assets/](report/assets/) khi cần.

**Trọng tâm tự đánh giá sau phần nhóm:**

- Research có chỉ ra cách xử lý hiện có đáp ứng nhu cầu mà không cần xây công cụ không?
- Khi nào lợi ích của AI đủ lớn để bù công sức kiểm tra đầu ra?

### Nguyễn Phú Nam - 2A202603501

**Phần việc phụ trách:**

- Ghi chép, tổng hợp kết quả trao đổi và hỗ trợ CP4 kiểm chứng.
- Chủ trì CP5 quy trình trước/sau; hỗ trợ tiêu chí đánh giá và kết luận CP6.

**Sản phẩm cần bàn giao:**

- Biểu mẫu ghi thời điểm dừng lướt, thời điểm viết tiếp, công sức tạo ghi chú và bối cảnh của từng lần.
- Quy trình hiện tại và quy trình có ghi chú, thể hiện rõ điểm bắt đầu/kết thúc phép đo và trường hợp không có ghi chú.
- Bảng before/after tách baseline, target và kết quả đo; tính phần thời gian tiết kiệm sau khi trừ công sức bổ sung.
- Ghi chép phản hồi và các điều chỉnh được nhóm thống nhất để cập nhật quy trình, tiêu chí đánh giá.

**Nơi bàn giao bằng chứng:**

- [Báo cáo nhóm](report/team/group_report.md), mục 3.2 và 4: kết quả kiểm chứng, quy trình và bảng before/after.
- [report/assets/](report/assets/): nơi lưu biểu mẫu, log và hình quy trình nếu xuất ra file riêng.

**Trọng tâm tự đánh giá sau phần nhóm:**

- Định nghĩa mốc đo như thế nào để các lần ghi log có thể so sánh?
- Quy trình có ghi chú xử lý ra sao khi người dùng bị gián đoạn bất ngờ?
