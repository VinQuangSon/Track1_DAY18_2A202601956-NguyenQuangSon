# Track 1 — Day 17: Finding and Validating Pain Points

> **Case:** AI Support Radar  
> **Lưu ý về integrity:** Các phần Problem Framing, Evidence Map và Conversation Guide dưới đây là **hypothesis / research design**, không phải fact về user. Phần Interview Record và recording phải đến từ người được phỏng vấn thật. Không dùng mock interview như evidence khi nộp.

---

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202601916
- **Họ tên:** Lê Đăng Tấn
- **Tên nhóm:** Mixue
- **Thành viên:**:
    - Lê Đăng Tấn - 2A202601916
    - Nguyễn Quang Sơn - 2A202601956
    - Phạm Tiến Hưng - 2A202601800
    - Nguyễn Minh Quang - 2A202601730
- **Case đã chọn:** AI Support Radar

---

# 2. Problem Hypothesis Brief

## 2.1. Solution — gỡ solution khỏi hình thức cụ thể

### Solution directive

Sau mỗi phiên học, hệ thống phân tích các tín hiệu như di chuyển giữa slide, dừng lâu hoặc xem lại, highlight và ghi chú, đánh dấu “Chưa hiểu”, thay đổi câu trả lời, và nội dung trao đổi với AI Chat. AI tạo một Support Queue cho giảng viên, gồm người học có thể cần hỗ trợ, nội dung có thể đang gặp khó khăn, các tín hiệu dẫn đến nhận định và một hành động hỗ trợ được đề xuất. Giảng viên xem lại và quyết định có liên hệ hay không.

### Capability trung tính

> Giúp người phụ trách học tập **nhận biết sớm những learner có khả năng đang bị mắc kẹt, hiểu bối cảnh của khó khăn và ưu tiên ai cần được hỗ trợ trước**, mà không phải tự theo dõi thủ công toàn bộ hành vi học tập.

Capability này không phụ thuộc vào tên “Radar”, giao diện Support Queue hay việc bắt buộc phải dùng AI.

---

## 2.2. Change — chuỗi thay đổi được kỳ vọng

```text
Tín hiệu học tập rời rạc
→ được tổng hợp thành thông tin dễ chú ý
→ instructor/coach nhận ra learner có thể cần hỗ trợ
→ instructor/coach ưu tiên và chọn cách can thiệp
→ learner nhận hỗ trợ đúng lúc
→ giảm tình trạng khó khăn kéo dài mà không được xử lý
```

### Các thay đổi được kỳ vọng

1. **Awareness:** Instructor/coach biết sớm hơn learner nào có thể đang gặp khó khăn và ở nội dung nào.
2. **Behavior:** Instructor/coach dành sự chú ý và hành động hỗ trợ cho các trường hợp cần thiết thay vì chỉ chờ learner chủ động hỏi.
3. **Outcome:** Learner có khả năng giải quyết điểm vướng sớm hơn và tiếp tục tiến trình học với ít “unresolved confusion” hơn.

### Output vs. Outcome

- **Output team có thể tạo:** danh sách/cờ cảnh báo, context, mức ưu tiên, gợi ý hỗ trợ.
- **Outcome team chỉ có thể ảnh hưởng:** instructor có thật sự can thiệp không; learner có nhận/đón nhận hỗ trợ không; khó khăn có được giải quyết không.

---

## 2.3. Actor — các nhóm liên quan

| Actor | Họ đang làm gì? | Pain/hậu quả có thể có | Họ hưởng lợi thế nào? |
|---|---|---|---|
| **Learner** | Học qua slide, bài tập, ghi chú, AI Chat; tự quyết định có hỏi trợ giúp hay không | Có thể mắc kẹt nhưng không biết cách diễn đạt, không chắc vấn đề đủ lớn để hỏi, ngại làm phiền hoặc không nhận ra mình hiểu sai | Nhận hỗ trợ sớm hơn ở đúng điểm vướng |
| **Instructor** | Theo dõi tiến độ nhiều learner, giải đáp và quyết định ai cần can thiệp | Không nhìn thấy “silent struggle”; dữ liệu phân tán; khó ưu tiên khi thời gian hạn chế | Có context để ưu tiên hỗ trợ và giảm missed cases |
| **Coach/TA** | Hỗ trợ learner theo ca/lab, follow-up vấn đề cụ thể | Thiếu context trước khi trao đổi; phụ thuộc learner tự báo | Chuẩn bị hỗ trợ nhanh hơn và đúng trọng tâm |

### Actor nhóm chọn để điều tra trước

> **Learner**

### Vì sao chọn learner trước

1. Core assumption của solution là **hành vi học tập có thể phản ánh một nhu cầu hỗ trợ có thật**.
2. Nếu learner thực tế không có một pain đáng kể, hoặc họ đã có cách tự xử lý đủ tốt, thì việc phát hiện tín hiệu chính xác đến đâu cũng không tạo nhiều giá trị.
3. Brief đề xuất ưu tiên **hai learners + một coach/instructor**, nên learner-side evidence là nhánh có thể được triangulate tốt nhất trong vòng lab này.
4. Instructor vẫn là dependency quan trọng và cần một interview riêng để kiểm tra khả năng hành động sau khi phát hiện vấn đề.

---

## 2.4. Situation & Job

### Mô tả Situation & Job

> Khi đang học một nội dung mới và gặp một đoạn khiến mình không chắc đã hiểu đúng hoặc không thể tiếp tục bài tập, **learner** đang cố **xác định mình đang vướng ở đâu và tìm đủ hỗ trợ để tiếp tục học**, bằng cách **xem lại slide, sửa câu trả lời, ghi chú/highlight, thử hỏi AI, tìm tài liệu khác hoặc cân nhắc hỏi người khác**.

### JTBD Hypothesis

> Khi tôi bị mắc ở một phần nội dung trong lúc tự học, tôi muốn **nhanh chóng xác định điểm mình chưa hiểu và tìm được mức hỗ trợ phù hợp**, để có thể **tiếp tục học mà không mang theo một lỗ hổng chưa được giải quyết**.

---

## 2.5. Pain — hai cách giải thích cạnh tranh

### Pain Hypothesis A — “Có nhu cầu hỗ trợ nhưng không chủ động phát tín hiệu rõ ràng”

> Khi gặp một phần nội dung khó trong lúc tự học, learner gặp khó khăn trong việc **nhận được sự hỗ trợ đúng lúc** vì họ **không phải lúc nào cũng chủ động hỏi người khác: có thể chưa diễn đạt được câu hỏi, không chắc vấn đề có đáng để hỏi, ngại làm phiền hoặc ưu tiên tự thử thêm**, dẫn đến **mất nhiều thời gian, bỏ qua nội dung hoặc tiếp tục học khi điểm chưa hiểu vẫn còn**.

### Pain Hypothesis B — “Vấn đề chính là tự chẩn đoán, không phải thiếu kênh hỗ trợ”

> Khi gặp một phần nội dung khó trong lúc tự học, learner gặp khó khăn trong việc **biết chính xác mình đang hiểu sai ở đâu** vì họ **có thể không nhận ra misunderstanding hoặc chỉ cảm thấy mơ hồ rằng mình ‘chưa chắc’**, dẫn đến **việc xem lại/hỏi AI lặp lại nhưng không xử lý đúng root cause**.

### Giả thuyết chọn điều tra trước

> **A**, nhưng interview phải chủ động tìm evidence có thể khiến nhóm chuyển sang B hoặc bác bỏ cả hai.

### Lý do chọn A

- Nó là assumption trực tiếp nhất nối learner pain với khả năng “phát hiện nhu cầu hỗ trợ”.
- Nếu learner **đã luôn chủ động hỏi** khi cần và các kênh hiện tại hoạt động tốt, core value của Support Radar yếu đi rõ rệt.
- Nếu interview cho thấy learner **không biết mình đang sai**, nhóm sẽ chuyển trọng tâm sang B.

---

## 2.6. Evidence Map

| Cần kiểm tra | Evidence làm nhóm tin hơn | Evidence làm nhóm nghi ngờ/bác bỏ |
|---|---|---|
| **Situation có thật** | Learner kể được một lần gần đây họ mắc ở slide/bài tập cụ thể và mô tả được sequence | Chỉ kể chung chung; không nhớ tình huống thực tế gần đây |
| **Pain có ý nghĩa** | Mất nhiều thời gian, bỏ dở, đoán mò, nộp sai, phải quay lại sau, ảnh hưởng phần sau | Chỉ hơi bất tiện vài phút và tự xử lý ngay |
| **Workaround tồn tại** | Xem lại nhiều lần, đổi câu trả lời, ghi chú, hỏi AI, search, nhắn bạn, bỏ qua rồi quay lại | Không cần workaround hoặc chỉ dùng một cách đơn giản là đủ |
| **Consequence tồn tại** | Delay, frustration, misunderstanding kéo dài, chất lượng bài giảm, phải nhờ hỗ trợ muộn | Không có hậu quả đáng kể |
| **Pattern có lặp** | Tình huống tương tự xảy ra nhiều hơn một lần / ở nhiều buổi | Chỉ là ngoại lệ hiếm |
| **Hidden support need tồn tại** | Có lúc learner cần hỗ trợ nhưng không hỏi instructor/coach | Hầu như lúc nào cần họ cũng hỏi ngay |
| **Instructor-side actionability** | Instructor từng bỏ sót learner và sẽ hành động nếu có context đáng tin | Instructor đã biết rõ ai đang khó; bottleneck thật là không có thời gian/quyền xử lý |

---

## 2.7. Problem Hypothesis chốt

> Khi đang tự học một nội dung mới và bị mắc ở một phần cụ thể, **một số learner không nhận được hỗ trợ đúng lúc** vì nhu cầu hỗ trợ của họ **không được phát ra thành một yêu cầu rõ ràng** — họ có thể tiếp tục tự thử, xem lại, đổi đáp án hoặc hỏi AI thay vì chủ động hỏi instructor/coach — dẫn đến **thời gian bị kéo dài, điểm chưa hiểu bị bỏ lại hoặc họ tiếp tục học với một misunderstanding chưa được xử lý**.

### Điều gì phải đúng để giả thuyết đứng vững

1. Situation này xảy ra đủ thường xuyên.
2. Hậu quả đủ đáng kể để đáng giải.
3. Có trường hợp learner cần hỗ trợ nhưng **không chủ động hỏi**.
4. Một người hỗ trợ khác thực sự có thể làm gì đó hữu ích nếu nhận biết sớm.
5. Tín hiệu hành vi không chỉ phản ánh “learning style” bình thường mà có liên hệ với khó khăn thực tế.

### Điều gì có thể khiến nhóm sửa hoặc bác bỏ

- Learner luôn tự xử lý hiệu quả và hiếm khi cần người khác.
- Learner chủ động hỏi ngay khi cần nên không có “silent struggle”.
- Hành vi như xem lại/highlight/đổi đáp án thường là chiến lược học tích cực, không phải dấu hiệu khó khăn.
- Instructor đã biết ai cần hỗ trợ nhưng không thể hành động vì thiếu thời gian, ownership hoặc nguồn lực.
- Hậu quả của việc hỗ trợ chậm là rất nhỏ.

---

## 2.8. Solution Parking Lot

| Hướng giải quyết | AI / Không AI |
|---|---|
| 1. Support Queue ưu tiên learner dựa trên nhiều tín hiệu hành vi và context | AI |
| 2. Rule-based flags: ví dụ nhiều lần đổi đáp án + “Chưa hiểu” + xem lại quá N lần | Không AI |
| 3. “Exit check” cuối phiên: learner tự chọn mức hiểu + nút yêu cầu follow-up | Không AI |
| 4. Coach review định kỳ danh sách learner có quiz errors hoặc session incomplete | Không AI |
| 5. Hệ thống gợi ý tài nguyên/hướng hỗ trợ khác nhau trước khi escalation sang người thật | AI |
| 6. Peer-help / office-hour routing dựa trên topic learner đang vướng | Có thể không AI |

---

# 3. Conversation Guide phiên bản cuối

## 3.1. Big 3 — ba điều quan trọng nhất cần học

| Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết? |
|---|---|---|
| **1. Lần gần nhất learner bị mắc nhưng không hỏi người hỗ trợ ngay đã diễn ra như thế nào?** | Sequence cụ thể: trigger → hành vi → workaround → quyết định có/không hỏi | Learner nói họ luôn hỏi ngay hoặc situation gần như không xảy ra |
| **2. Việc trì hoãn/không hỏi gây hậu quả thực tế gì?** | Time cost, bỏ dở, sai tiếp, frustration, quay lại, ảnh hưởng phần sau | Không có consequence đáng kể; tự xử lý trong thời gian rất ngắn |
| **3. “Scary question”: hành vi nhìn giống khó khăn có thật sự nghĩa là cần hỗ trợ không?** | Cùng một hành vi (xem lại, đổi đáp án, highlight, hỏi AI) và lý do thực tế phía sau | Các hành vi này chủ yếu là thói quen học tốt/khám phá, không phản ánh pain |

---

## 3.2. Tiêu chí tuyển người

### Learner

> Chúng tôi cần nói chuyện với người đã **có ít nhất một lần bị mắc ở một phần nội dung/bài tập khi tự học và phải tự tìm cách xử lý** trong vòng **14 ngày gần đây**.

### Coach/Instructor

> Chúng tôi cần nói chuyện với người đã **theo dõi tiến độ của nhiều learner và có ít nhất một lần phải quyết định ai cần được hỗ trợ/follow-up** trong vòng **30 ngày gần đây**.

### Recruitment check — Learner

> “Trong 14 ngày gần đây, bạn có nhớ một lần đang học mà bị mắc ở một phần cụ thể và phải thử ít nhất một cách để tự xử lý không?”

### Recruitment check — Instructor/Coach

> “Trong 30 ngày gần đây, bạn có lần nào phải nhìn vào tiến độ/kết quả của nhiều learner rồi quyết định ai cần được hỗ trợ trước không?”

---

## 3.3. Lời mở đầu

> “Bọn mình đang tìm hiểu cách mọi người xử lý những lúc bị mắc trong quá trình học và cách người hỗ trợ nhận biết những trường hợp cần giúp. Mình muốn nghe về những việc đã thực sự xảy ra gần đây, không có câu trả lời đúng sai. Mình sẽ không giới thiệu hay xin feedback về một tính năng. Nếu bạn đồng ý, mình muốn ghi âm để xem lại chính xác nội dung phỏng vấn; bản ghi chỉ dùng cho bài học và không chia sẻ công khai.”

---

## 3.4. Story opener — Learner

> “Kể mình nghe về **lần gần nhất bạn đang học một nội dung và bị mắc ở một chỗ đến mức phải dừng lại để tìm cách xử lý**?”

### Big 3 Questions — Learner

| Điều cần học | Câu hỏi sẽ dùng |
|---|---|
| 1. Sequence và quyết định có hỏi hay không | “Từ lúc nhận ra mình bị mắc, bạn đã làm gì tiếp theo, theo đúng thứ tự?” |
| 2. Consequence | “Việc đó cuối cùng làm bạn mất gì hoặc ảnh hưởng đến phần học tiếp theo như thế nào?” |
| 3. Scary question về tín hiệu hành vi | “Trong lần đó, có hành vi nào như xem lại, đổi đáp án, ghi chú, highlight hoặc hỏi AI không? Với từng việc, lúc đó bạn làm vì lý do gì?” |

### Probe bank — Learner

- “Lúc đó chuyện gì xảy ra tiếp theo?”
- “Bạn đã làm gì trước tiên?”
- “Vì sao bạn chọn cách đó?”
- “Bạn mất khoảng bao lâu?”
- “Có lúc nào bạn nghĩ đến việc hỏi instructor/coach/bạn học không?”
- “Điều gì khiến bạn hỏi / không hỏi?”
- “Bạn biết vấn đề đã được giải quyết bằng cách nào?”
- “Nếu chưa giải quyết, bạn đã làm gì tiếp?”
- “Lần trước đó chuyện tương tự xảy ra khi nào?”

> **Không hỏi:** “Nếu có AI tự phát hiện bạn đang khó thì bạn có dùng không?”

---

## 3.5. Story opener — Instructor/Coach

> “Kể mình nghe về **lần gần nhất bạn phát hiện một learner đang cần hỗ trợ nhưng họ chưa chủ động nói rõ với bạn từ đầu**?”

### Big 3 Questions — Instructor/Coach

1. “Bạn phát hiện trường hợp đó bằng cách nào? Có tín hiệu cụ thể nào khiến bạn chú ý?”
2. “Bạn đã quyết định có can thiệp hay không dựa trên những thông tin nào?”
3. **Scary question:** “Có trường hợp nào bạn đã biết learner đang gặp khó nhưng vẫn không follow-up được không? Điều gì thực sự cản bạn?”

### Probe bank — Instructor/Coach

- “Bạn đang theo dõi bao nhiêu learner lúc đó?”
- “Tín hiệu nào đáng tin, tín hiệu nào dễ hiểu nhầm?”
- “Bạn đã bỏ sót trường hợp nào gần đây chưa?”
- “Nếu có thêm context, context nào thật sự thay đổi quyết định của bạn?”
- “Bạn cần biết điều gì trước khi liên hệ learner?”
- “Việc follow-up tốn bao nhiêu thời gian/công sức?”
- “Điều gì xảy ra nếu bạn không can thiệp?”

---

## 3.6. Ba phản xạ khi data lệch

| User đưa ra | Phản xạ | Cách quay lại evidence |
|---|---|---|
| Lời khen | **Deflect** | “Cảm ơn bạn. Quay lại lần gần nhất đó, lúc ấy bạn đã làm gì?” |
| Câu chung chung / dự đoán tương lai | **Anchor** | “Lần gần nhất chuyện đó thực sự xảy ra là khi nào?” |
| Feature request / ý tưởng | **Dig** | “Điều đó giúp bạn hoàn thành việc gì? Hiện tại bạn đang xử lý việc đó ra sao?” |

---

# 4. Interview Plan

## Ưu tiên người phỏng vấn

1. **Learner 01** — đáp ứng tiêu chí 14 ngày.
2. **Learner 02** — đáp ứng tiêu chí 14 ngày.
3. **Coach/Instructor 01** — từng review/ưu tiên hỗ trợ learner trong 30 ngày.

### Nếu không có coach/instructor trong giờ lab

Ghi đúng câu sau trong README/note:

> **“Vòng này chỉ có learner-side evidence; instructor-side job chưa được kiểm chứng.”**

---

# 5. Practice Reflection — bản khung để hoàn thiện sau interview thật

> **Không nộp các câu dưới đây như fact nếu bạn chưa thực sự phỏng vấn.** Sau practice, thay nội dung trong ngoặc vuông bằng việc đã xảy ra.

### 1. Câu hỏi nào đã giúp user kể một tình huống cụ thể?

> Câu hỏi hiệu quả nhất là: **“Kể mình nghe về lần gần nhất bạn đang học một nội dung và bị mắc ở một chỗ đến mức phải dừng lại để tìm cách xử lý?”**  
> Nó buộc conversation bám vào một event có thời điểm, context và sequence thay vì opinion chung.  
> **Evidence từ practice thật:** Với learner L01, câu hỏi về lần gần đây bị vướng đã mở ra một tình huống cụ thể: learner không hiểu bài nhưng ngại giơ tay hỏi giảng viên, sau đó chuyển sang hỏi AI, Google và bạn bè. Với instructor I01, câu hỏi về learner gặp khó nhưng chưa chủ động hỏi giúp khai thác được cách instructor theo dõi checkpoint VLab và chủ động đến bàn xác nhận.

### 2. Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?

> Mình cần tránh nhảy quá nhanh sang “vì sao” hoặc giải thích hộ interviewee. Khi nghe một tín hiệu như “mình xem lại mấy lần”, nên hỏi **“sau lần xem lại đầu tiên thì bạn làm gì tiếp?”** trước khi suy luận đó là khó khăn.  
> **Moment cụ thể từ practice:** Ở interview instructor, mình đã đưa sẵn quá nhiều ví dụ như “buồn ngủ”, “mất tập trung”, “sang tab khác”, “Facebook”, “chơi game”, khiến câu hỏi bị leading. Ở interview learner, mình cũng ngắt câu chuyện bằng câu “chỉ cần trả lời là mình vướng mắc ở đâu”, làm mất cơ hội đào sâu sequence tự nhiên của event.

### 3. Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?

> Nhóm sửa guide theo hướng:
> - thay câu hỏi opinion bằng câu hỏi về **lần gần nhất**;
> - tách “hành vi” khỏi “ý nghĩa của hành vi”, vì xem lại/highlight có thể là learning strategy bình thường;
> - thêm scary question cho instructor: **“Có trường hợp bạn đã biết learner gặp khó nhưng vẫn không follow-up được không?”** để kiểm tra xem bottleneck thật có phải detection hay không.
>
> **Sửa đổi phát sinh từ practice thật:** Sau hai lượt interview, nhóm sửa guide theo ba điểm: (1) mở bằng một recent-event cụ thể và để participant kể hết sequence trước khi probe; (2) bỏ các ví dụ về behavioral signal khỏi câu hỏi chính để tránh dẫn dắt; (3) thêm câu hỏi kiểm tra false positive và consequence, vì L01 cho thấy learner có thể tự xử lý nhanh bằng AI/Google/bạn bè, còn I01 cho thấy checkpoint chậm đôi khi chỉ do quên tick chứ không phải đang gặp khó. Vì vậy, guide cần phân biệt “có dấu hiệu struggling” với “thực sự cần instructor can thiệp”.

---

# 6. AI Support Log

## AI đã giúp gì?

AI được dùng để:

1. Reverse solution directive thành capability trung tính.
2. Làm rõ change chain từ output → behavior → outcome.
3. Xác định ba actor và phân biệt job/pain của learner, instructor, coach.
4. Tạo hai pain hypotheses cạnh tranh.
5. Xây Evidence Map với cả evidence ủng hộ và evidence bác bỏ.
6. Chuyển hypothesis thành Big 3 và Conversation Guide không pitch solution.
7. Rà soát các câu hỏi dễ leading và thêm scary questions.

## Điểm AI có thể sai hoặc hời hợt

- AI ban đầu có xu hướng giả định các hành vi như “xem lại”, “đổi đáp án”, “highlight” là dấu hiệu struggling. Đây có thể chỉ là cách học chủ động.
- AI không có quyền coi learner “ngại hỏi” hoặc instructor “bỏ sót” là fact nếu chưa có interview evidence.
- AI không thể thay thế consent, recording và sự kiện thực tế từ interviewee.

## Mình đã tự sửa thế nào?

- Giữ toàn bộ nội dung Chặng 1 ở trạng thái **hypothesis**.
- Thêm Pain Hypothesis B để chống confirmation bias.
- Thêm evidence bác bỏ vào từng dòng của Evidence Map.
- Viết scary question để có khả năng chứng minh **detection không phải bottleneck thật**.
- Tách rõ mock/practice khỏi evidence có thể nộp.

---

# 7. Interview Record

Interview Record thật nằm tại:

- `interview/notes.md`
- `interview/recording.m4a` / `.mp3` / `.mp4`, hoặc
- `interview/recording-link.md`
