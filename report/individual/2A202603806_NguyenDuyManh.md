# Báo cáo cá nhân — MSSV_HoTen

## 1. Thông tin học viên

- Họ tên: Nguyễn Duy Mạnh
- MSSV: 2A202603806
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Hallucination
- Link repo nhóm: https://github.com/bachvx1709/K5-L3B-DAY02-Hallucination-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Cần đọc, tổng hợp nhiều thông tin |Khi có nhiều tin tức công nghệ xuất hiện trên Reddit, X, Facebook và các trang tin khác, tôi muốn nắm bắt được những cập nhật quan trọng, để không bỏ lỡ thông tin liên quan đến lĩnh vực mình quan tâm. |Người quan tâm công nghệ |Số nguồn theo dõi ~5 nguồn/1 tuần, mỗi ngày dành 30 phút đọc |
| 2 |Cần đọc, tổng hợp thông tin |Khi lựa chọn sản phẩm công nghệ trong ngân sách giới hạn, tôi muốn so sánh thông số và trải nghiệm từ nhiều nguồn, để chọn được sản phẩm phù hợp mà không mất quá nhiều thời gian. |Người mua sản phẩm công nghệ |Tham khảo khoảng 5-7 nguồn/1 lần mua |
| 3 |Tốn thời gian |Khi quay lại một dự án lập trình sau thời gian gián đoạn, tôi muốn nhanh chóng nắm được tiến độ và những công việc còn dang dở, để có thể tiếp tục phát triển mà không phải tìm hiểu lại từ đầu. |Lập trình viên |Cần dành ra 30 phút để làm quen lại và một tháng chuyển dự án 2 lần |
| 4 |Lặp lại |Khi gặp lại một lỗi lập trình đã từng xử lý, tôi muốn nhanh chóng tìm lại nguyên nhân và cách khắc phục, để không phải mất thời gian tìm kiếm và debug lại từ đầu. |Lập trình viên |Gặp khoảng 5 lần/1 tháng và mất 30 phút tìm lại cách sửa |
| 5 |Pain từ người khác |Khi thực hiện bài tập nhóm, tôi muốn nắm được tiến độ và phần việc của từng thành viên, để phối hợp hiệu quả và tránh tình trạng công việc bị dồn vào sát hạn nộp. |PM, cả team |Mỗi tuần hỏi tiến độ 5 lần, 2 nhiệm vụ hoàn thành trễ |
| 6 |Lặp lại |Khi có nhiều môn học với thời gian và phòng học khác nhau, tôi muốn nắm chính xác lịch học của từng buổi, để tránh đi muộn, nhầm phòng hoặc bỏ lỡ tiết học. |Sinh viên |Một tuần đi học phải xem lại lịch học 3-4 lần |
| 7 |Lặp lại, tốn thời gian |Khi bắt đầu một dự án lập trình mới, tôi muốn thiết lập đúng môi trường, thư viện và công cụ cần thiết, để không mất nhiều thời gian xử lý các lỗi cài đặt và cấu hình. |Lập trình viên |1 tháng khoảng 2 lần |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

#### Các ý tưởng giữ lại đưa vào bảng Scan: 1, 2, 3, 4, 5

#### Các ý tưởng bị loại bỏ và lý do

**Ý 6: Thiết lập môi trường, thư viện và công cụ khi bắt đầu dự án mới**
  *Lý do loại:*
    **Bài toán đã có chuẩn công nghiệp giải quyết triệt để (Solved Problem):** Hệ sinh thái phần mềm đã có công cụ chuẩn hóa tối ưu như Docker, Dev Containers, starter CLI (`create-next-app`, `vite`) và các trình quản lý môi trường (`nvm`, `venv`, `poetry`). Vấn đề thực chất chỉ nằm ở việc thiếu file cấu hình mẫu hoặc `README.md`.
    **Tác vụ một lần, tần suất thấp (One-off task):** Việc dựng môi trường chỉ diễn ra 1–2 lần ở đầu dự án, sau đó cả nhóm làm việc nhiều tháng trên môi trường ổn định; không đủ độ nhức nhối thường nhật để tạo thói quen sử dụng giải pháp mới.

**Ý 7: Theo dõi thời gian và phòng học để tránh nhầm lịch, đi trễ**
  *Lý do loại:*
    **Cạnh tranh trực tiếp với các công cụ mặc định hoàn hảo (Commodity Problem):** Google Calendar, Apple Calendar và Outlook đã giải quyết trọn vẹn bằng thông báo đẩy, widget màn hình khóa và đồng bộ đa thiết bị; cổng portal trường học cũng đã hỗ trợ xuất file `.ics` đồng bộ tự động.
    **Lỗi thói quen cá nhân, không phải lỗ hổng quy trình (Behavioral Issue):** Quên phòng/giờ học xuất phát từ sự lơ đễnh cá nhân chứ không phải do dữ liệu phân mảnh hay quy trình xử lý phức tạp.
    **Biên độ giá trị gia tăng bằng 0:** Dữ liệu đầu ra là chuỗi tĩnh đơn giản (`Môn - Giờ - Phòng`), không cần tổng hợp hay xử lý logic đa chiều.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Khó tìm lại cách khắc phục lỗi lập trình đã gặp |Vấn đề lặp lại, có số liệu cụ thể và ảnh hưởng trực tiếp đến hiệu suất lập trình. (#4) | |
| 2 |Khó tổng hợp tin tức công nghệ từ nhiều nền tảng (#1) |Thông tin phân tán, dễ trùng lặp và bỏ lỡ những cập nhật quan trọng. |Khó xác định tiêu chí tin tức quan trọng |
| 3 |Khó theo dõi tiến độ bài tập nhóm (#5) |Vấn đề không chỉ ảnh hưởng đến cá nhân mà còn tác động đến tiến độ chung của nhóm. | |

### Problem Card #1 - Khó tìm lại cách khắc phục lỗi lập trình đã gặp

| Trường | Nội dung |
|---|---|
| Job Story | Khi gặp lại một lỗi lập trình đã từng xử lý, tôi muốn nhanh chóng tìm lại nguyên nhân và cách khắc phục, để không phải mất thời gian tìm kiếm và debug lại từ đầu. |
| Actor | Lập trình viên thường xuyên phát triển và bảo trì phần mềm |
| Thời điểm / bối cảnh |	Trong quá trình lập trình, khi gặp lỗi tương tự lỗi đã xử lý ở dự án trước hoặc trong lần làm việc trước đó. |
| Quy trình hiện tại |1. Đọc thông báo lỗi · 2. Kiểm tra source code và cấu hình · 3. Tìm lại lịch sử sửa lỗi, tài liệu hoặc cuộc hội thoại cũ · 4. Tìm kiếm thêm trên Internet nếu chưa nhớ cách xử lý · 5. Thử các phương án khắc phục · 6. Kiểm tra lại kết quả. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3–4: Khó tìm lại thông tin và cách sửa lỗi trước đây do dữ liệu phân tán, không có nơi lưu trữ thống nhất. (20 phút) |
| Impact |Gặp khoảng 5 lần/tháng, mỗi lần mất khoảng 30 phút, tương đương 150 phút (2,5 giờ)/tháng để tìm lại cách sửa lỗi. |
| Success metric |Giảm thời gian tìm lại cách sửa lỗi từ 30 phút xuống dưới 15 phút/lần; cách xử lý tìm được phải phù hợp với lỗi thực tế. |
| Phương án không dùng AI |Xây dựng kho ghi chú lỗi tập trung bằng Markdown hoặc Notion, phân loại theo công nghệ, loại lỗi và từ khóa. Kết hợp tìm kiếm toàn văn để tra cứu các lỗi đã xử lý. |
| Giả thuyết về AI |Nếu lỗi được mô tả khác với cách ghi chú ban đầu, tìm kiếm bằng từ khóa có thể không hiệu quả. Có thể thử tìm kiếm ngữ nghĩa để truy xuất các trường hợp lỗi tương tự. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:


```text
HIỆN TẠI — ~30 phút/lần

[1. Đọc thông báo lỗi]
        ↓
[2. Kiểm tra source code và cấu hình]
        ↓
[3. Tìm lịch sử sửa lỗi, tài liệu, hội thoại cũ] ← BOTTLENECK (giả định)
        ↓
[4. Tìm kiếm thêm trên Internet]                 ← BOTTLENECK (giả định)
        ↓
[5. Thử các phương án khắc phục]
        ↓
[6. Kiểm tra lại kết quả]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi có nhiều tin tức công nghệ xuất hiện trên Reddit, X, Facebook và các trang tin khác, tôi muốn nắm bắt được những cập nhật quan trọng, để không bỏ lỡ thông tin liên quan đến lĩnh vực mình quan tâm. |
| Actor | Người quan tâm công nghệ |
| Thời điểm / bối cảnh | Hằng ngày hoặc cuối tuần, khi muốn cập nhật các thông tin mới về công nghệ, công cụ lập trình và xu hướng phát triển phần mềm. |
| Quy trình hiện tại | 1. Mở các nền tảng tin tức · 2. Duyệt bài viết mới · 3. Lọc nội dung liên quan · 4. Mở và đọc các bài quan tâm · 5. Đối chiếu thông tin giữa các nguồn · 6. Ghi nhớ hoặc lưu lại các tin quan trọng. |
| Bottleneck | Bước 2–5: Nội dung phân tán giữa nhiều nền tảng, có thể trùng lặp hoặc thiếu ngữ cảnh. (Mất 10 phút cho việc tìm kiếm tin tức) |
| Impact | Theo dõi khoảng 5 nguồn/tuần, dành trung bình 30 phút/ngày, tương đương 210 phút (3,5 giờ)/tuần cho việc theo dõi tin tức công nghệ. Đây là tổng thời gian đọc tin, không phải toàn bộ thời gian lãng phí. |
| Success metric | Giảm thời gian cập nhật tin xuống khoảng 10–15 phút/ngày mà vẫn nắm được các tin quan trọng; hạn chế tin trùng lặp và duy trì khả năng truy cập nguồn gốc thông tin. |
| Phương án không dùng AI | Sử dụng RSS Reader để tập trung các nguồn tin, lọc theo từ khóa, chủ đề và thời gian; loại bỏ URL trùng lặp, sắp xếp bài viết theo mức độ quan tâm. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ nhận diện các bài viết cùng nói về một sự kiện dù khác tiêu đề, tóm tắt nhiều nguồn và phân loại mức độ liên quan theo sở thích người đọc. |
| Cảm nhận nhanh | Workflow |


Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~30 phút/ngày

[1. Mở Reddit, X, Facebook và các trang tin khác]
        ↓
[2. Duyệt bài viết mới]               ← BOTTLENECK (giả định)
        ↓
[3. Lọc nội dung liên quan]            ← BOTTLENECK (giả định)
        ↓
[4. Mở và đọc các bài quan tâm]
        ↓
[5. Đối chiếu giữa nhiều nguồn]        ← BOTTLENECK (giả định)
        ↓
[6. Ghi nhớ hoặc lưu lại tin quan trọng]
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi thực hiện bài tập nhóm, tôi muốn nắm được tiến độ và phần việc của từng thành viên, để phối hợp hiệu quả và tránh tình trạng công việc bị dồn vào sát hạn nộp. |
| Actor | Trưởng nhóm (PM) chịu trách nhiệm phân công và theo dõi tiến độ; các thành viên thực hiện nhiệm vụ. |
| Thời điểm / bối cảnh | Trong quá trình thực hiện bài tập nhóm hoặc dự án môn học, đặc biệt khi gần đến deadline. |
| Quy trình hiện tại | 1. Phân chia công việc cho từng thành viên · 2. Trao đổi qua nhóm chat · 3. Chủ động hỏi tiến độ · 4. Tổng hợp trạng thái công việc · 5. Phát hiện nhiệm vụ chậm · 6. Nhắc nhở hoặc điều chỉnh phân công. |
| Bottleneck | Bước 3–4: Phải liên tục hỏi và tổng hợp tiến độ thủ công, khó nắm được trạng thái thực tế của tất cả nhiệm vụ. Chưa đo thời gian cho từng bước. |
| Impact | Trung bình 5 lần hỏi tiến độ/tuần, ghi nhận 2 nhiệm vụ hoàn thành trễ trong kỳ quan sát được nêu ở CP1. Chưa xác định tổng thời gian tiêu tốn hoặc tỷ lệ nhiệm vụ trễ. |
| Success metric | Giảm số lần phải chủ động hỏi tiến độ từ 5 xuống tối đa 2 lần/tuần; giảm số nhiệm vụ trễ hạn và bảo đảm các thành viên cập nhật tiến độ đúng thực tế. |
| Phương án không dùng AI | Sử dụng bảng Kanban với các trạng thái To do, In progress, Done; đặt deadline, người phụ trách và tự động nhắc việc dựa trên thời hạn. |
| Giả thuyết về AI (nếu có) | Chưa có giả thuyết đủ mạnh để chứng minh cần AI. Nếu các thành viên cập nhật tiến độ đầy đủ, quy tắc theo dõi và nhắc deadline có thể giải quyết phần lớn vấn đề. |
| Cảm nhận nhanh | Rule / Workflow |


Quy trình nháp hiện tại:

```text
HIỆN TẠI — 5 lần hỏi tiến độ/tuần, 2 nhiệm vụ trễ

[1. Phân chia công việc và deadline]
        ↓
[2. Trao đổi qua nhóm chat]
        ↓
[3. Chủ động hỏi tiến độ từng thành viên]  ← BOTTLENECK (giả định)
        ↓
[4. Tổng hợp trạng thái công việc]          ← BOTTLENECK (giả định)
        ↓
[5. Phát hiện nhiệm vụ chậm]
        ↓
[6. Nhắc nhở hoặc điều chỉnh phân công]
```

### Card muốn pitch nhất

- Card số: #1 — Khó tìm lại cách khắc phục lỗi lập trình đã gặp.
- Vì sao: Đây là vấn đề tôi thường xuyên gặp trong quá trình lập trình, khoảng 5 lần/tháng, mỗi lần mất trung bình 30 phút để tìm lại cách sửa, tương đương 150 phút/tháng. Vấn đề có pain rõ ràng, dễ đo lường và có thể áp dụng cho nhiều lập trình viên. Ngoài ra, có thể so sánh hiệu quả giữa tìm kiếm thông thường và tìm kiếm ngữ nghĩa để xác định liệu AI có thực sự cần thiết hay không.
- Câu hỏi muốn nhóm phản biện: Nếu sử dụng Markdown, Notion hoặc Git để lưu lại lịch sử lỗi và cách khắc phục, liệu vấn đề đã được giải quyết đủ tốt chưa? Giá trị bổ sung của AI so với tìm kiếm bằng từ khóa là gì?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Vấn đề có thể xuất phát từ việc không ghi chép cách sửa lỗi, chứ không phải thiếu công cụ tìm kiếm. |Có |Làm rõ bottleneck là thông tin sửa lỗi phân tán, khó tìm lại. Bổ sung phương án lưu trữ lỗi có cấu trúc bằng Markdown hoặc Notion. |
|Các công cụ như Git, Notion hoặc tìm kiếm từ khóa đã có thể giải quyết một phần vấn đề. |Có |Bổ sung phương án không dùng AI, ưu tiên thử nghiệm tìm kiếm thông thường trước khi cân nhắc tìm kiếm ngữ nghĩa. |
|Vấn đề chỉ ảnh hưởng đến cá nhân, chưa đủ quy mô để trở thành một bài toán đáng giải quyết. |Không đồng ý |Tôi cho rằng một vấn đề không nhất thiết phải ảnh hưởng đến nhiều người mới có giá trị. Với tần suất 5 lần/tháng và 30 phút/lần, tôi đã mất khoảng 150 phút/tháng. Đây là pain có thể đo lường được và đủ cơ sở để thử nghiệm giải pháp quy mô nhỏ. Tuy nhiên, tôi vẫn đề xuất khảo sát thêm lập trình viên khác trước khi mở rộng phạm vi. |
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Tôi trình bày 3 vấn đề từ trải nghiệm cá nhân: khó tìm lại cách khắc phục lỗi lập trình đã gặp, khó tổng hợp tin tức công nghệ từ nhiều nền tảng và khó theo dõi tiến độ bài tập nhóm. Với mỗi vấn đề, tôi xác định actor, quy trình hiện tại, bottleneck, impact và phương án không dùng AI. |Đóng góp 3/9 candidate cho nhóm, giúp mở rộng các hướng giải quyết và cung cấp dữ liệu ban đầu để so sánh, lựa chọn problem phù hợp. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Nếu nhóm sử dụng một template thống nhất ngay từ đầu, liệu có còn mất 60 phút để chỉnh sửa định dạng và văn phong khi tổng hợp không?|Giúp nhóm xác định được 1 giải pháp có sẵn (Sử dụng template có sẵn và quy tắc định dạng chung trước khi phát hành) |
| Nhận phản biện | Câu hỏi tôi nhận được: Các công cụ như Feedly hoặc RSS Reader đã hỗ trợ tổng hợp tin tức, vậy chúng chưa giải quyết được khó khăn cụ thể nào của bạn?| Tôi đã sửa gì: Tôi điều chỉnh hướng phân tích từ "thiếu công cụ tổng hợp tin tức" sang "mất thời gian chọn lọc và xác định thông tin quan trọng từ nhiều nguồn". Đồng thời bổ sung RSS Reader làm phương án không dùng AI, tránh đề xuất xây dựng lại tính năng đã có.|
| Gom cluster / cây OST |Tôi tham gia phân loại 9 candidate thành 4 nhóm: tìm kiếm và truy xuất thông tin, học tập và xử lý tài liệu, quản lý kế hoạch và tiến độ, tự động hóa tác vụ lặp lại. |Giúp nhóm nhìn thấy điểm chung giữa các vấn đề, tránh nhầm lẫn giữa opportunity và solution, tạo cơ sở để chấm điểm và lựa chọn candidate. |
| Chọn candidate problem |Tôi tham gia so sánh các candidate theo 7 tiêu chí: actor, quy trình, bằng chứng pain, impact, khả năng triển khai lab, khả năng so sánh các mức can thiệp và mức độ hiểu domain. Sau khi xem xét, tôi thống nhất với lựa chọn "Chuẩn hóa báo cáo nhóm trước deadline". | Giúp nhóm hội tụ từ 9 candidate về một problem có quy trình rõ ràng, baseline 120 phút/lần và bottleneck 60 phút ở khâu chuẩn hóa, phù hợp để nghiên cứu và kiểm chứng. |
| Kiểm chứng / research | Tôi hỗ trợ xác định các giả định quan trọng trong Assumption Map, xây dựng câu hỏi phỏng vấn theo The Mom Test và nghiên cứu các giải pháp hiện có như Google Docs, Microsoft Word và Zotero. Tôi tập trung kiểm tra liệu template, Styles và công cụ quản lý trích dẫn đã giải quyết được phần nào của vấn đề. | Giúp nhóm nhận ra rằng nhiều tác vụ định dạng và trích dẫn đã có giải pháp. Từ đó đề xuất thu hẹp phạm vi vào việc rà soát nội dung trùng lặp, thiếu liên kết và bỏ sót rubric. Phần phỏng vấn thực tế vẫn cần được hoàn thành để xác nhận pain. |
| Quy trình nhóm | Tôi tham gia xây dựng quy trình Before/After, xác định các bước thu thập tài liệu, ghép nội dung, chuẩn hóa, rà soát và nộp báo cáo. Trong quy trình tương lai, tôi phân biệt các bước Rule, Workflow, AI và Human Review, đồng thời bổ sung boundary và fallback khi AI hoạt động không chính xác. | Giúp nhóm xác định rõ vị trí can thiệp của từng thành phần, tránh tự động hóa toàn bộ quy trình và bảo đảm người tổng hợp vẫn kiểm soát nội dung trước khi nộp. |
| Problem Statement | Tôi tham gia điều chỉnh Problem Statement từ việc "chuẩn hóa toàn bộ báo cáo nhóm" sang tập trung giải quyết thời gian rà soát và kiểm tra tính thống nhất của các phần viết. Đồng thời bổ sung baseline, success metric, AI intervention point và Human-in-the-loop. | Giúp bài toán cụ thể hơn và có thể đo lường: mục tiêu giảm thời gian từ 120 phút xuống dưới 40 phút/lần, hạn chế lỗi định dạng và bỏ sót yêu cầu rubric. |
| Mức can thiệp AI | Tôi tham gia so sánh No AI, Rule, Workflow và Agent. Tôi đề xuất ưu tiên template và Rule cho các tác vụ định dạng; chỉ sử dụng AI để hỗ trợ phát hiện trùng lặp ngữ nghĩa, thiếu nội dung theo rubric và đề xuất chỉnh sửa. | Giúp nhóm lựa chọn mức 'Workflow có AI hỗ trợ', thay vì Agent tự chủ. Đồng thời xác định người tổng hợp phải phê duyệt mọi thay đổi nội dung và có phương án quay về kiểm tra thủ công. |
| Quyết định | Tôi thống nhất lựa chọn NOT YET vì nhóm chưa có đủ bằng chứng cho thấy AI tạo ra giá trị vượt trội so với template, checklist và các công cụ hiện có. Tôi đề xuất kiểm chứng thêm bằng phỏng vấn người dùng, thử nghiệm thực tế và đánh giá chất lượng đầu ra. | Giúp nhóm tránh triển khai giải pháp quá sớm. Nhóm đặt ngưỡng dừng: nếu sau 3 tuần AI không cải thiện thêm ít nhất 20% thời gian so với phương án Rule/Checklist hoặc không đạt tiêu chí chất lượng, quay về Workflow không AI. |

---

## 5. Dùng AI

**Công cụ sử dụng:** ChatGPT (OpenAI)

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **CP1 — Scan** | Brainstorm thêm các vấn đề từ trải nghiệm cá nhân, chuẩn hóa Job Story và xác định đối tượng chịu ảnh hưởng. | Gợi ý được nhiều vấn đề liên quan đến học tập, lập trình và làm việc nhóm; giúp chuyển cách mô tả từ giải pháp sang problem. | Ban đầu AI hiểu nhầm yêu cầu thành vấn đề doanh nghiệp, đề xuất các bài toán Vinhomes/VinFast. Một số dấu hiệu ban đầu chỉ là chỉ số cần đo, chưa có bằng chứng thực tế. | Làm rõ yêu cầu là vấn đề cá nhân; tự chọn các vấn đề thực sự gặp và bổ sung số liệu về thời gian, tần suất, mức độ ảnh hưởng. |
| **CP2 — Problem Card** | Hỗ trợ xây dựng Job Story, mô tả quy trình hiện tại, xác định bottleneck, impact, success metric và các phương án giải quyết. | Giúp hệ thống hóa problem thành các trường rõ ràng, xác định từng bước trong quy trình và đề xuất chỉ số đo lường. | Ban đầu AI có xu hướng đề xuất giải pháp AI cho mọi vấn đề, chưa xem xét đầy đủ khả năng giải quyết bằng công cụ hoặc quy tắc đơn giản. | Yêu cầu đánh giá lại hai trường "Giả thuyết về AI" và "Cảm nhận nhanh"; phân biệt No AI, Rule, Workflow và Agent, không mặc định vấn đề nào cũng cần AI. |
| **CP4 — Research** | Liệt kê Assumption Map, xây dựng câu hỏi phỏng vấn theo The Mom Test và nghiên cứu công cụ đã giải quyết vấn đề tương tự. | Giúp xác định các giả định cần kiểm chứng và so sánh Google Docs, Microsoft Word, Zotero để nhận ra những chức năng đã có sẵn. | AI chưa có dữ liệu phỏng vấn thực tế; các Interview Snapshots được tạo chỉ là tình huống mô phỏng, không phải bằng chứng xác nhận pain. Phân tích khoảng trống của công cụ còn cần kiểm thử trực tiếp. | Giữ rõ trạng thái mô phỏng của dữ liệu phỏng vấn; tập trung nghiên cứu vấn đề chuẩn hóa báo cáo nhóm thay vì xây dựng lại những chức năng đã có. |
| **CP5 — Quy trình** | Xây dựng sơ đồ Before/After, phân chia trách nhiệm giữa Rule, AI và con người; xác định bottleneck và fallback. | Giúp trực quan hóa quy trình, xác định điểm có thể giảm thao tác thủ công và thiết lập cơ chế Human-in-the-loop. | AI đề xuất quy trình tương lai với mục tiêu giảm thời gian mạnh nhưng chưa có kết quả thực nghiệm chứng minh. Một số bước mới có thể làm tăng công sức review. | Giữ baseline 120 phút/lần và bottleneck 60 phút từ Problem Card; coi mục tiêu dưới 40 phút là giả thuyết cần kiểm chứng; yêu cầu người dùng duyệt thay đổi và giữ quy trình thủ công dự phòng. |
| **CP5–6 — Problem Statement** | Viết và điều chỉnh Problem Statement từ phiên bản ban đầu sang v1, bổ sung impact, success metric, AI intervention point, boundary và HITL. | Giúp thu hẹp bài toán từ chuẩn hóa toàn bộ báo cáo sang rà soát rubric, nội dung trùng lặp và sự thiếu thống nhất giữa các phần viết. | AI có xu hướng mở rộng phạm vi tính năng, trong khi chưa chứng minh được công đoạn nào thực sự cần AI và đâu là nguyên nhân chính khiến báo cáo hoàn thành muộn. | Thu hẹp phạm vi vào khâu rà soát sau khi ghép tài liệu; tận dụng template và công cụ có sẵn cho định dạng, trích dẫn; không cho AI tự sửa nội dung chuyên môn hoặc nộp bài. |
| **CP6 — Mức can thiệp / quyết định** | So sánh No AI, Rule, Workflow, Agent; xây dựng AI Canvas, tiêu chí đánh giá, phân tích rủi ro và đề xuất Go / Not Yet / No-Go. | Giúp lựa chọn mức can thiệp phù hợp là Workflow có AI hỗ trợ một bước, không cần Agent tự chủ; xác định ngưỡng đánh giá và ngưỡng dừng. | Chưa có bằng chứng AI tạo ra giá trị vượt trội so với template và checklist. Các ngưỡng Precision, Recall và thời gian tiết kiệm mới là mục tiêu, chưa phải kết quả đạt được. | **Chọn NOT YET** thay vì GO; yêu cầu kiểm chứng với người dùng thật và so sánh phương án không dùng AI trước. Nếu sau 3 tuần AI không tạo thêm ít nhất 20% cải thiện hoặc không đạt chất lượng, quay về Rule / Workflow không AI. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Sau khi nghe top 3 problems của các thành viên trong nhóm (và những người nhóm khác), tôi có thêm nhiều cách nhìn về vấn đề của người khác, cùng một môi trường học nhưng mỗi người lại có điểm nghẽn hoàn toàn khác nhau. Những người làm leader thường hay gặp vấn đề về giao tiếp & phân công công việc, những người thiên về kỹ thuật lại hay gặp vấn đề với phân mảnh tài liệu...

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, ngay khi vừa nói đến vấn đề về luật thì cả nhóm liền nghĩ ngay đến: Xây dựng chatbot AI tích hợp RAG để đọc tài liệu và trả lời câu hỏi, rồi sau đó bắt đầu tranh luận dùng model gì, vector db gì,... Lúc đó nhóm tự đặt ra những câu hỏi ngược lại kiểu "Nếu user chỉ cần tra 1 điều luật cụ thể thì tính năng search của các công cụ tìm kiếm đã quá đủ rồi, lúc đó có cần đến chatbot không?"

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có, khi bảo vệ quan điểm cho bài toán "Thiết lập môi trường và cấu hình dự án cho thành viên mới" vì bản thân từng mất nhiều thời gian cho việc này nên tôi nghĩ đây là vấn đề lớn. Nhưng nhóm chỉ ra rằng đây là 1 tác vụ dùng 1 lần, trong 1 dự án kéo dài 3-4 tháng việc dựng môi trường chỉ diễn ra 1-2 lần và trong ~ 1 tuần đầu - đó không phải pain point lớn. Tôi chấp nhận buông bỏ ý tưởng vì bài toán thiếu tần suất và giải pháp thay thế đã có sẵn, không đáng để đầu tư nguồn lực.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có, cùng 1 vấn đề nhưng thời gian giải quyết của từng nhóm đối tượng lại khác nhau mặc dù công cụ sử dụng có sự tương đồng về chức năng

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất khi viết Problem Statement là dễ rơi vào bẫy dùng các tính từ chung chung kiểu như "mất nhiều thời gian", "rất khó khăn", "kém hiệu quả", ... Thế nên việc phải tìm được 1 con số đo lường cụ thể là khâu đòi hỏi đào sâu dữ liệu thật, xác định pain point thật sự.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ khảo sát người dùng nhiều hơn thay vì ngồi đoán mò xem họ "đau" ở đâu, nhóm đôi khi mất quá nhiều thời gian để tranh luận dựa trên quan điểm cá nhân trước khi thực sự kiểm chứng. Điểm tôi sẽ phản biện nhóm quyết liệt hơn: Loại bỏ các ý tưởng "nghe có vẻ hay nhưng tần suất sử dụng không thường xuyên". Dừng những cuộc tranh luận lan man về "tính năng tương lai" trong khi chân dung bài toán, pain point thực sự chưa được xác định.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Ý tưởng chính của nhóm là chuẩn hóa báo cáo nhóm trước deadline, nhằm giải quyết tình trạng người tổng hợp mất nhiều thời gian chỉnh sửa định dạng, rà soát nội dung và kiểm tra các yêu cầu trong rubric. Quy trình hiện tại gồm thu thập bài từ các thành viên, kiểm tra nội dung, ghép tài liệu, chuẩn hóa và nộp báo cáo, trong đó bước chuẩn hóa là bottleneck lớn nhất. Nhóm đặt mục tiêu giảm tổng thời gian hoàn thiện báo cáo từ 120 phút xuống dưới 40 phút, đồng thời hạn chế lỗi định dạng và bỏ sót các tiêu chí bắt buộc. Về boundary, AI chỉ được phát hiện vấn đề và đề xuất chỉnh sửa, không tự ý thay đổi nội dung chuyên môn, tạo thông tin hoặc nộp bài khi chưa được người dùng phê duyệt. Nhóm lựa chọn mức can thiệp Workflow, trong đó Rule xử lý các yêu cầu định dạng, AI hỗ trợ rà soát nội dung và con người kiểm tra, quyết định cuối cùng. Nhóm không chọn Agent vì quy trình đã có các bước rõ ràng, không cần AI tự quyết định hành động tiếp theo. Quyết định hiện tại là NOT YET, do chưa có đủ bằng chứng cho thấy AI hiệu quả hơn template và checklist, vì vậy cần tiếp tục kiểm chứng trước khi triển khai.

---

## 7. Tài liệu tham khảo

- The Mom Test — Rob Fitzpatrick (https://www.momtestbook.com/)
- Testing Business Ideas — Strategyzer (https://www.strategyzer.com/library/testing-business-ideas-book-summary)
- How to Test Your Idea — Strategyzer (https://www.strategyzer.com/library/how-to-test-your-idea-start-with-the-most-critical-hypotheses)
