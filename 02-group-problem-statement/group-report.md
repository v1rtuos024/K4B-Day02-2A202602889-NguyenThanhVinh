# 02 — Group Problem Statement (Bản nộp nhóm)

> Bản này được tổng hợp từ 5 individual reports. Score, phân vai và quyết định cuối cần được cả nhóm xác nhận trước khi nộp. Không có interview/survey nào được ghi là đã thực hiện nếu chưa có bằng chứng.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò / đóng góp trong bản tổng hợp |
|---:|---|---|---|
| 1 | Nguyễn Thành Vinh | 2A202602889 | Tổng hợp convergence; workflow và Problem Statement |
| 2 | Trần Hữu Đức | 2A202602459 | Baseline về tìm tài liệu và candidate báo cáo |
| 3 | Đinh Văn Bình | 2A202602830 | Candidate tra cứu tài liệu; rủi ro hallucination và yêu cầu trích nguồn |
| 4 | Doãn Hữu Nguyên | 2A202602671 | Candidate lọc tài liệu dài; metric thời gian và độ hữu ích |
| 5 | Tô Huy Thông | 2A202602608 | Challenge Rule/Workflow/Agent; metric và phương án non-AI |

**Candidate problem nhóm chọn:**

Sinh viên phải đọc/lọc slide hoặc PDF dài để xác định phần cần ưu tiên theo mục tiêu học tập, mất khoảng 45–120 phút cho một tài liệu và vẫn có thể chọn sai trọng tâm.

---

## Phase 3 — Group Convergence: từ 15 candidates về 1

### 3.1. Trình bày top 3 mỗi người

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---:|---|---|---|---|---|
| 1 | Nguyễn Thành Vinh | Cá nhân hóa việc học sau lecture/lab | Sinh viên có định hướng chuyên môn riêng | Tìm và đánh giá tài liệu bổ sung sau 8 giờ học bắt buộc | Cùng cluster học tập; cần thu baseline ngoài giờ |
| 2 | Nguyễn Thành Vinh | Lọc bài viết công nghệ có giá trị thấp | Developer tự học | Chỉ nhận ra bài kém sau khi đã đọc sâu | Có mẫu 10 bài nhưng tiêu chí còn cá nhân |
| 3 | Nguyễn Thành Vinh | Theo dõi hạn VPS/domain | Người quản lý hạ tầng cá nhân | Chép ngày hết hạn sang Calendar | Rule đơn giản có thể đủ; impact tổng chưa rõ |
| 4 | Trần Hữu Đức | Viết daily report thủ công | Người viết report và quản lý | Nhớ lại rồi soạn từ đầu | Workflow rõ; 20–30 phút/ngày |
| 5 | Trần Hữu Đức | Tổng hợp báo cáo tuần từ daily reports | Người viết/nhận báo cáo | Đọc lại và viết lại thông tin đã có | Workflow rõ; 45–60 phút/tuần |
| 6 | Trần Hữu Đức | Tìm tài liệu tự học phù hợp | Người tự học | Search và đánh giá độ phù hợp | Mất 30–40% buổi học theo baseline ước tính |
| 7 | Đinh Văn Bình | Tra cứu quyền lợi và quy định CSVC | Sinh viên, nhất là khóa mới | Lục nhiều PDF/quy chế | RAG phù hợp nhưng cần dữ liệu chính thức |
| 8 | Đinh Văn Bình | Tóm tắt họp/chat thành task và deadline | Nhóm trưởng, thành viên | Trích task từ trao đổi tự do | Lặp lại; trưởng nhóm phải review |
| 9 | Đinh Văn Bình | Dữ liệu việc làm cựu sinh viên | Sinh viên năm 3–4 | Tìm dữ liệu khách quan, có kiểm chứng | Impact lớn nhưng thiếu data đầu vào |
| 10 | Doãn Hữu Nguyên | Theo dõi tiến độ nhóm | Nhóm trưởng và thành viên | Hỏi từng người rồi tổng hợp thủ công | Có thể chỉ cần task manager |
| 11 | Doãn Hữu Nguyên | Gom deadline từ nhiều nguồn | Sinh viên | Kiểm LMS, chat, email rồi ghi lại | Pain rõ; quyền truy cập nhiều nguồn là rủi ro |
| 12 | Doãn Hữu Nguyên | Lọc tài liệu học tập dài | Sinh viên | Đọc/lướt 50–150 trang để tìm phần quan trọng | Khớp trực tiếp với 3 report khác |
| 13 | Tô Huy Thông | Gom task từ nhiều nguồn trước khi lên lịch | Người lập kế hoạch tuần | Mở nhiều app, copy và loại trùng | Có thể pilot bán thủ công; tích hợp khó |
| 14 | Tô Huy Thông | Blank page khi lên lịch | Người lập kế hoạch tuần | Không có cấu trúc gợi nhớ task | Template có thể giải phần lớn |
| 15 | Tô Huy Thông | Ước lượng thời gian task thấp hơn thực tế | Người lập kế hoạch tuần | Ước lượng cảm tính, thiếu log lịch sử | Nên bắt đầu bằng rule và time log |

### 3.2. Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Học và tra cứu tài liệu | 1, 2, 6, 7, 9, 12 | Phải tìm, đọc và đánh giá nhiều nguồn trước khi ra được nội dung cần dùng | 4/5 thành viên có candidate trực tiếp về lọc tài liệu học tập |
| B — Báo cáo và tiến độ nhóm | 4, 5, 8, 10 | Biến note/chat/task rời rạc thành report hoặc action rõ ràng | Metric thời gian tốt; nguồn input không đồng nhất |
| C — Task, deadline và lập kế hoạch | 11, 13, 14, 15 | Gom việc, nhớ context, ước lượng rồi đưa vào lịch | Có nhiều phương án Rule/process fix |
| D — Quản lý tài nguyên kỹ thuật | 3 | Theo dõi trạng thái và hạn của tài nguyên | Pain cụ thể nhưng chỉ một thành viên nêu |

### 3.3. Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Lọc slide/PDF dài theo learning objectives | 4/5 report có pain gần nhau; actor và tài liệu đầu vào rõ; có baseline 45–120 phút; đo được cả thời gian và độ hữu ích | “Quan trọng” phụ thuộc môn và mục tiêu; baseline chủ yếu là tự ước tính |
| Tổng hợp report/tiến độ từ note và chat | Lặp hằng ngày/tuần; impact cộng dồn; workflow tuyến tính và human review rõ | Chất lượng output phụ thuộc input; có thể cần quyền truy cập nhiều công cụ |
| Gom task/deadline trước khi lập kế hoạch | Có ít nhất 2 report nêu pain trực tiếp; số nguồn và số task trễ đo được; so sánh Rule/Workflow/Agent tốt | Calendar/task manager có thể đã giải đủ; tích hợp Zalo/email/LMS khó trong lab |

### 3.4. Score để đồng thuận

Thang điểm 1–5. Đây là score tổng hợp từ nội dung report, chưa phải biên bản vote trực tiếp của nhóm.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Lọc slide/PDF theo mục tiêu học | 5 | 5 | 4 | 5 | 5 | 5 | 5 | **34** |
| Tổng hợp report/tiến độ | 5 | 5 | 4 | 5 | 5 | 5 | 4 | **33** |
| Gom task/deadline | 5 | 5 | 3 | 4 | 4 | 5 | 5 | **31** |

**Candidate nhóm chọn:**

Lọc slide/PDF dài để tạo bản đồ nội dung ưu tiên theo learning objectives.

**Vì sao chọn:**

Bốn trong năm individual reports độc lập mô tả pain về tìm, đọc hoặc lọc tài liệu học tập. Actor là sinh viên và nhóm có thể tự kiểm chứng bằng chính tài liệu đang học, không cần xin quyền truy cập hệ thống ngoài. Workflow hiện tại vẽ được rõ và có baseline từ 45–60 phút cho slide 60–80 trang, đến 60–120 phút cho tài liệu 50–150 trang. Bài toán cũng cho phép so sánh thẳng Rule, Workflow và Agent, đồng thời đặt human boundary ở bước sinh viên kiểm trang gốc. Scope pilot đủ nhỏ để làm trong lab: một learning objective, một slide deck và một bản đồ nội dung ưu tiên.

**Vì sao không chọn các candidate còn lại:**

- **Tổng hợp report/tiến độ:** Impact thời gian tốt nhưng chỉ report của Trần Hữu Đức có baseline daily/weekly trực tiếp. Các candidate họp nhóm và theo dõi tiến độ gần nhau về pattern, song không cùng output và có rủi ro “garbage in, garbage out”.
- **Gom task/deadline:** Calendar, task manager hoặc checklist nguồn có thể giải phần lớn trước khi cần AI. Nếu tự động kéo từ Zalo, email và LMS, scope sẽ chuyển sang permission/integration và khó pilot trong lab.
- **Tra cứu quyền lợi/CSVC:** Có use case RAG rõ nhưng chưa chắc nhóm có bộ quy định chính thức, đầy đủ và còn hiệu lực.
- **Quản lý VPS/domain:** Rule nhắc hạn giải được phần lớn, còn impact hiện chỉ được ghi nhận ở một thành viên.

**Disagreement / challenge:**

Không có biên bản thảo luận trực tiếp trong các file. Các report nêu ba challenge cần nhóm xác nhận: AI có xác định được “quan trọng” tốt hơn mục lục/checklist không; tiêu chí nào chứng minh gợi ý hữu ích; và AI phải trích đúng trang để tránh bịa hoặc bỏ sót. Bản nhóm giữ các challenge này làm điều kiện cho pilot thay vì coi tóm tắt là kết quả học tập.

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation

| Nguồn | Số người / mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Review 5 individual reports | 5 thành viên | 4/5 người nêu pain cùng cụm. Trần Hữu Đức: “phải mất 30–40% thời gian buổi học chỉ để tìm và lọc tài liệu phù hợp”. Doãn Hữu Nguyên: “một tài liệu 50–150 trang/slide có thể mất 60–120 phút để xác định phần cần ưu tiên”. | Tô Huy Thông không đưa pain này vào top 3; vì vậy chưa thể nói mọi sinh viên đều gặp. | Thu hẹp actor thành sinh viên thường xuyên phải tự lọc slide/PDF dài, không khẳng định 100% sinh viên. |
| Quan sát từ report Đinh Văn Bình | 1 trường hợp, slide 60–80 trang | “Mất 45–60'/môn để lọc ý chính”; đây là baseline gần nhất với scope slide deck của pilot. | Claim “70% sinh viên không đọc trước” chưa có survey đính kèm nên không dùng làm evidence nhóm. | Dùng baseline cá nhân 45–60 phút; không dùng tỷ lệ toàn lớp. |
| Interview / survey ngoài nhóm | Chưa thực hiện | Chưa có quote hoặc dữ liệu ngoài nhóm. | Baseline hiện là self-report và chưa được bấm giờ đồng nhất. | Pilot phải ghi log thời gian thật và hỏi 5 sinh viên trước khi mở rộng. |

**Insight sau validation:**

Pain không nằm ở việc đọc toàn bộ tài liệu, mà ở bước chuẩn bị: nối learning objectives với đúng phần của slide/PDF, giải thích vì sao phần đó đáng ưu tiên và kiểm lại trang gốc. Nhóm không đặt mục tiêu để AI quyết định nội dung nào được phép bỏ qua.

### 4.2. Research giải pháp đã có

| Nguồn / tool / case | Link chính thức | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google NotebookLM | https://support.google.com/notebooklm/answer/17003757 | Hỏi đáp và tổng hợp dựa trên nguồn người dùng đưa vào | Phản hồi trong NotebookLM được grounding riêng trên nguồn notebook, phù hợp với boundary “chỉ dùng tài liệu môn học” | Vẫn cần learning objective và người học đánh giá phần nào thực sự cần ưu tiên | Giới hạn nguồn tốt hơn để AI tự search web; yêu cầu chỉ đúng trang/đoạn |
| ChatGPT Study mode | https://help.openai.com/en/articles/11780217-using-study-mode-in-chatgpt | Làm việc với notes, slides, readings/PDF; đặt câu hỏi và kiểm tra mức hiểu | Hỗ trợ chia chủ đề, hỏi kiểu Socratic và tạo câu hỏi luyện tập | Tài liệu chính thức cảnh báo có thể sai hoặc bỏ sót nội dung file | Workflow phải có bước người học kiểm file gốc; không dùng output như đáp án cuối |
| Microsoft Copilot in OneDrive | https://support.microsoft.com/en-us/onedrive/summarize-your-files-with-copilot | Tóm tắt một hoặc nhiều Word, PowerPoint, PDF trong OneDrive | Có thể tóm tắt tối đa 5 file và hỏi tiếp theo chủ đề | Tóm tắt file chưa đồng nghĩa với chọn đúng phần theo learning objective; phụ thuộc tài khoản/licence | Không cần build chức năng tóm tắt chung; pilot nên tập trung vào objective-to-section mapping |

**Research takeaway:**

Các sản phẩm hiện có đã xử lý tốt bước upload và tóm tắt tài liệu. Khoảng trống đáng pilot là một workflow prompt có cấu trúc: learning objective → danh sách section/page ưu tiên → lý do → câu hỏi tự kiểm, sau đó sinh viên xác nhận trên tài liệu gốc. Nhóm chưa cần build Agent hay hệ thống RAG riêng trong lab.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Scope chuẩn hóa cho pilot: một slide/PDF 60–80 trang và learning objectives của môn học.

    CURRENT STATE — khoảng 45–60 phút chuẩn bị

    [1 Nhận slide/PDF: 1' — sinh viên]
    → [2 Đọc learning objectives/đề cương: 5' — sinh viên]
    → [3 Lướt 60–80 trang: 25–35' — sinh viên]  <-- bottleneck
    → [4 Đánh dấu phần có vẻ quan trọng: 10–12' — sinh viên]
    → [5 Viết danh sách ưu tiên/câu hỏi: 5–7' — sinh viên]
    → [6 Bắt đầu đọc sâu — ngoài scope đo thời gian chuẩn bị]

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Sinh viên | File từ giảng viên/LMS | Slide/PDF sẵn sàng | ~1 phút/tài liệu | Handoff từ giảng viên |
| 2 | Sinh viên | Đề cương, learning objectives | Tiêu chí đọc | ~5 phút/tài liệu | Nếu không có objective, sinh viên phải tự đặt mục tiêu |
| 3 | Sinh viên | 60–80 trang | Hiểu sơ bộ cấu trúc | ~25–35 phút/tài liệu | **Bottleneck:** đọc lướt nhiều trang |
| 4 | Sinh viên | Cấu trúc và nội dung đã lướt | Danh sách phần có vẻ quan trọng | ~10–12 phút/tài liệu | “Quan trọng” còn cảm tính |
| 5 | Sinh viên | Danh sách phần | Learning plan/câu hỏi ban đầu | ~5–7 phút/tài liệu | Output trước khi học sâu |
| 6 | Sinh viên | Learning plan + tài liệu | Kiến thức/ghi chú | Ngoài scope pilot | Không được bỏ bước học thật |

**Bottleneck chính:**

Sinh viên dành phần lớn thời gian chuẩn bị để lướt toàn bộ file rồi tự nối từng phần với learning objectives. Nếu chỉ tóm tắt chung, workflow vẫn chưa trả lời “tôi cần ưu tiên phần nào cho mục tiêu này”; nếu AI tự quyết mà không chỉ trang, người học khó phát hiện bỏ sót.

### 5.2. Future workflow bản nhóm

    FUTURE STATE — mục tiêu dưới 20 phút chuẩn bị

    [1 Sinh viên chọn file + learning objectives: 3']
    → [2 Rule trích heading/số trang: 1' — máy]
    → [3 AI map objective → section/page + lý do + câu hỏi: 2']
    → [4 Sinh viên mở đúng trang, kiểm và sửa map: 10']  <-- human boundary
    → [5 Sinh viên chốt tối đa 10 mục ưu tiên: 3']
    → [6 Bắt đầu đọc sâu — ngoài scope]

    Fallback: nếu file scan kém, AI không trích được trang, hoặc map sai nhiều,
    sinh viên dùng mục lục + checklist và lướt thủ công như current workflow.

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian tạo learning plan | 45–60 phút/tài liệu 60–80 trang | ≤20 phút | Bấm giờ từ lúc mở file đến khi chốt danh sách ưu tiên |
| Số bước chuẩn bị | 5 | 5 | Đếm bước trước khi đọc sâu; máy hỗ trợ bước 2–3 |
| Số bước hoàn toàn thủ công | 5/5 | 3/5 | Sinh viên vẫn chọn input, kiểm trang và chốt plan |
| Độ hữu ích của phần được gợi ý | Chưa có baseline | ≥80% mục được sinh viên chấp nhận sau khi kiểm | Số mục giữ lại / tổng mục AI gợi ý |
| Độ chính xác nguồn | Không áp dụng | 100% mục có đúng số trang; 0 nội dung ngoài nguồn | Mở từng citation/page để đối chiếu |
| Risk mới | Chọn sai trọng tâm do tự lướt | AI bỏ sót, ưu tiên sai hoặc bịa nội dung | Ghi lỗi theo từng output; sinh viên kiểm trước khi học |

### 5.3. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên phải chuẩn bị bài từ slide/PDF dài trước khi học sâu hoặc ôn tập. |
| **Workflow** | Nhận tài liệu → xem mục tiêu → lướt toàn file → đánh dấu phần quan trọng → tạo learning plan → đọc sâu. |
| **Bottleneck** | Lướt 60–80 trang và tự nối nội dung với learning objectives mất khoảng 25–35 phút trong tổng 45–60 phút chuẩn bị. |
| **Impact** | Thời gian chuẩn bị cao làm sinh viên dễ bỏ qua bước đọc trước hoặc chọn nội dung theo cảm tính. Report khác trong nhóm ghi nhận phạm vi 60–120 phút với tài liệu 50–150 trang, nhưng chưa đo theo cùng một protocol. |
| **Success Metric** | Giảm thời gian tạo learning plan xuống ≤20 phút; ≥80% mục AI gợi ý được sinh viên giữ lại; 100% mục có trang nguồn kiểm được. |
| **Boundary** | Chỉ xử lý file và objective do sinh viên cung cấp; không tự tìm nguồn ngoài, không quyết định phần được bỏ qua, không làm bài/thi thay và không thay việc đọc sâu. |

**Câu hỏi AI phản biện v0:**

- **Field mơ hồ:** “Nội dung quan trọng” phụ thuộc mục tiêu; “học nhanh hơn” không chứng minh hiểu tốt hơn; baseline từ nhiều report chưa cùng kích thước tài liệu.
- **Nhóm sửa:** Chuẩn hóa scope 60–80 trang, bắt buộc learning objectives làm context, đổi output thành “bản đồ nội dung ưu tiên”, thêm citation theo trang và coi điểm tự kiểm là guardrail chứ không hứa tăng kết quả học.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp

- **Độ mơ hồ:** [ ] Thấp / [x] Cao — Nhiều phần đều có thể hữu ích; thứ tự ưu tiên phụ thuộc learning objectives, trình độ và mục đích học.
- **Độ phức tạp:** [ ] Thấp / [x] Cao — Workflow có file, objective, cấu trúc trang, semantic mapping và bước review phụ thuộc nhau.

**Bài toán nhóm nằm ở ô nào:**

Mơ hồ cao, phức tạp cao về nội dung; tuy nhiên đường đi cố định và không cần hệ thống tự lập kế hoạch, nên mức triển khai phù hợp vẫn là **Workflow**.

**Vì sao:**

AI hữu ích ở phép nối ngữ nghĩa giữa objective và section, nơi keyword rule dễ bỏ sót cách diễn đạt khác nhau. Mọi tài liệu vẫn đi qua cùng năm bước và sinh viên quyết định output cuối, nên thêm Agent sẽ tăng quyền tự chủ và rủi ro mà không giải thêm bottleneck.

### 6.1. So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Trích mục lục/heading; tìm keyword từ learning objectives; tạo checklist cố định | Đủ khi slide có cấu trúc tốt và dùng đúng từ khóa | Bỏ sót section dùng từ đồng nghĩa hoặc cần hiểu context; chưa giải thích lý do ưu tiên | Dùng cho bước trích cấu trúc, không chọn cho toàn bài |
| **Workflow** | Rule trích cấu trúc → AI map objective với section/page → sinh viên kiểm → chốt learning plan | Hợp khi input và thứ tự bước cố định nhưng cần hiểu ngữ nghĩa | AI ưu tiên sai hoặc bịa; cần kiểm citation | **Chọn** |
| **Agent** | Tự lấy file từ LMS, tự tìm thêm nguồn, tự lập kế hoạch và theo dõi tiến độ | Chỉ đáng cân nhắc nếu cần nhiều tool, nhiều nhánh và quyền tự quyết | Permission, privacy, nguồn ngoài không kiểm soát, scope quá lớn | Không chọn |

**5 câu hỏi chốt:**

1. **Rule có giải được 70–80% case không?** Chưa chắc. Rule giải tốt bước trích heading/keyword nhưng không đủ để đánh giá sự liên quan khi objective và slide dùng cách diễn đạt khác nhau.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Các bước đi thẳng: chọn input → trích cấu trúc → map → review → chốt. Trường hợp file lỗi dùng fallback thủ công.
3. **Có thật sự cần Agent tự lập kế hoạch và gọi tool không?** Không. Pilot không cần tự truy cập LMS, tự search web hoặc tự theo dõi người học.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** Sinh viên phát hiện ở bước mở trang gốc; mục tiêu review toàn bộ map trong tối đa 10 phút.
5. **Có hạ từ Agent xuống Workflow hoặc Rule không?** Có thể hạ từ Agent xuống Workflow. Rule được dùng cho trích cấu trúc, nhưng chưa đủ cho semantic mapping của toàn bài toán.

**Mức chọn:**

**Workflow.**

**Vì sao chọn:**

Input, output và thứ tự xử lý đã xác định rõ nên Workflow dễ pilot và đo. AI chỉ can thiệp ở bước map learning objective với section/page, còn Rule làm phần trích cấu trúc. Sinh viên phải kiểm từng mục trên tài liệu gốc trước khi chốt, nhờ đó rủi ro có người sở hữu rõ. Agent không tạo thêm giá trị trong scope hiện tại.

**Vì sao không chọn mức đơn giản hơn:**

Checklist, mục lục và keyword search là baseline non-AI bắt buộc để so sánh. Tuy nhiên chúng không giải thích được quan hệ ngữ nghĩa khi tài liệu dùng từ khác learning objective hoặc một objective cần kết hợp nhiều section. Vì vậy Rule được giữ như một thành phần, không phải toàn bộ solution.

### 6.2. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học thường xuyên phải tự chuẩn bị bài từ slide/PDF dài; pilot với 5 thành viên nhóm. |
| **Workflow** | Chọn file 60–80 trang và learning objectives → trích cấu trúc → tạo objective-to-section map → kiểm trang gốc → chốt tối đa 10 mục ưu tiên → đọc sâu. |
| **Bottleneck** | Trong current workflow, sinh viên lướt toàn file 25–35 phút rồi đánh dấu thủ công, khiến tổng thời gian tạo learning plan khoảng 45–60 phút. |
| **Impact** | 4/5 report thành viên nêu pain cùng cụm; một report ghi 45–60 phút cho slide 60–80 trang và một report ghi 60–120 phút cho tài liệu 50–150 trang. Các số là self-report, cần pilot bấm giờ lại. |
| **Success Metric** | Median thời gian chuẩn bị ≤20 phút và giảm ≥50% so với baseline của cùng người; ≥80% mục gợi ý được giữ; 100% mục có trang nguồn đúng. |
| **Boundary (làm / không làm)** | Làm: map objective với section/page, nêu lý do và gợi ý câu hỏi tự kiểm. Không làm: tự search web, quyết định phần được bỏ, làm bài/thi, chấm điểm hoặc thay việc đọc tài liệu gốc. |
| **AI intervention point** | Sau khi Rule trích heading/số trang và trước khi sinh viên mở trang gốc để review. |
| **Mức chọn** | Workflow — đường đi cố định, kết hợp Rule cho cấu trúc, AI cho semantic mapping và người học cho quyết định cuối. |
| **Rủi ro & người thật kiểm tra** | Rủi ro lớn nhất là AI bỏ sót/ưu tiên sai hoặc tạo nội dung không có trong tài liệu. Sinh viên kiểm từng mục bằng số trang; mục không kiểm được bị xóa. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor là sinh viên có slide/PDF dài; workflow và output pilot đã chuẩn hóa. |
| Baseline + metric đo được chưa? | Not Yet | Có self-report 45–60 phút và 60–120 phút, nhưng chưa bấm giờ theo cùng protocol; pilot sẽ thu baseline thật. |
| Data/input đủ dùng chưa? | Yes | Chỉ cần 2 slide/PDF môn học và learning objectives tương ứng. |
| AI sai, hậu quả chấp nhận được không? | Yes trong scope pilot | Output chỉ là gợi ý; sinh viên kiểm trang gốc, không tự nộp hoặc chấm điểm. |
| Có người review/owner không? | Yes | Mỗi sinh viên là owner của learning plan của mình. |
| Có cách non-AI đơn giản hơn không? | Yes | Mục lục + keyword + checklist là comparator bắt buộc trong pilot. |

**Decision:**

**Go với scope nhỏ.**

**Lý do:**

Pain được lặp lại trong 4/5 individual reports, actor và input đều nằm trong quyền kiểm soát của nhóm. Có baseline ban đầu, metric đo được và phương án non-AI để so sánh. AI chỉ làm một bước ngôn ngữ cụ thể, còn sinh viên kiểm nguồn và quyết định learning plan. Dù chưa có survey ngoài nhóm, rủi ro pilot thấp và có thể rollback ngay.

**Pilot nhỏ nhất:**

- **Mẫu:** 5 thành viên, 2 slide/PDF dài 60–80 trang có learning objectives.
- **Cách chạy:** Với tài liệu A, đo current workflow bằng mục lục/keyword/checklist. Với tài liệu B, chạy Workflow AI. Đổi thứ tự A/B giữa các thành viên để giảm bias do thứ tự.
- **Ba số đo:** (1) phút từ lúc mở file đến khi chốt plan; (2) tỷ lệ mục AI gợi ý được giữ sau review; (3) tỷ lệ mục có citation đúng trang và không có nội dung ngoài nguồn.
- **Guardrail:** Sau khi đọc, dùng cùng một rubric 5 câu để kiểm mức hiểu; Workflow không đạt nếu tiết kiệm thời gian nhưng điểm hiểu giảm rõ rệt.

**Nếu Not Yet — cần validate gì trước:**

Không áp dụng cho quyết định hiện tại. Trước khi mở rộng ngoài nhóm, cần survey/interview ít nhất 5–10 sinh viên và đo baseline theo cùng một loại tài liệu.

**Nếu No-Go — làm gì thay AI:**

Không áp dụng cho quyết định hiện tại. Phương án thay thế luôn sẵn có là mục lục + keyword search + checklist theo learning objectives.

**Exit / rollback:**

Dừng AI và quay về checklist nếu median thời gian không giảm ít nhất 30%, dưới 80% mục gợi ý được giữ, xuất hiện bất kỳ nội dung không truy được về trang nguồn sau review, hoặc điểm tự kiểm thấp hơn rõ rệt so với workflow cũ. Nếu Rule keyword + mục lục đạt kết quả tương đương Workflow, hạ solution xuống Rule.

---

### Self-check nộp phần 02

- [x] Có nhật ký hội tụ 15 → 1, gồm cluster, shortlist và score.
- [x] Có validation nội bộ từ 5 reports; ghi rõ chưa có interview/survey ngoài nhóm; có research bằng link chính thức.
- [x] Có workflow trước/sau với thời gian, actor, bottleneck, boundary và fallback.
- [x] Có Problem Statement v0 → v1; metric trước/sau, cách đo và boundary rõ.
- [x] Có so sánh Rule/Workflow/Agent và quyết định Go với scope nhỏ dựa trên bằng chứng.
