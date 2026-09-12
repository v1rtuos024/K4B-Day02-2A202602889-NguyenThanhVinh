# 01 — Individual Problem Scan

> Thực hiện theo Phase 1 và Phase 2 trong 01-worksheet.md. Các số có ký hiệu ~ là baseline ước lượng ban đầu và cần được xác nhận bằng cách bấm giờ trong lần thực hiện tiếp theo.

## Thông tin cá nhân

- **Họ và tên:** Nguyễn Thành Vinh
- **Mã học viên:** 2A202602889
- **Vai trò / bối cảnh:** Sinh viên năm 4, developer
- **Công việc hằng tuần:** học trên trường; xây dựng project nhóm; xây dựng project cá nhân; học kiến thức mới; thực tập tại doanh nghiệp.

---

## Phase 1 — Scan problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật / baseline ban đầu |
|---:|---|---|---|---|
| 1 | Lặp lại | Tôi phải tạo lịch nhắc hạn và kiểm tra VPS/domain bằng tay, dễ bỏ sót khi số tài nguyên tăng. | Bản thân tôi, người trực tiếp quản lý hạ tầng | Mỗi lần tạo hoặc cập nhật lịch mất khoảng **5 phút cho một VPS/domain**. |
| 2 | Pain từ người khác | Khối lượng lecture và lab lớn khiến học viên khó dành sự tập trung cho ngách chuyên môn riêng. | Tôi và các học viên có định hướng chuyên môn riêng | Một module có khoảng **4 giờ lecture + 4 giờ lab**; sau đó vẫn cần thời gian ngoài giờ để học theo định hướng cá nhân. |
| 3 | Lặp lại | Làm việc với nhiều hệ quản trị cơ sở dữ liệu thường kéo theo nhiều phần mềm client riêng. | Bản thân tôi khi phát triển nhiều project | Các công cụ/database liên quan hiện chiếm khoảng **20 GB** trên máy. |
| 4 | Tốn thời gian | Tôi phải tự lọc nhiều bài công nghệ có nội dung lặp lại, hời hợt hoặc thiếu nguồn trước khi tìm được bài hữu ích. | Bản thân tôi và người làm công nghệ đọc blog để cập nhật kiến thức | Trong **10 bài Medium gần đây tôi đọc thử, 8 bài** không mang lại đủ giá trị để ghi chú hoặc áp dụng. Đây là quan sát trên mẫu cá nhân, không phải thống kê toàn Medium. |
| 5 | Tốn thời gian | Việc chuyển liên tục giữa học trên trường, project nhóm, project cá nhân, tự học và thực tập làm tôi phải nhớ lại context trước khi bắt đầu. | Bản thân tôi | Có **5 bối cảnh công việc chính mỗi tuần**; thời gian khôi phục context chưa được bấm giờ. |
| 6 | Lặp lại | Mỗi project mới cần thiết lập lại môi trường, biến môi trường, database và lệnh chạy trước khi code. | Bản thân tôi và thành viên mới của project | Xuất hiện ở cả **project nhóm và project cá nhân**; baseline thời gian sẽ được bấm ở lần setup tiếp theo. |
| 7 | Tốn thời gian | Khi học công nghệ mới, tài liệu nằm rải rác giữa lecture, lab và tài liệu chính thức nên khó xác định thứ tự đọc. | Bản thân tôi | Phải đối chiếu ít nhất **3 loại nguồn**: lecture, lab và tài liệu chính thức; thời gian tìm/đối chiếu chưa được ghi log. |
| 8 | Pain từ người khác | Thành viên project nhóm có thể hiểu khác nhau về yêu cầu nếu quyết định và task nằm ở nhiều cuộc trao đổi. | Tôi và các thành viên project nhóm | Một yêu cầu liên quan ít nhất **2 phía**: người giao việc và người thực hiện; cần kiểm chứng thêm bằng số lần hỏi lại trong tuần. |
| 9 | AI có thể tốt hơn | Khi gặp lỗi kỹ thuật, tôi phải đọc nhiều kết quả tìm kiếm rồi tự nối triệu chứng, log và phiên bản thư viện. | Bản thân tôi khi phát triển project | Mỗi lần debug phải đối chiếu tối thiểu **3 loại dữ liệu**: error message, source code và tài liệu phiên bản; cần bấm giờ 3 phiên debug tiếp theo. |
| 10 | Lặp lại | Kiến thức hữu ích sau khi học chưa được chuyển đều đặn thành ghi chú ngắn có thể tìm lại cho project sau. | Bản thân tôi | Mỗi tuần có **5 bối cảnh công việc** tạo ra kiến thức mới, nhưng chưa có một workflow ghi chú chung; cần đo số lần phải tìm lại cùng nội dung. |

**AI đã dùng ở Phase 1:**

- **Prompt đã hỏi:** Hoàn thiện bảng scan từ các pain tôi đã ghi, phản biện các phát biểu quá rộng và chỉ giữ những candidate gắn với bối cảnh học tập/developer của tôi.
- **Ý dùng được:** Thu hẹp phát biểu “8/10 bài Medium do AI viết” thành quan sát cá nhân về giá trị sử dụng của 10 bài đã đọc; tách pain theo các bối cảnh công việc hằng tuần.
- **Ý bỏ vì chưa phải pain thật:** Các ý cần dữ kiện mà tôi chưa cung cấp, chẳng hạn số lần trễ deadline, số thành viên bị ảnh hưởng hoặc thời gian debug trung bình.

**Self-check Phase 1:**

- [x] Có 10 candidate problems; mỗi dòng có actor và dấu hiệu/baseline hoặc cách thu thập baseline rõ ràng.
- [x] Dùng đủ 4 lăng kính.
- [x] Các phát biểu chưa kiểm chứng được giới hạn phạm vi hoặc đánh dấu cần đo thêm.

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Quá tải giữa nội dung lecture/lab và kiến thức theo định hướng cá nhân | Actor và lịch học rõ; impact trực tiếp tới thời gian và khả năng tập trung; có thể thử một workflow nhỏ ngay trong module tiếp theo. | Chưa đo chính xác thời gian học thêm ngoài 8 giờ bắt buộc và chưa có quality metric ổn định. |
| 2 | Lọc bài viết công nghệ có giá trị thấp | Có mẫu quan sát ban đầu 10 bài; workflow tìm–đọc–kiểm nguồn vẽ được; AI có thể hỗ trợ phân loại nhưng vẫn cần người kiểm chứng. | Mẫu 10 bài còn nhỏ và tiêu chí “có giá trị” hiện mang tính cá nhân. |
| 3 | Quản lý hạn VPS/domain thủ công | Là công việc lặp lại, có thời gian 5 phút/tài nguyên và hậu quả bỏ sót dễ hiểu; có thể giải bằng rule đơn giản. | Chưa thống kê tổng số tài nguyên và số lần cập nhật mỗi tháng nên chưa biết impact tổng. |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Cá nhân hóa việc học sau lecture và lab

**Problem 1 câu:**
Sau 8 giờ lecture và lab của một module, học viên có định hướng riêng vẫn phải tự lọc tài liệu bổ sung và nối chúng với mục tiêu cá nhân, làm tăng tải học và dễ học dàn trải.

**Actor:**
Bản thân tôi — sinh viên năm 4, developer; rộng hơn là học viên vừa phải hoàn thành nội dung bắt buộc vừa theo một ngách chuyên môn.

**Thời điểm / bối cảnh:**
Sau mỗi block gồm 4 giờ lecture và 4 giờ lab, khi tôi cần ôn lại và chọn nội dung học thêm cho project hoặc định hướng nghề nghiệp.

**Current workflow:**

1. Tham gia lecture (240 phút).
2. Hoàn thành lab theo yêu cầu (240 phút).
3. Xem lại phần chưa hiểu và liệt kê câu hỏi.
4. Tìm thêm video, blog và tài liệu chính thức.
5. Đọc thử nhiều nguồn để xác định nội dung phù hợp với ngách cá nhân.
6. Tự ghi chú và thử áp dụng vào project.

**Bottleneck:**
Bước 4–5: tìm và đánh giá tài liệu bổ sung. Lecture/lab có phạm vi chung, còn tôi phải tự xác định nguồn nào đáng đọc cho mục tiêu riêng.

**Impact:**
8 giờ là thời gian học bắt buộc cho mỗi module; phần tìm và lọc tài liệu ngoài giờ chưa được ghi log nên tôi khó kiểm soát tổng tải học và dễ chuyển sang nhiều nguồn mà chưa áp dụng được.

**Success metric:**

- Trong module tiếp theo, bấm giờ toàn bộ phần tìm/lọc tài liệu để tạo baseline.
- Giảm ít nhất **30% thời gian tìm/lọc** ở module kế tiếp so với baseline đầu tiên.
- Sau mỗi module tạo được **1 learning plan tối đa 3 nguồn**, mỗi nguồn gắn với một mục tiêu hoặc task thực hành.
- Hoàn thành ít nhất **80% task đã chọn**, thay vì tiếp tục mở thêm nguồn mới.

**Non-AI alternative:**
Dùng learning checklist cố định, chỉ đọc tài liệu chính thức và giới hạn tối đa ba nguồn cho một chủ đề.

**AI hypothesis:**
AI nhận outline lecture/lab và mục tiêu cá nhân, sau đó đối chiếu để chỉ ra khoảng trống kiến thức, đề xuất thứ tự học và câu hỏi tự kiểm. Tôi tự chọn nguồn, kiểm link và quyết định learning plan cuối.

**Quick gut:** **Workflow** — input và các bước tương đối cố định; AI chỉ hỗ trợ lập bản đồ nội dung và gợi ý thứ tự.

**Draft workflow Card #1:**

    CURRENT STATE — 480 phút bắt buộc + thời gian ngoài giờ chưa đo

    [1 Lecture: 240']
    → [2 Lab: 240']
    → [3 Liệt kê phần chưa hiểu: ~15']
    → [4 Tìm nhiều nguồn: cần bấm giờ]
    → [5 Lọc theo định hướng: cần bấm giờ]  <-- bottleneck
    → [6 Ghi chú + thực hành: cần bấm giờ]

    FUTURE STATE — 480 phút bắt buộc + giảm ≥30% thời gian tìm/lọc

    [1 Lecture + lab: 480']
    → [2 Nhập outline + mục tiêu: ~5']
    → [3 AI lập gap map và gợi ý thứ tự: ~2']
    → [4 Tôi kiểm nguồn, chọn tối đa 3 mục: ~15']  <-- human boundary
    → [5 Thực hành + tự đánh giá]

    Fallback: nếu AI gợi ý sai trọng tâm hoặc nguồn không kiểm được,
    tôi bỏ gợi ý và dùng checklist + tài liệu chính thức.

---

#### Problem Card #2 — Lọc nội dung công nghệ trước khi đọc sâu

**Problem 1 câu:**
Khi cập nhật kiến thức qua blog công nghệ, tôi phải đọc thử nhiều bài lặp ý, thiếu chiều sâu hoặc thiếu nguồn trước khi tìm được nội dung đủ giá trị để áp dụng.

**Actor:**
Bản thân tôi — developer thường xuyên tự học công nghệ.

**Thời điểm / bối cảnh:**
Khi tìm bài viết để hiểu một công nghệ mới, giải quyết vấn đề trong project hoặc cập nhật xu hướng.

**Current workflow:**

1. Tìm theo từ khóa hoặc mở bài được đề xuất.
2. Đọc tiêu đề, mô tả và mục lục.
3. Đọc thử nội dung chính.
4. Kiểm tra ví dụ, nguồn tham chiếu và ngày xuất bản.
5. Đánh giá có nên ghi chú/áp dụng hay bỏ qua.
6. Lặp lại với bài tiếp theo.

**Bottleneck:**
Bước 3–4: chỉ sau khi đọc một phần đáng kể tôi mới nhận ra bài lặp lại, thiếu nguồn hoặc không phù hợp trình độ/mục tiêu.

**Impact:**
Trong mẫu 10 bài Medium gần đây, tôi chỉ giữ lại 2 bài để ghi chú hoặc áp dụng. Tỷ lệ loại 8/10 cho thấy nhiều công sức đọc thử chưa tạo ra đầu ra sử dụng được, nhưng cần đo thêm thời gian trên mẫu tiếp theo.

**Success metric:**

- Với 20 bài tiếp theo, ghi thời gian sàng lọc và số bài được giữ để có baseline đáng tin cậy hơn.
- Giảm ít nhất **50% số bài phải đọc sâu rồi mới loại**.
- Mỗi bài được giữ phải đạt ít nhất **3/4 tiêu chí**: đúng mục tiêu, có ví dụ cụ thể, có nguồn/tài liệu gốc, có thể tạo một ghi chú hoặc hành động.
- Không chấp nhận bài chỉ vì AI đánh giá cao; tôi phải kiểm ít nhất một nguồn gốc trước khi dùng.

**Non-AI alternative:**
Dùng checklist bốn tiêu chí, ưu tiên tài liệu chính thức/tác giả có uy tín, và đọc mục lục/kết luận trước khi đọc toàn bài.

**AI hypothesis:**
AI trích cấu trúc, claim chính, ví dụ và nguồn của từng bài; gắn cờ nội dung lặp hoặc thiếu bằng chứng. Tôi đọc lại đoạn quan trọng và tự quyết định giữ/bỏ.

**Quick gut:** **Workflow** — quy trình sàng lọc đi theo một đường cố định; chưa cần Agent tự tìm và tự quyết định thay người đọc.

**Draft workflow Card #2:**

    CURRENT STATE — baseline: 10 bài, loại 8 bài sau khi đọc thử

    [1 Tìm/mở bài]
    → [2 Đọc lướt]
    → [3 Đọc phần chính]
    → [4 Kiểm ví dụ + nguồn]  <-- bottleneck
    → [5 Giữ hoặc bỏ]

    FUTURE STATE — mục tiêu giảm ≥50% bài bị loại sau khi đã đọc sâu

    [1 Thu tối đa 20 link]
    → [2 Rule lọc ngày/tác giả/nguồn]
    → [3 AI trích claim, ví dụ, citation]
    → [4 Tôi kiểm nguồn gốc + chấm checklist]  <-- human boundary
    → [5 Đọc sâu bài đạt ≥3/4 tiêu chí]

    Fallback: nếu AI tóm tắt sai hoặc bỏ sót ngữ cảnh, tôi đọc bài gốc;
    nếu không kiểm được nguồn thì loại bài khỏi danh sách áp dụng.

---

#### Problem Card #3 — Theo dõi hạn VPS và domain

**Problem 1 câu:**
Mỗi khi thêm hoặc gia hạn VPS/domain, tôi phải tự nhập lịch nhắc và kiểm tra lại bằng tay khoảng 5 phút cho mỗi tài nguyên, nên dễ lệch ngày hoặc bỏ sót khi danh sách tăng.

**Actor:**
Bản thân tôi — người sở hữu và quản lý VPS/domain cho các project.

**Thời điểm / bối cảnh:**
Khi mua mới, gia hạn, đổi nhà cung cấp hoặc định kỳ rà soát ngày hết hạn.

**Current workflow:**

1. Đăng nhập trang quản trị của nhà cung cấp.
2. Mở từng VPS/domain và đọc ngày hết hạn.
3. Chuyển sang Calendar.
4. Tạo hoặc cập nhật sự kiện nhắc hạn.
5. Định kỳ kiểm tra lại giữa Calendar và nhà cung cấp.

**Bottleneck:**
Bước 2–4: sao chép ngày hết hạn giữa hai hệ thống. Mỗi tài nguyên mất khoảng 5 phút và có khả năng nhập sai hoặc quên cập nhật sau khi gia hạn.

**Impact:**
Tốn khoảng 5 phút cho mỗi lần thêm/cập nhật một tài nguyên. Hậu quả tiềm tàng của việc bỏ sót là domain hoặc dịch vụ hết hạn, nhưng tôi chưa có log về số lần bỏ sót nên không khẳng định tần suất.

**Success metric:**

- Giảm thao tác tạo/cập nhật nhắc hạn từ **5 phút xuống dưới 1 phút/tài nguyên**.
- **100% VPS/domain** trong danh sách có ngày hết hạn và hai mốc nhắc trước hạn.
- Khi rà soát hằng tháng, số ngày sai lệch giữa tracker và nhà cung cấp bằng **0**.

**Non-AI alternative:**
Dùng một bảng tracker chuẩn hóa với công thức tạo hai mốc nhắc, hoặc bật auto-renew và email nhắc hạn từ nhà cung cấp.

**AI hypothesis:**
AI không cần thiết cho luồng chính. AI chỉ có thể hỗ trợ đọc email hóa đơn không đồng nhất, nhưng rule/calendar automation đã giải quyết phần lớn bài toán với rủi ro thấp hơn.

**Quick gut:** **Rule**.

**Draft workflow Card #3:**

    CURRENT STATE — khoảng 5 phút/tài nguyên

    [1 Đăng nhập provider: ~1']
    → [2 Tìm ngày hết hạn: ~1']
    → [3 Nhập Calendar: ~2']  <-- bottleneck
    → [4 Kiểm lại: ~1']

    FUTURE STATE — dưới 1 phút/tài nguyên

    [1 Nhập/cập nhật ngày trong tracker]
    → [2 Rule tạo mốc nhắc 30 ngày và 7 ngày]
    → [3 Tôi kiểm dashboard hằng tháng]  <-- human boundary

    Fallback: nếu automation lỗi, email của provider và tracker là hai nguồn
    để tôi đối chiếu rồi tạo lịch thủ công.

---

### 2.3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:**
**Card #1 — Cá nhân hóa việc học sau lecture và lab.**

**Pitch 2 phút:**

    Mỗi module đã có 4 giờ lecture và 4 giờ lab, nhưng sau đó tôi vẫn phải tự tìm
    và lọc tài liệu để nối kiến thức chung với định hướng developer của mình.
    Điểm nghẽn không nằm ở 8 giờ bắt buộc mà nằm ở bước chọn đúng phần cần học tiếp:
    tài liệu rải rác, dễ mở quá nhiều nguồn và học dàn trải.

    Tôi đề xuất thử một workflow nhỏ: đưa outline và mục tiêu cá nhân cho AI để lập
    gap map, sau đó chính tôi kiểm nguồn và chỉ chọn tối đa ba mục để thực hành.
    Module đầu dùng để đo baseline; module sau đặt mục tiêu giảm ít nhất 30% thời gian
    tìm/lọc và hoàn thành ít nhất 80% task đã chọn. AI không quyết định nguồn cuối,
    không thay việc học và không đánh giá kết quả thay tôi.

**Câu hỏi tôi muốn nhóm challenge:**

1. Pain này đủ cụ thể ở bước tìm/lọc tài liệu chưa, hay vẫn đang gộp cả “quá tải học tập” quá rộng?
2. Ngoài thời gian tìm/lọc, metric nào chứng minh workflow giúp học đúng ngách hơn mà không làm giảm mức hiểu bài?

**AI phản biện Card:**

- **Điểm yếu AI chỉ ra:** Chỉ nói “quá tải” chưa đủ đo; 8 giờ lecture/lab là thời gian bắt buộc, không thể coi toàn bộ là bottleneck cần giảm. Mẫu 10 bài Medium cũng không chứng minh tác giả dùng AI.
- **Tôi sửa gì:** Thu hẹp bottleneck vào bước tìm/lọc tài liệu ngoài giờ; tách metric thời gian khỏi metric hoàn thành; đổi claim về Medium thành quan sát cá nhân về giá trị sử dụng; thêm human boundary và cách thu baseline.

### Self-check nộp phần 01

- [x] Có 5+ problems và top 3 Problem Cards đủ field.
- [x] Mỗi Card có workflow trước/sau, bottleneck, metric và fallback.
- [x] Đã chọn một card để pitch và chuẩn bị câu hỏi challenge.
- [x] Các dữ kiện chưa đo được ghi rõ là baseline cần thu thập, không trình bày như sự thật đã kiểm chứng.
