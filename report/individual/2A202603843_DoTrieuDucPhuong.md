# Báo cáo cá nhân — 2A202603843_DoTrieuDucPhuong

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên:   Đỗ Triệu Đức Phương
- MSSV: 2A202603843

- Email trường (không bắt buộc, repo có thể để public): 26ai.phuongdtd@vinuni.edu.vn
- Tên nhóm: Hallucination
- Link repo nhóm: https://github.com/bachvx1709/K5-L3B-DAY02-Hallucination-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu làm bài lab, tôi muốn kiểm tra lại toàn bộ quy cách đặt tên file, cấu trúc thư mục và quyền truy cập repo git, để không bị trừ điểm oan vì sai format nộp bài. | Sinh viên trong lớp | Mất 20–30 phút/bài lab, tuần nào cũng phải đối chiếu file SUBMISSION.md. |
| 2 | Tốn thời gian | Khi nhận đề bài Lab dài 15–20 trang kèm nhiều file phụ lục, tôi muốn trích xuất nhanh các mốc thời gian, tiêu chí chấm và yêu cầu kỹ thuật cốt lõi, để lập kế hoạch làm bài đúng trọng tâm. | Bản thân | Mất trung bình 60–90 phút chỉ để đọc và highlight tài liệu, xảy ra 1–2 lần mỗi 2 tuần. |
| 3 | Tốn thời gian | Khi đến hạn nộp báo cáo nhóm trước 23h59, tôi muốn tổng hợp các phần viết rời rạc của các thành viên thành một tài liệu đồng nhất về văn phong, định dạng và trích dẫn, để kịp nộp bài chất lượng cao đúng giờ. | Nhóm trưởng | Mất 2–3 tiếng chỉnh sửa thủ công vào đêm deadline, font chữ, kích cỡ hình ảnh và format bảng. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị thi cuối kỳ các môn chuyên ngành, tôi muốn tổng hợp các khái niệm chính, công thức và ví dụ từ slide bài giảng, ghi chú cá nhân và bài tập hàng tuần vào một dàn ý ôn tập duy nhất, để hệ thống hóa kiến thức mà không bị ngợp. | Bản thân và bạn học cùng lớp | Mất khoảng 8–10 tiếng đọc lại 12 buổi slide và tài liệu rải rác trên Canvas/LMS, Drive, nhiều nội dung trùng lặp hoặc mâu thuẫn. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm tài liệu nghiên cứu để viết phần Related Work cho đồ án, tôi muốn so sánh nhanh phương pháp, bộ dữ liệu và kết quả benchmark của 10–15 bài báo, để chọn ra baseline phù hợp nhất cho mô hình của nhóm. | Sinh viên làm đồ án / nghiên cứu khoa học | Mất 4–6 tiếng đọc lướt abstract, methodology và bảng kết quả, phải tự lập bảng excel thủ công đối chiếu từng bài. |


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý giữ lại:** "Tìm lại các thông báo quan trọng và link tài liệu bị trôi trong kênh chat nhóm khi cần nộp bài."
  - *Lý do giữ:* Đây là vấn đề thực tế mà nhóm gặp phải thường xuyên, có đối tượng chịu ảnh hưởng rõ và đo đếm được số lần lặp lại.
- **Ý bỏ qua:** "Cần một trợ lý ảo chatbot thông minh hỗ trợ nhắc lịch học tập và làm bài tập cho sinh viên."
  - *Lý do bỏ:* Phạm vi bài toán quá rộng, không bám vào một bottleneck cụ thể và thiếu số liệu đo lường hành vi thực tế.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp và chuẩn hóa báo cáo nhóm đêm deadline | Quy trình rõ với sinh viên làm việc nhóm, có baseline đo bằng phút và rủi ro trễ hạn rõ ràng | Chưa biết văn phong và cấu trúc có thể giải quyết bằng template quy định trước không |
| 2 | Kiểm tra quy cách nộp bài và checklist git trước khi submit | Tần suất lặp lại hàng tuần, hậu quả nghiêm trọng| Bài toán này có cần tới AI hay chỉ cần Script/Rule tự động hóa là đủ |
| 3 | Trích xuất rubric và lập dàn ý yêu cầu từ đề bài Lab dài | Đề bài các môn chuyên ngành ngày càng dài, dễ sót tiêu chí phụ | Làm sao đo lường độ chính xác khi trích xuất nếu đề bài dùng từ ngữ không theo chuẩn|

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến hạn nộp báo cáo nhóm trước 23h59, tôi muốn tổng hợp các phần viết rời rạc của các thành viên thành một tài liệu đồng nhất về văn phong, định dạng và trích dẫn, để kịp nộp bài chất lượng cao đúng giờ mà không phải thức trắng đêm. |
| Actor | Nhóm trưởng hoặc thành viên phụ trách tổng hợp bài nộp của nhóm 3–4 sinh viên. |
| Thời điểm / bối cảnh | 20h00 – 23h59 đêm deadline bài tập lớn / lab. |
| Quy trình hiện tại (3–7 bước) | 1. Thu thập các file docx/markdown riêng lẻ từ Google Drive / Zalo · 2. Đọc lướt kiểm tra xem các thành viên có viết đủ các mục theo rubric không · 3. Copy-paste các phần vào file template chung của nhóm · 4. Chuẩn hóa format  và sửa những lỗi trong việc viết văn giữa các phần · 5. Đọc lại lần cuối, export PDF và nộp bài trên LMS. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: Chuẩn hóa format và dung hòa văn phong rời rạc giữa các thành viên, mất khoảng 60 phút. |
| Impact (nếu không giải thì sao) | Mất tổng cộng 120 phút mỗi deadline; 2/3 lần gần nhất nộp bài sát nút (23h55) trong trạng thái vội vàng; từng bị trừ 0.5–1.0 điểm do format bảng bị vỡ và trích dẫn thiếu đồng nhất. |
| Success metric (baseline → target) | Tổng thời gian tổng hợp từ 120 phút giảm xuống dưới 40 phút; 0 lỗi format layout khi export PDF; nộp bài trước hạn ít nhất 30 phút. |
| Phương án không dùng AI | Dùng template Google Docs cố định style + checklist yêu cầu từng người tự format trước khi nộp. (Hạn chế: Vẫn không giải quyết được việc các bạn viết lệch ý, trùng lặp nội dung hoặc khác biệt về ngữ điệu). |
| Giả thuyết về AI (nếu có) | AI đóng vai trò Workflow assistant: Rà soát checklist rubric xem thiếu mục nào, phát hiện đoạn viết bị lặp ý giữa các thành viên và gợi ý câu chuyển đoạn đồng nhất; người tổng hợp review và duyệt lần cuối. |


### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị nộp bài lab hàng tuần, tôi muốn kiểm tra lại toàn bộ quy cách đặt tên file, cấu trúc thư mục, link commit và quyền truy cập repo git, để không bị trừ điểm oan vì sai format nộp bài. |
| Actor | Sinh viên môn thực hành lab. |
| Thời điểm / bối cảnh | 30–45 phút trước hạn chót nộp bài trên LMS/GitHub. |
| Quy trình hiện tại (3–7 bước) | 1. Mở file SUBMISSION.md của repo gốc đối chiếu · 2. Kiểm tra tên file cá nhân theo cú pháp MSSV_HoTen.md · 3. Kiểm tra các thư mục bắt buộc (individual, team, assets) · 4. Mở cửa sổ ẩn danh test quyền truy cập repo và link commit · 5. Copy link commit dán vào ô nộp bài LMS. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & 4: Mở Incognito kiểm tra thủ công quyền truy cập và từng đường dẫn link nộp bài, mất khoảng 15–20 phút. |
| Impact (nếu không giải thì sao) | Mất 30–35 phút/bài lab; có nguy cơ nhận điểm 0 nếu sơ suất để repo ở chế độ private hoặc gửi nhầm link local/commit chưa push. |
| Success metric (baseline → target) | Thời gian kiểm tra từ 30 phút giảm xuống dưới 2 phút; tỷ lệ sai sót quy cách nộp bài là 0%. |
| Phương án không dùng AI | Viết một bash script hoặc GitHub Action tự động kiểm tra regex tên file, cấu trúc thư mục và ping HTTP check quyền public của repo. |
| Giả thuyết về AI (nếu có) | Không cần AI vì đây là tập luật cố định, hoàn toàn giải quyết bằng Rule/Script tự động hóa. |


### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận đề bài Lab dài 15–20 trang kèm nhiều file phụ lục, tôi muốn trích xuất nhanh các mốc thời gian, tiêu chí chấm và yêu cầu kỹ thuật cốt lõi, để lập kế hoạch làm bài đúng trọng tâm. |
| Actor | Nhóm trưởng hoặc cá nhân sinh viên nhận đề bài môn học. |
| Thời điểm / bối cảnh | Ngày đầu tiên khi giảng viên công bố đề bài assignment/lab. |
| Quy trình hiện tại (3–7 bước) | 1. Tải đề bài PDF (15–20 trang) và slide bài giảng liên quan · 2. Đọc lướt toàn bộ tài liệu để nắm bối cảnh · 3. Đọc lại lần 2 để bôi vàng (highlight) các yêu cầu kỹ thuật và bảng rubric điểm · 4. Gõ lại vào file Google Sheets chia task cho nhóm · 5. Họp nhóm 15 phút để phân chia theo bảng vừa lập. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Rà soát rubric và yêu cầu phân tán rải rác trong nhiều trang và phụ lục, mất khoảng 35–45 phút. |
| Impact (nếu không giải thì sao) | Mất khoảng 90 phút cho mỗi đề bài; nhóm từng bị trừ 1.5 điểm đồ án vì bỏ sót yêu cầu "đính kèm file cấu hình docker-compose" nằm ở dòng cuối cùng của phụ lục. |
| Success metric (baseline → target) | Thời gian trích xuất rubric và checklist giảm từ 60 phút xuống 15 phút; 100% tiêu chí chấm điểm được đưa vào bảng task nhóm. |
| Phương án không dùng AI | Đọc bằng mắt có checklist giấy hoặc dùng tính năng search từ khóa ("rubric", "deadline", "deliverable") trong file PDF. (Hạn chế: Dễ sót nếu đề bài dùng từ đồng nghĩa hoặc tiêu chí phụ ghi trong phần ghi chú). |
| Giả thuyết về AI (nếu có) | AI trích xuất các tiêu chí chấm điểm, deadline và deliverables thành bảng checklist JSON/Markdown có trích dẫn trang nguồn; nhóm trưởng đối chiếu xác nhận. |


### Card muốn pitch nhất

- Card số: Problem Card #1 (Tổng hợp và chuẩn hóa báo cáo nhóm đêm deadline)
- Vì sao: Đây là bài toán có quy trình rõ ràng, tần suất lặp lại cao (mọi môn học có bài tập nhóm đều gặp), pain thực tế rất nặng với cả nhóm và sinh viên nào cũng có trải nghiệm đồng cảm. Hơn nữa, bài toán có ranh giới can thiệp rất đẹp: phân định rõ phần nào giải bằng Rule (format font/lề) và phần nào giải bằng Workflow (rà soát sự đồng nhất nội dung).
- Câu hỏi muốn nhóm phản biện: "Liệu nguyên nhân gốc rễ khiến nhóm trưởng mất 60 phút format có phải do thiếu công cụ, hay do các thành viên nộp bài quá sát giờ khiến nhóm trưởng không có thời gian xử lý?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Việc format font chữ, căn lề, bảng biểu hoàn toàn có thể giải quyết bằng Google Docs Styles hoặc Template Markdown mà không cần AI | Đồng ý | Đã làm rõ: phần format giao diện sẽ dùng Template/Rule cố định; AI chỉ dùng trong Workflow để rà soát sự liền mạch văn phong và kiểm tra xem có mục nào trong rubric bị bỏ sót không. |
| Nếu các thành viên nộp bài lúc 23h50 thì dù công cụ có tối ưu cũng không kịp nộp bài | Đồng ý | Đưa thêm quy định / boundary vào quy trình: Đặt soft deadline nội bộ cho các thành viên là 21h00, tạo khoảng thời gian 2 tiếng cho bước tổng hợp. |
| Metric 'văn phong đồng nhất' quá cảm tính và khó đo lường | Đồng ý | Đổi thành metric khách quan đo được: Tổng thời gian từ 120 phút xuống dưới 40 phút, số lỗi định dạng khi xuất PDF bằng 0, nộp bài trước hạn ít nhất 30 phút. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày vấn đề khó tìm lại cách khắc phục lỗi lập trình đã gặp. Nêu bối cảnh, quy trình hiện tại, thời gian tìm kiếm và ảnh hưởng khi phải tìm lại cách sửa lỗi cũ. | Giúp nhóm hiểu rõ vấn đề không chỉ nằm ở việc gặp lỗi, mà còn ở việc thông tin sửa lỗi trước đây bị phân tán và khó truy xuất. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: [Điền câu hỏi thực tế bạn đã hỏi]. Gợi ý nếu chưa nhớ: “Vấn đề này có thực sự cần AI không, hay có thể giải quyết bằng công cụ quản lý và tìm kiếm thông thường?” | Giúp người trình bày làm rõ nguyên nhân gốc, mức độ cần thiết của AI và tính khả thi của giải pháp. |
| Nhận phản biện | Câu hỏi tôi nhận được: [Điền câu hỏi thực tế]. Tôi đã sửa gì: Làm rõ sự khác biệt giữa tìm kiếm bằng từ khóa và tìm kiếm ngữ nghĩa; bổ sung yêu cầu phải kiểm tra lỗi tương tự trong đúng bối cảnh công nghệ, phiên bản và cấu hình. | Tránh giả định rằng hai lỗi có thông báo giống nhau thì chắc chắn có cùng nguyên nhân và cách sửa. |
| Gom cluster / cây OST | Cùng nhóm phân loại các candidate theo dạng công việc. Ví dụ: Cluster A – Báo cáo/tổng hợp; Cluster B – Tìm kiếm thông tin, chẳng hạn tìm lại quyết định cũ trong Slack. Sau đó xem xét điểm chung, cơ hội và khó khăn của từng nhóm vấn đề. | Giúp nhóm nhìn thấy các vấn đề có cùng bản chất, tránh đánh giá từng candidate một cách rời rạc. |
| Chọn candidate problem | Tham gia so sánh các candidate theo mức độ thường xuyên, thời gian bị mất, mức độ ảnh hưởng, khả năng kiểm chứng và mức độ phù hợp với AI. Candidate được chọn là “Khó tìm lại cách khắc phục lỗi lập trình đã gặp”. | Nhóm tập trung vào một vấn đề cụ thể, có quy trình hiện tại và metric để đánh giá thay vì giải quyết quá nhiều vấn đề cùng lúc. |
| Kiểm chứng / research | Xem xét quy trình tìm lỗi, thời gian tìm lại thông tin và phương án không dùng AI như kho ghi chú Markdown/Notion kết hợp tìm kiếm toàn văn. Đặt giả thuyết rằng tìm kiếm ngữ nghĩa có thể hỗ trợ khi cách mô tả lỗi khác với nội dung đã lưu. | Làm rõ rằng cần so sánh AI với phương án đơn giản hơn, không mặc định AI luôn là lựa chọn tốt nhất. |
| Quy trình nhóm | Tham gia xây dựng và chỉnh sửa quy trình hiện tại, xác định bước 3–4 là bottleneck: tìm lại lịch sử sửa lỗi, tài liệu, hội thoại cũ và tìm kiếm thêm trên Internet. | Xác định được vị trí tốn thời gian nhất, khoảng 20 phút trong tổng thời gian ước tính 30 phút/lần. |
| Problem Statement | Tham gia xác định actor là lập trình viên; bối cảnh là khi gặp lại lỗi tương tự; bottleneck là dữ liệu sửa lỗi phân tán; impact khoảng 5 lần/tháng, 30 phút/lần; mục tiêu giảm thời gian tìm lại cách sửa lỗi xuống dưới 15 phút/lần. | Problem Statement có đối tượng, bối cảnh, nguyên nhân, tác động và metric cụ thể hơn. |
| Mức can thiệp AI | Đề xuất AI hỗ trợ tìm kiếm ngữ nghĩa/truy xuất các trường hợp lỗi tương tự từ kho kiến thức đã lưu. Người dùng tự xem xét kết quả, áp dụng cách sửa và kiểm tra lại. | Giữ AI ở vai trò hỗ trợ tìm kiếm, không giao quyền tự sửa code hoặc tự chạy lệnh. |
| Quyết định | Ưu tiên hướng AI hỗ trợ truy xuất lỗi tương tự, kết hợp kho kiến thức tập trung. Nếu không tìm được kết quả phù hợp thì lập trình viên tiếp tục tìm kiếm và debug thủ công. | Có phương án dự phòng, giữ quyền quyết định và kiểm chứng ở con người. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Hỗ trợ tìm và liệt kê các vấn đề có thể gặp trong học tập, làm việc và lập trình. | Giúp mở rộng góc nhìn, đưa ra nhiều tình huống để xem xét. | Một số vấn đề còn chung chung, chưa thể hiện rõ ai gặp, gặp khi nào và ảnh hưởng cụ thể ra sao. | Chọn những tình huống có trải nghiệm hoặc quy trình thực tế, không giữ lại candidate chỉ vì nghe có vẻ thú vị. |
| CP2 Problem Card | Hỗ trợ diễn đạt Job Story, actor, bối cảnh, quy trình, bottleneck, impact và giả thuyết AI. | Giúp sắp xếp nội dung theo cấu trúc Problem Card và phát hiện các trường thông tin còn thiếu. | AI có thể đưa ra thời gian, tần suất hoặc tác động chưa được kiểm chứng nếu không có dữ liệu đầu vào. | Giữ số liệu đã có trong Problem Card; phân biệt số liệu được ghi nhận với ước lượng, không xem nội dung AI đề xuất là dữ liệu thực tế. |
| CP4 Research | Hỗ trợ tìm hướng nghiên cứu và phân tích phương án giải quyết vấn đề tìm lại lỗi lập trình. | Gợi ý kho tri thức tập trung, tìm kiếm toàn văn và tìm kiếm ngữ nghĩa. | AI có thể nhanh chóng đề xuất RAG hoặc chatbot mà chưa chứng minh phương án đó tốt hơn tìm kiếm thông thường. | Đặt phương án Markdown/Notion và tìm kiếm toàn văn làm baseline để so sánh trước khi quyết định dùng AI. |
| CP5 Quy trình | Hỗ trợ mô tả và so sánh quy trình hiện tại với quy trình dự kiến có AI. | Giúp nhìn rõ bước nào có thể được rút ngắn và bước nào vẫn cần con người thực hiện. | Thời gian ở từng bước có thể chỉ là ước lượng; quy trình tương lai dễ bị mô tả quá lý tưởng. | Giữ rõ tổng thời gian hiện tại khoảng 30 phút/lần và bottleneck khoảng 20 phút; ghi thời gian tương lai khoảng 12 phút là mục tiêu giả định, cần kiểm chứng thực tế. |
| CP5–6 Problem Statement | Hỗ trợ sắp xếp actor, bối cảnh, bottleneck, impact, success metric và boundary. | Giúp Problem Statement tập trung vào một vấn đề cụ thể, có thể đo lường. | Có nguy cơ đưa giải pháp AI vào phần mô tả vấn đề quá sớm hoặc nhầm giả thuyết với kết quả đã chứng minh. | Tách riêng vấn đề và giải pháp; giữ trọng tâm là khó tìm lại thông tin sửa lỗi, không phải nhu cầu xây chatbot. |
| CP6 Mức can thiệp / quyết định | Hỗ trợ phân tích AI nên tham gia ở bước nào trong quy trình. | Giúp xác định AI phù hợp với việc tìm kiếm và gợi ý trường hợp tương tự. | AI không thể bảo đảm cách sửa được đề xuất phù hợp với mọi phiên bản, môi trường hoặc cấu hình. | Chọn hướng AI chỉ hỗ trợ truy xuất; lập trình viên phải đọc, đánh giá, áp dụng và kiểm thử trước khi chấp nhận cách sửa. |

---

## 6. Reflection (CP7)

**Lưu ý:** Sáu câu dưới đây cần được viết bằng trải nghiệm thật của bạn. Hãy dùng các ý gợi nhớ để tự viết thành đoạn văn tối thiểu 200 từ cho từng câu, không nên chép nguyên phần gợi ý.

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Có thể triển khai theo các ý:
- Trước đây bạn thường đánh giá vấn đề theo tiêu chí nào?
- Khi nghe các candidate của thành viên khác, bạn nhận ra vấn đề có thể xuất hiện trong nhiều bối cảnh khác nhau như thế nào?
- Bạn học được gì từ cách các bạn xác định actor, bottleneck và impact?
- Bạn có nhận ra một vấn đề nghe có vẻ quan trọng nhưng chưa đủ dữ liệu để chứng minh không?
- Điều đó ảnh hưởng thế nào đến cách bạn đánh giá candidate của nhóm?

### 6.2. Nhóm có lúc nào bị “solution-first” không? Lúc đó nhóm nhận ra và xử lý thế nào?

Có thể triển khai theo các ý:
- Nhóm có từng nghĩ ngay đến chatbot, RAG hoặc tìm kiếm ngữ nghĩa khi mới nghe vấn đề không?
- Vì sao việc nghĩ giải pháp quá sớm có thể khiến nhóm bỏ qua nguyên nhân thực tế?
- Nhóm đã quay lại phân tích quy trình hiện tại như thế nào?
- Việc xác định bước 3–4 là bottleneck có giúp nhóm tập trung hơn không?
- Bạn rút ra điều gì về việc phải hiểu vấn đề trước khi chọn công nghệ?

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.

Có thể triển khai theo các ý:
- Ban đầu bạn nghĩ giải pháp hoặc candidate nào là phù hợp?
- Người phản biện đã hỏi điều gì?
- Câu hỏi đó khiến bạn nhận ra điểm chưa hợp lý nào?
- Bạn đã thay đổi cách nhìn về mức độ cần thiết của AI, metric hay phạm vi giải pháp ra sao?
- Sau lần đó, bạn có thay đổi cách trình bày và bảo vệ ý kiến không?

### 6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?

Có thể triển khai theo các ý:
- Nhóm đã sử dụng hình thức kiểm chứng nào? Hãy ghi đúng hình thức thực tế.
- Kết quả có giống giả định ban đầu không?
- Có thông tin nào khiến bạn bất ngờ về tần suất gặp lỗi, thời gian tìm kiếm hoặc cách lưu trữ lỗi cũ không?
- Phương án tìm kiếm thông thường có thể giải quyết được bao nhiêu phần của vấn đề?
- Kết quả đó khiến nhóm giữ nguyên hay điều chỉnh giả thuyết AI như thế nào?

**Lưu ý:** Nếu nhóm chưa thực hiện phỏng vấn hoặc survey thì hãy nói rõ điều đó. Không tự tạo số người tham gia hoặc kết quả kiểm chứng.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Có thể triển khai theo các ý:
- Khó xác định đâu là vấn đề gốc và đâu chỉ là biểu hiện bên ngoài?
- Khó phân biệt giữa khó tìm lại cách sửa lỗi và khó sửa lỗi lập trình nói chung như thế nào?
- Khó lượng hóa thời gian và tần suất ra sao?
- Việc xác định success metric từ 30 phút xuống dưới 15 phút/lần có điểm gì cần cân nhắc?
- Bạn đã làm gì để Problem Statement không biến thành mô tả giải pháp?

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

- thu thập dữ liệu thực tế sớm hơn hay không?
- đo thời gian từng bước thay vì ước lượng 
- chứng minh phương án AI tốt hơn kho ghi chú và tìm kiếm toàn văn 
- dộ chính xác của kết quả tìm kiếm, rủi ro áp dụng sai cách sửa và trách nhiệm kiểm thử 
- thay đổi cách phân chia công việc hoặc trao đổi trong nhóm 

### 6.7. Hiểu bài: Chuỗi problem → quy trình → metric → boundary → mức can thiệp AI → quyết định
Bài nhóm em tập trung vào vấn đề tổng hợp báo cáo nhóm vào thời điểm gần deadline, khi các thành viên gửi những phần nội dung riêng lẻ với văn phong, định dạng và cách trích dẫn không đồng nhất. 
- Quy trình hiện tại gồm:
+ thu thập file từ các thành viên, kiểm tra nội dung theo rubric, ghép các phần vào template chung, chuẩn hóa định dạng và văn phong, 
+ sau đó đọc lại, xuất PDF và nộp bài. Bottleneck chính nằm ở bước chuẩn hóa format và dung hòa văn phong, mất khoảng 60 phút trong tổng thời gian 120 phút mỗi deadline.

- Nhóm đặt mục tiêu giảm thời gian tổng hợp xuống dưới 40 phút, không có lỗi format khi xuất PDF và nộp bài trước deadline ít nhất 30 phút. 
Mức can thiệp AI được chọn là Workflow Assistant, hỗ trợ người tổng hợp trong quá trình xử lý tài liệu. Người phụ trách vẫn phải kiểm tra, chỉnh sửa và duyệt kết quả cuối cùng. Nhóm lựa chọn hướng kết hợp AI với template Google Docs và checklist để giảm thời gian tổng hợp nhưng vẫn bảo đảm chất lượng báo cáo.


---

## 7. Tài liệu tham khảo

1. Tài liệu Problem Card CP2 của nhóm – nội dung về candidate “Khó tìm lại cách khắc phục lỗi lập trình đã gặp”.
