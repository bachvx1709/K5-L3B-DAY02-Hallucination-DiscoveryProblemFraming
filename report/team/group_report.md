# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Hallucination
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Tổng hợp báo cáo nhóm
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Duy Mạnh       | Tìm lại cách khắc phục lỗi lập trình đã gặp | Lập trình viên | Khó tìm lại lịch sử sửa lỗi                     | Nếu đã từng sửa lỗi, tại sao không ghi lại cách xử lý vào tài liệu hoặc Git commit? Vấn đề thực sự là thiếu nơi lưu trữ hay khả năng tìm kiếm chưa hiệu quả? (Vũ Xuân Bách)                                   |
| 2 | Nguyễn Duy Mạnh              | Tổng hợp tin tức công nghệ từ nhiều nền tảng         | Người quan tâm công nghệ | Tin phân tán, trùng lặp                         | ác công cụ như Feedly hoặc RSS Reader đã hỗ trợ tổng hợp tin tức, vậy chúng chưa giải quyết được khó khăn cụ thể nào của bạn? (Đỗ Triệu Đức Phương)                          |
| 3 | Nguyễn Duy Mạnh               | Theo dõi tiến độ bài tập nhóm                        | Trưởng nhóm              | Hỏi và tổng hợp tiến độ thủ công                | Nếu các thành viên không chủ động cập nhật tiến độ, liệu một công cụ mới có thực sự giải quyết được vấn đề hay vẫn phụ thuộc vào ý thức của từng người? (Vũ Xuân Bách)                          |
| 4 | Đỗ Triệu Đức Phương           | Chuẩn hóa báo cáo nhóm trước deadline                | Người tổng hợp báo cáo   | Sửa format và văn phong mất thời gian           | Nếu nhóm sử dụng một template thống nhất ngay từ đầu, liệu có còn mất 60 phút để chỉnh sửa định dạng và văn phong khi tổng hợp không?  (Nguyễn Duy Mạnh )                                |
| 5 | Đỗ Triệu Đức Phương            | Kiểm tra quy cách nộp bài Lab                        | Sinh viên                | Kiểm tra file, thư mục, quyền truy cập thủ công | Các yêu cầu như tên file, cấu trúc thư mục và quyền truy cập đều có thể kiểm tra bằng script. Vậy có cần xây dựng một giải pháp phức tạp hơn không? (Vũ Xuân Bách)                                   |
| 6 | Đỗ Triệu Đức Phương            | Trích xuất deadline, rubric và yêu cầu từ đề bài Lab | Sinh viên / Trưởng nhóm  | Yêu cầu phân tán trong nhiều trang              | Nếu hệ thống bỏ sót một tiêu chí chấm điểm quan trọng trong phụ lục, làm thế nào để phát hiện và đảm bảo checklist đáng tin cậy hơn cách đọc thủ công? (Vũ Xuân Bách)                                   |
| 7 | Vũ Xuân Bách            | Tra cứu quy định và thủ tục pháp lý                  | Cá nhân / Hộ kinh doanh  | Khó đối chiếu văn bản còn hiệu lực              | Khi các văn bản pháp luật thay đổi hoặc có quy định chồng chéo, làm thế nào để bảo đảm thông tin được cung cấp còn hiệu lực và phù hợp với từng trường hợp cụ thể? (Nguyễn Duy Mạnh )                                  |
| 8 | Vũ Xuân Bách           | Review kiến thức để phát hiện lỗ hổng                | Học sinh / Sinh viên     | Khó tự đánh giá mức độ hiểu                     | àm thế nào để xác định người học thực sự hiểu sai kiến thức, thay vì chỉ diễn đạt khác đáp án mẫu nhưng vẫn đúng về mặt chuyên môn? (Đỗ Triệu Đức Phương )                                     |
| 9 | Vũ Xuân Bách            | Điều chỉnh kế hoạch khi có thay đổi                  | Cá nhân quản lý kế hoạch | Khó xác định nhiệm vụ phụ thuộc                 | Nếu người dùng không khai báo đầy đủ các nhiệm vụ phụ thuộc, làm thế nào để xác định chính xác những công việc bị ảnh hưởng khi kế hoạch thay đổi? (Đỗ Triệu Đức Phương)                                  |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Tìm kiếm và truy xuất thông tin | Tra cứu pháp lý, tìm lại cách khắc phục lỗi lập trình | Thông tin phân tán, khó tìm đúng nội dung, cần kiểm tra tính chính xác và ngữ cảnh áp dụng |
| B — Học tập và xử lý tài liệu | Review kiến thức, trích xuất yêu cầu/rubric từ đề bài Lab, tổng hợp báo cáo nhóm | Cần đọc, đối chiếu, đánh giá và tổng hợp nhiều nội dung để phát hiện thiếu sót |
| C — Quản lý kế hoạch và tiến độ | Điều chỉnh kế hoạch khi có thay đổi, theo dõi tiến độ bài tập nhóm | Các nhiệm vụ có liên quan đến nhau, thay đổi ở một nhiệm vụ có thể ảnh hưởng đến tiến độ chung |
| D — Tự động hóa tác vụ lặp lại | Kiểm tra quy cách nộp bài Lab, tổng hợp tin tức công nghệ | Người dùng phải thực hiện các bước kiểm tra, thu thập, lọc thông tin lặp lại theo quy trình tương đối ổn định |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian nhóm trưởng dành cho việc thu thập,
đối chiếu và tổng hợp thông tin để hoàn thành báo cáo nhóm
đầy đủ, chính xác và mạch lạc.

├── Opportunity A: Thông tin nằm rải rác
│   └── Khó tìm lại thông tin từ nhiều nguồn, tài liệu và
│       cuộc trao đổi khác nhau.
│
├── Opportunity B: Khó xác định thông tin quan trọng
│   └── Mất thời gian đọc, đối chiếu và chọn lọc nội dung
│       phù hợp với mục tiêu báo cáo.
│
├── Opportunity C: Khó tổng hợp thành nội dung mạch lạc
│   └── Thông tin từ nhiều thành viên thiếu thống nhất,
│       trùng lặp hoặc chưa có sự liên kết.
│
└── Opportunity D: Khó kiểm tra tính đầy đủ và chính xác
    └── Dễ bỏ sót yêu cầu, thiếu minh chứng hoặc sai lệch
        thông tin khi hoàn thiện báo cáo.
```

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tổng hợp báo cáo nhóm | 5 | 5 | 4 | 5 | 5 | 4 | 4 | **32** |
| Kiểm tra quy cách nộp bài Lab | 4 | 5 | 4 | 3 | 3 | 4 | 4 | 27 |
| Trích xuất yêu cầu/rubric từ đề bài Lab | 4 | 4 | 4 | 3 | 3 | 4 | 4 | 26 |

**Candidate được chọn:** Tổng hợp báo cáo nhóm

**Vì sao chọn:** Quy trình thực tế, tốn thời gian thu thập, chọn lọc và tổng hợp thông tin từ nhiều thành viên. Có thể đo thời gian hoàn thành, mức độ đầy đủ và số lỗi/thiếu sót. 

**Vì sao loại các candidate còn lại:** Kiểm tra quy cách nộp bài Lab có quy tắc tương đối cố định, dễ giải quyết bằng Rule. Trích xuất yêu cầu/rubric từ đề bài Lab có phạm vi hẹp, impact thực tế có thể thấp hơn.

**Xử lý bất đồng (nếu có):**  Thống nhất lựa chọn dựa trên mức độ cấp thiết của pain, khả năng đo lường impact, tính khả thi trong Lab và khả năng so sánh các phương án triển khai.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Các nhóm sinh viên khác cũng mất trên 60 phút để tổng hợp và chuẩn hóa báo cáo trước deadline. | Value | 5 | 2 | ✅ |
| 2 | Chuẩn hóa format, văn phong và trích dẫn là bước tốn thời gian nhất, không phải việc thu thập bài từ thành viên. | Value | 5 | 3 | ✅ |
| 3 | Việc thiếu thống nhất giữa các phần viết là nguyên nhân chính khiến báo cáo hoàn thiện muộn, không chỉ do thành viên gửi bài trễ. | Value | 5 | 1 | ✅ |
| 4 | Template, Google Docs/Word và công cụ quản lý trích dẫn chưa giải quyết đủ việc rà soát nội dung, phát hiện trùng lặp và thiếu mục theo rubric. | Feasibility | 4 | 2 | ✅ |
| 5 | Người tổng hợp sẵn sàng thay đổi quy trình làm việc để tiết kiệm thời gian chuẩn hóa báo cáo. | Viability | 4 | 1 | ✅ |
| 6 | Có thể giảm thời gian tổng hợp xuống dưới 40 phút mà không làm tăng lỗi nội dung hoặc định dạng. | Value | 5 | 1 | ✅ |


Giả định nhóm kiểm chứng trong buổi này: Template, Google Docs/Word và công cụ quản lý trích dẫn chưa giải quyết đủ việc rà soát nội dung, phát hiện trùng lặp và thiếu mục theo rubric.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi | Sinh viên năm 4 ngành CNTT, làm nhóm trưởng |
| Câu nói đáng nhớ (mô phỏng) | "Các bạn gửi mỗi người một file, đến lúc ghép vào thì font chữ, heading với bảng biểu mỗi chỗ một kiểu. Mình phải sửa lại gần hết." |
| Lần gần nhất (giả định) | Tuần trước, tổng hợp báo cáo bài tập lớn của nhóm 4 người |
| Workaround hiện tại | Ghép các file vào Word, sử dụng Format Painter, chỉnh lại heading và bảng biểu thủ công |
| Mất bao lâu, bao lần (giả định) | Khoảng 100 phút để hoàn thiện báo cáo, trong đó 50 phút chỉnh định dạng; từng gặp vấn đề tương tự ở 2 bài tập nhóm trước đó. |
| Insight giả định | Khác biệt về định dạng giữa các thành viên là nguyên nhân đáng kể khiến việc tổng hợp mất thời gian |

| Trường | Nội dung |
|---|---|
| Người được hỏi | Sinh viên năm 3 ngành digital marketing, phụ trách tổng hợp báo cáo |
| Câu nói đáng nhớ (mô phỏng) | "Format thì sửa cũng nhanh, nhưng đọc lại mới phát hiện hai người viết trùng ý, có phần lại thiếu yêu cầu của đề bài." |
| Lần gần nhất (giả định) | Hai tuần trước, tổng hợp báo cáo đồ án môn học |
| Workaround hiện tại | Sử dụng Google Docs và template chung; tự đọc lại từng phần để đối chiếu rubric |
| Mất bao lâu, bao lần (giả định) | Khoảng 90 phút để tổng hợp; 40 phút dành cho rà soát nội dung, phát hiện trùng lặp và bổ sung phần còn thiếu |
| Insight giả định | Ngay cả khi dùng template, việc kiểm tra nội dung theo rubric và phát hiện trùng lặp vẫn có thể tốn nhiều thời gian |

| Trường | Nội dung |
|---|---|
| Người được hỏi | Trưởng phòng, thường xuyên làm báo cáo |
| Câu nói đáng nhớ (mô phỏng) | "Nhóm mình dùng chung một mẫu Google Docs từ đầu nên không phải sửa format nhiều. Chủ yếu mất thời gian vì có bạn gửi bài sát deadline." |
| Lần gần nhất (giả định) | Tuần trước, hoàn thiện báo cáo dự án 6 người |
| Workaround hiện tại | Sử dụng Google Docs với template và quy định cách trình bày trước khi phân chia công việc |
| Mất bao lâu, bao lần (giả định) | Khoảng 30 phút kiểm tra và hoàn thiện báo cáo sau khi nhận đủ nội dung; chưa ghi nhận lỗi định dạng nghiêm trọng |
| Insight giả định | Template có thể giải quyết phần lớn vấn đề định dạng. Một số trường hợp chậm nộp xuất phát từ tiến độ của thành viên, không phải công đoạn chuẩn hóa |

Tổng hợp: 

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Interview mô phỏng | 3 | 2/3 tình huống mất 90–100 phút tổng hợp; có vấn đề về định dạng, trùng lặp nội dung và thiếu mục theo rubric | 1/3 tình huống sử dụng template hiệu quả, chỉ cần 30 phút hoàn thiện; nguyên nhân chậm chủ yếu do thành viên gửi bài muộn |
| Problem Card ban đầu | 1 | Tổng hợp mất 120 phút, riêng chuẩn hóa mất 60 phút; 2/3 lần gần nhất nộp sát deadline | Chưa xác định việc nộp sát deadline có hoàn toàn do công đoạn chuẩn hóa hay không |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
 Google Docs | [Google Docs Help](https://support.google.com/docs/answer/116338) | Bước 3–4: Ghép nội dung, chuẩn hóa heading và định dạng văn bản | Có template, Styles, hỗ trợ nhiều thành viên chỉnh sửa cùng một tài liệu | Không tự bảo đảm các phần viết đáp ứng đủ rubric, không trùng ý hoặc thống nhất về lập luận | Ưu tiên sử dụng template và quy tắc định dạng chung trước khi phát triển tính năng mới |
| Microsoft Word | [Microsoft Support](https://support.microsoft.com/en-us/word/compare-and-merge-two-versions-of-a-document) | Bước 3–4: So sánh phiên bản, theo dõi thay đổi và hỗ trợ chỉnh sửa tài liệu | Có Styles, Track Changes, Compare và các chức năng rà soát tài liệu | Vẫn cần người kiểm tra nội dung, tính mạch lạc và mức độ đáp ứng yêu cầu của giảng viên | Tận dụng chức năng chỉnh sửa và so sánh tài liệu hiện có |
| Zotero | [Zotero Documentation](https://www.zotero.org/support/word_processor_integration) | Bước 4–5: Chuẩn hóa trích dẫn và danh mục tài liệu tham khảo | Hỗ trợ nhiều chuẩn trích dẫn, tích hợp với Word và Google Docs | Không kiểm tra được sự đầy đủ của báo cáo hoặc nội dung trùng lặp giữa các phần | Không cần tự phát triển hệ thống quản lý trích dẫn từ đầu |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```
HIỆN TẠI — 5 BƯỚC ~120 phút - 5/5 thủ. công

[1. Thu thập các phần báo cáo từ thành viên]
                   ↓
[2. Đọc và kiểm tra nội dung theo rubric]
                   ↓
[3. Ghép các phần vào tài liệu chung]
                   ↓
[4. Chuẩn hóa format, văn phong, trích dẫn] ← 🔴 BOTTLENECK (~60 phút)
                   ↓
[5. Kiểm tra lần cuối, xuất PDF và nộp bài]
                   ↓
             [Hoàn thành]

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Người tổng hợp, thành viên | File DOCX/Markdown từ Google Drive, Zalo | Tập hợp các phần báo cáo | Chưa đo riêng | File có thể khác nhau về định dạng và cấu trúc |
| 2 | Người tổng hợp | Các phần viết, đề bài và rubric | Danh sách nội dung cần bổ sung hoặc chỉnh sửa | Chưa đo riêng | Phải đọc thủ công để kiểm tra thiếu mục, trùng lặp nội dung |
| 3 | Người tổng hợp | Các phần báo cáo đã nhận | Một tài liệu báo cáo chung | Chưa đo riêng | Copy-paste và sắp xếp nội dung theo bố cục |
| 4 | Người tổng hợp | Báo cáo đã ghép | Báo cáo có định dạng và cách trình bày thống nhất | ~60 phút/lần | 🔴 Bottleneck: chỉnh heading, font, bảng biểu, văn phong và trích dẫn |
| 5 | Người tổng hợp | Báo cáo hoàn chỉnh, checklist nộp bài | File PDF được kiểm tra và nộp | Chưa đo riêng | Kiểm tra lỗi layout, xuất PDF và nộp qua LMS |

**Bottleneck chính:** Bước 4 — Chuẩn hóa định dạng và văn phong, chiếm khoảng 60/120 phút, tương đương **50% tổng thời gian**.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```
TƯƠNG LAI — 7 BƯỚC - MỤC TIÊU < 40 PHÚT - 3 BƯỚC THỦ CÔNG

[1. Thành viên nộp nội dung theo template]
               👤 HUMAN
                    ↓
[2. Thu thập và kiểm tra file đầu vào]
               ⚙️ RULE
  - Kiểm tra định dạng file
  - Kiểm tra các mục bắt buộc
  - Báo file thiếu hoặc không đọc được
                    ↓
[3. Ghép nội dung theo cấu trúc báo cáo]
               ⚙️ WORKFLOW
                    ↓
[4. Kiểm tra cấu trúc và định dạng]
               ⚙️ RULE
  - Heading, font, style
  - Mục và tiểu mục theo rubric
  - Các yêu cầu trình bày xác định được
                    ↓
[5. Rà soát nội dung và đề xuất chỉnh sửa]
               🤖 AI
  - Phát hiện nội dung có khả năng trùng lặp
  - Đánh dấu phần thiếu liên kết
  - Gợi ý thống nhất văn phong
  - Đối chiếu nội dung với rubric
                    ↓
        AI xử lý thành công?
               /          \
             Có           Không
              ↓              ↓
[6. Người tổng hợp     [FALLBACK]
 kiểm tra đề xuất]      Chuyển sang checklist
    👤 HUMAN            và review thủ công
              ↑______________|
              ↓
      Người dùng chấp thuận?
             /         \
           Có          Không
            ↓            ↓
    [Áp dụng sửa]   [Giữ bản gốc /
                     chỉnh thủ công]
            \            /
             ↓          ↓
[7. Kiểm tra PDF và nộp báo cáo]
             👤 HUMAN
                    ↓
              [Hoàn thành]
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 bước chính | 7 bước chính | Nhiều bước hơn do tách riêng khâu kiểm tra và phê duyệt, nhưng giảm thao tác thủ công |
| Tổng thời gian | ~120 phút/lần | < 40 phút/lần | Mục tiêu giảm trên 66,7%; cần đo thực nghiệm |
| Số bước thủ công | 5/5 bước | 3/7 bước có Human tham gia chính | AI chỉ hỗ trợ; bước review và nộp vẫn bắt buộc thủ công |
| Bottleneck chính | Chuẩn hóa format và văn phong (~60 phút) | Review các đề xuất và kiểm tra chất lượng đầu ra | Chưa đo thời gian review sau khi cải tiến |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
