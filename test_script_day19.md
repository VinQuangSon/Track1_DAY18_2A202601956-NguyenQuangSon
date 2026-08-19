# Kịch Bản Test cho Người Ngoài Nhóm — VLearn 3 Prototype Options

> **Slide Day 19 · Bước 2**: Chuẩn Bị Kịch Bản Test với Người Ngoài Nhóm  
> File demo: [vlearn_3_options_demo.html](file:///e:/Classroom/Code/Codelabs/K4-DAY18-2A202601916-LeDangTan/vlearn_3_options_demo.html)

---

## 📋 Setup trước khi test

- Mở file bằng Chrome hoặc Edge
- Không giải thích giao diện trước cho tester
- Giao nhiệm vụ dưới dạng **kết quả cần đạt**, không phải "bấm vào nút..."

---

## 🔴 Option A — Auto-escalate (AI Tự Báo)

### Câu hỏi Relevant Context
> *"Gần đây bạn có từng học xong 1 bài mà không hiểu không? Bạn làm gì trong lúc đó?"*

Dành tối đa 2 phút bắt đầu. Giúp đánh giá độ tin cậy của feedback.

### Outcome-based Task
> **"Bạn đang là learner trong bài lab Pandas. Hãy tìm hiểu điều gì xảy ra khi bạn bị kẹt ở đây."**

**Nên nói:** *"Hãy dùng công cụ để ôn lại phần chưa hiểu."*  
**Tránh:** *"Bạn bấm vào nút 'Mô phỏng bị kẹt' ở thanh công cụ."*

### 5 Điểm Quan Sát
| # | Quan sát | Ghi chú |
|---|---|---|
| 1 | **First action** — Tester làm gì đầu tiên khi trang load? | Đọc content hay tìm button? |
| 2 | **Hesitation** — Có dừng lại khi banner auto-escalate hiện không? | Ngạc nhiên hay expect? |
| 3 | **Evidence** — Tester có đọc chip signals (12 phút, mở lại slide...) không? | Quan trọng với Option A |
| 4 | **Late Veto** — Tester tìm cách từ chối escalation hay chấp nhận? | Agency của learner |
| 5 | **Trade-off** — Tester nói gì về việc AI báo trước khi hỏi? | Core differentiator |

---

## 🟡 Option B — Confirm Before Escalate (Hỏi Trước)

### Câu hỏi Relevant Context
> *"Gần đây bạn có từng học xong 1 bài mà không hiểu không?"* (dùng lại)

### Outcome-based Task (Instructor role)
> **"Bạn là giảng viên. Có một learner trông như đang bị kẹt. Hãy quyết định xem bạn cần làm gì."**

### 5 Điểm Quan Sát
| # | Quan sát | Ghi chú |
|---|---|---|
| 1 | **First action** — Click vào learner "An" trong bảng hay tìm button khác? | Flow entry point |
| 2 | **Check-in decision** — Tester chọn "Hỏi learner" hay "Theo dõi thêm"? | Human control point |
| 3 | **Learner view** — Mở "Learner view" để xem modal check-in không? | Cross-role perspective |
| 4 | **Cách sửa/kiểm soát** — Sau khi nhận context, tester chọn mức can thiệp nào? | Decision quality |
| 5 | **Option được chọn & Trade-off** — Tester thấy flow này so với A thế nào? | Comparative insight |

---

## 🔵 Option C — AI Assessment + Human Review

### Câu hỏi Relevant Context
> *"Bạn thường để ý signal gì khi một học viên đang gặp khó khăn trong lớp?"*

### Outcome-based Task (Instructor role)
> **"Bạn là giảng viên. Hệ thống đã phân tích xong. Hãy đưa ra quyết định hỗ trợ learner."**

### 5 Điểm Quan Sát
| # | Quan sát | Ghi chú |
|---|---|---|
| 1 | **First action** — Tester click "An" ngay hay đọc Class Progress trước? | Attention flow |
| 2 | **Evidence được đọc hay bỏ qua** — Tester có nhìn vào evidence list không? | Automation bias risk |
| 3 | **Raw evidence** — Có bấm "View raw evidence" không? | Trust in AI signal |
| 4 | **Cách sửa/kiểm soát** — Chọn Support now, Snooze hay Dismiss? Lý do gì? | Decision rationale |
| 5 | **Role switch** — Có thử switch sang Learner view để xem AI không hiện không? | Privacy awareness |

---

## 📝 Mẫu Ghi Feedback Note

```
Tester: ___________  Option tested: A / B / C  Thời gian: ___ phút

1. First action: _________________________________________________
2. Hesitation/Do dự: ____________________________________________
3. Evidence đọc/bỏ qua: ________________________________________
4. Cách sửa sai / Lấy lại kiểm soát: _____________________________
5. Option được chọn & Trade-off nhận xét: _________________________

Câu nói đáng nhớ nhất: "_______________________________________"
```

---

## 3 Câu Cứu Hộ khi Tester Bị Kẹt
1. *"Bạn cứ nói to suy nghĩ nhé"*
2. *"Bạn sẽ làm gì tiếp theo?"*
3. *"Theo bạn, nó nên hoạt động như thế nào?"*

---

> [!TIP]
> Mỗi option test khoảng **5-7 phút**. Ưu tiên observe, hỏi sau. Dùng nút `↻` Reset để reset prototype về trạng thái ban đầu giữa các lần test.
