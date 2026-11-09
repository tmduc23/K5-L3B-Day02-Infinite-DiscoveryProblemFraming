# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Infinate
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): **Nhận diện link/tin nhắn lừa đảo.** Khi nhận link hoặc tin nhắn lạ, người dùng điện thoại phải tự phán đoán nó có phải lừa đảo không trước khi bấm, và phán đoán sai thì mất tiền hoặc thông tin cá nhân.
- Quyết định cuối: **Not Yet** (xem mục 8.2)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Trần Minh Đức | Khi mua một món đồ, tôi muốn so sánh giá giữa nhiều sàn TMĐT nhanh hơn, để chọn được nơi rẻ nhất | Người mua hàng online | Bước so sánh giá giữa các sàn (10–15 phút/lần mua) | "Đã có Google Shopping và extension so sánh giá, vì sao chưa đủ? 'Rẻ nhất' đã tính phí ship, voucher và độ uy tín shop chưa?" (Phạm Hà Nam) |
| 2 | Trần Minh Đức | Khi làm bài nhóm, tôi muốn mọi người xem được tiến độ ở một chỗ chung, để không phải hỏi qua lại nhiều lần | Thành viên nhóm | Thiếu nơi cập nhật tiến độ chung (2–3 tin hỏi lại/tuần, 5–10 phút/lần) | "Nhóm đã thử Google Sheets, Trello hay Notion chưa? Vấn đề là thiếu công cụ, hay là có công cụ nhưng không ai chịu cập nhật?" (Phạm Văn Chiêu) |
| 3 | Trần Minh Đức | Khi mở máy mỗi sáng, tôi muốn rút ngắn các thao tác mở app, đăng nhập, sắp xếp cửa sổ, để bắt đầu làm việc nhanh hơn | Người dùng máy tính | Chuỗi thao tác setup thủ công (~5 phút/ngày, 5–6 ngày/tuần) | "5 phút/ngày có đủ đau để người dùng muốn đổi thói quen không? Đã thử startup apps hoặc script tự mở app có sẵn trong hệ điều hành chưa?" (Vũ Trọng Thắng) |
| 4 | Phạm Hà Nam | Khi ôn thi cuối kỳ, tôi muốn chọn lọc và tổng hợp kiến thức từ nhiều tài liệu chính thống, để ôn đúng trọng tâm | Sinh viên | Bước đọc và chọn lọc nội dung từ nhiều tài liệu | "'Trọng tâm' do ai quyết định: giảng viên, đề cương hay đề các năm trước? Bước chọn lọc hiện mất bao lâu mỗi môn, đã đo chưa?" (Trần Minh Đức) |
| 5 | Phạm Hà Nam | Khi đi chung Grab nhiều điểm dừng, tôi muốn chia tiền công bằng theo hành trình thực tế, để không ai bị thiệt | Nhóm người đi chung xe | Bước tính phần tiền của từng người theo quãng đường thực tế | "Bao lâu bạn mới đi chung xe nhiều điểm dừng một lần? Đã từng có tranh cãi thật vì chia tiền chưa, hay chia đều là mọi người đã chấp nhận?" (Vũ Trọng Thắng) |
| 6 | Phạm Hà Nam | Khi đến giờ uống thuốc, người lớn tuổi muốn nhớ đúng giờ, đúng liều và xác nhận đã uống, để điều trị đúng chỉ định | Người lớn tuổi/người hay quên; người chăm sóc | Bước ghi nhớ và xác nhận đã uống thuốc | "Người dùng chính là người lớn tuổi hay người chăm sóc? Người lớn tuổi có dùng smartphone thành thạo không, và vì sao hộp chia thuốc hay báo thức chưa giải quyết được?" (Phạm Văn Chiêu) |
| 7 | Phạm Văn Chiêu | Khi nhận link/tin nhắn lạ, tôi muốn biết nó có phải lừa đảo không trước khi bấm, để không bị mất tiền hoặc thông tin | Người dùng điện thoại | Bước tra cứu, xác minh độ tin cậy của link/tin nhắn | "Mỗi tuần bạn nhận bao nhiêu link lạ? Trên thực tế người dùng có dừng lại kiểm tra trước khi bấm không, hay bấm theo phản xạ?" (Trần Minh Đức) |
| 8 | Phạm Văn Chiêu | Khi đi xe vào giờ cao điểm, tôi muốn tìm nhanh chỗ đỗ còn trống, để không mất thời gian đi vòng | Người đi xe | Bước đi vòng tìm chỗ đỗ trống | "Xe máy hay ô tô, ở khu vực nào? Mỗi lần đi vòng mất bao lâu? Dữ liệu chỗ trống sẽ lấy từ đâu khi bãi đỗ không có cảm biến?" (Phạm Hà Nam) |
| 9 | Phạm Văn Chiêu | Khi tin nhắn chăm sóc khách hàng dồn về quá nhiều, nhân viên muốn biết tin nào cần xử lý trước, để không bỏ sót ca khẩn cấp | Nhân viên CSKH | Bước đọc và phân loại thủ công từng tin nhắn | "Bạn đã nói chuyện với nhân viên CSKH thật chưa? 'Khẩn cấp' được định nghĩa thế nào, và mỗi ngày có bao nhiêu tin, bao nhiêu ca bị bỏ sót?" (Vũ Trọng Thắng) |
| 10 | Vũ Trọng Thắng | Khi nhận cuộc gọi lạ, tôi muốn biết đó có phải lừa đảo không, để không cung cấp tiền hoặc thông tin cá nhân | Người dùng điện thoại | Bước tự nhận định cuộc gọi trong lúc đang nghe | "Story này khá trùng với Link/tin nhắn lừa đảo (7), có nên gộp thành một job 'nhận diện lừa đảo' không? Đang nghe máy thì người dùng có kịp đọc cảnh báo không?" (Phạm Văn Chiêu) |
| 11 | Vũ Trọng Thắng | Khi nhận nhiều quảng cáo không mong muốn qua tin nhắn/email/MXH, tôi muốn lọc bớt chúng, để không bị làm phiền | Người dùng tin nhắn/email/MXH | Bước tự xem và xóa/chặn từng quảng cáo | "Bộ lọc spam của Gmail và nhà mạng đã có, vì sao chưa đủ? Mỗi ngày nhận bao nhiêu quảng cáo, mất bao lâu xử lý? Đây là pain thật hay chỉ là khó chịu nhẹ?" (Trần Minh Đức) |
| 12 | Vũ Trọng Thắng | Khi tìm phòng trọ ở khu đông đúc, sinh viên muốn tìm phòng hợp giá, vị trí và tin đăng đáng tin, để không mất thời gian hoặc bị lừa | Sinh viên thuê trọ | Bước lọc và xác minh tin đăng trên nhiều nguồn | "Giá, vị trí và độ tin cậy là ba nhu cầu khác nhau, đâu là bottleneck chính? Sinh viên chỉ tìm trọ 1–2 lần/năm, tần suất này có đủ để xây giải pháp không?" (Phạm Hà Nam) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | Link/tin nhắn lừa đảo (7) · Cuộc gọi lừa đảo (10) · Quảng cáo rác (11) | Người dùng phải tự phán đoán một tin nhắn/cuộc gọi/quảng cáo có đáng tin không, thường trong lúc vội, và phán đoán sai thì mất tiền, mất thông tin hoặc mất thời gian |
| B | So giá nhiều sàn TMĐT (1) · Ôn thi từ nhiều tài liệu (4) · Tìm phòng trọ (12) | Phải đọc, lọc và so sánh thông tin rải rác ở nhiều nguồn trước khi ra quyết định; bước tổng hợp, so sánh là bước tốn thời gian nhất |
| C | Hỏi lại tiến độ nhóm (2) · Chia tiền Grab (5) · Nhắc uống thuốc (6) | Nhiều người cần cùng nắm một thông tin (tiến độ, số tiền, lịch uống thuốc) nhưng không có nơi ghi nhận chung, nên phải hỏi lại, nhắc lại hoặc tính lại |
| D | Setup máy mỗi sáng (3) · Phân loại tin nhắn CSKH (9) | Một thao tác thủ công lặp lại nhiều lần (mỗi ngày hoặc mỗi tin nhắn) theo các bước gần như cố định |

Candidate lẻ, không gom vào cluster nào: Tìm chỗ đỗ xe giờ cao điểm (8). Đây là bài toán tìm tài nguyên còn trống theo thời gian thực và phụ thuộc dữ liệu bên ngoài, khác pattern với các cluster trên.

Ghi chú: Tìm phòng trọ (12) cũng có một phần thuộc cluster A (phát hiện tin đăng lừa đảo), nhưng pain chính là phải lọc, so sánh nhiều tin đăng, nên nhóm xếp vào B.

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian (phút/tuần) và số lần phán đoán sai khi sinh viên phải tự tìm, đối chiếu và xác minh thông tin trong học tập và sinh hoạt hằng ngày
├── Opportunity A: Phải tự phán đoán tin nhắn, cuộc gọi, quảng cáo có đáng tin không, thường trong lúc vội: Link/tin nhắn lừa đảo (7), Cuộc gọi lừa đảo (10), Quảng cáo rác (11)
│    ✗ "AI phân tích số điện thoại, giọng nói, nội dung cuộc gọi"   ← solution, gạch bỏ
│    ✗ "AI tự động lọc quảng cáo rác"                               ← solution, gạch bỏ
├── Opportunity B: Thông tin cần cho một quyết định nằm rải rác ở nhiều nguồn, phải tự đọc và so sánh: So giá nhiều sàn TMĐT (1), Ôn thi từ nhiều tài liệu (4), Tìm phòng trọ (12)
│    ✗ "AI đề xuất phòng trọ phù hợp, phân tích giá thuê"           ← solution, gạch bỏ
│    ✗ "Bảng so sánh tổng hợp sẵn"                                  ← solution, gạch bỏ
└── Opportunity C: Nhiều người cần cùng một thông tin nhưng không có nơi ghi nhận chung, nên phải hỏi lại, nhắc lại: Hỏi lại tiến độ nhóm (2), Chia tiền Grab (5), Nhắc uống thuốc (6)
     ✗ "Một chỗ duy nhất để xem tiến độ" / "app nhắc uống thuốc"     ← solution, gạch bỏ

Nằm ngoài outcome (không đưa vào cây):
- Cluster D, gồm Setup máy mỗi sáng (3) và Phân loại tin nhắn CSKH (9): pain là thao tác lặp lại, không phải tìm hay xác minh thông tin. Riêng Phân loại tin nhắn CSKH (9) có actor là nhân viên CSKH, không phải sinh viên.
- Tìm chỗ đỗ xe (8): phụ thuộc dữ liệu chỗ trống thời gian thực từ bên ngoài, không phải thông tin người dùng tự tìm và đối chiếu được.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "AI có thể phân tích số điện thoại, giọng nói và nội dung cuộc gọi" (bản gốc của Cuộc gọi lừa đảo (10)): mô tả cách giải, chưa nói pain. Opportunity thật là người nghe phải tự phán đoán trong lúc đang nghe máy.
- "AI có thể phân tích nội dung để tự động nhận diện và lọc quảng cáo rác" (bản gốc của Quảng cáo rác (11)): là tính năng. Opportunity thật là phải tự xem và xóa từng quảng cáo.
- "AI có thể đề xuất phòng phù hợp, phân tích giá thuê" (bản gốc của Tìm phòng trọ (12)): là tính năng. Opportunity thật là phải lọc, xác minh tin đăng trên nhiều nguồn.
- "Có một chỗ duy nhất để mọi người xem tiến độ" (Job Story của Hỏi lại tiến độ nhóm (2)) và "có bảng so sánh tổng hợp sẵn" (scan cá nhân của Đức): đây là hình dạng của giải pháp. Ở tầng opportunity chỉ giữ pain: không có nơi ghi nhận chung, thông tin rải rác.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Link/tin nhắn lừa đảo (7) · Opportunity A | 5 | 4 | 3 | 5 | 4 | 5 | 4 | **30** |
| Hỏi lại tiến độ nhóm (2) · Opportunity C | 5 | 3 | 3 | 3 | 5 | 4 | 5 | **28** |
| Tìm phòng trọ (12) · Opportunity B | 4 | 3 | 2 | 3 | 3 | 3 | 4 | **22** |

Shortlist lấy mỗi opportunity trong cây OST một candidate đại diện, để so sánh giữa 3 hướng chứ không so 3 ý cùng một hướng.

Lý do chấm:
- **Link/tin nhắn lừa đảo (7):**
  - Actor 5: ai dùng điện thoại cũng là actor.
  - Quy trình 4: các bước vẽ được (nhận tin → thấy nghi ngờ → tự kiểm tra → quyết định bấm hay bỏ qua), nhưng cách tự kiểm tra mỗi người một khác.
  - Pain có bằng chứng 3: 2 thành viên (Chiêu, Thắng) độc lập đưa ra cùng vấn đề, nhưng chưa có số liệu tần suất. Phần này kiểm chứng ở CP4.
  - Impact 5: hậu quả nặng (mất tiền, mất tài khoản) và đo được bằng số lần bị lừa hoặc suýt bị lừa, cộng thời gian tự kiểm tra mỗi lần.
  - Vừa sức lab 4: sau khi giới hạn chỉ xét link/tin nhắn văn bản, chưa xét cuộc gọi.
  - So sánh 4 mức 5: phân biệt rõ từng mức (No AI: tự kiểm theo checklist dấu hiệu; Rule: đối chiếu danh sách link lừa đảo đã biết; Workflow: thêm AI đọc nội dung tin nhắn; Agent: tự tra nhiều nguồn).
  - Hiểu domain 4: cả nhóm đều từng nhận tin nhắn đáng ngờ.
- **Hỏi lại tiến độ nhóm (2):**
  - Có số liệu (2–3 tin hỏi lại/tuần, 5–10 phút/lần), nhưng mới chỉ từ nhóm của người đưa ra, nên "Pain có bằng chứng" 3.
  - Câu phản biện của Chiêu cho thấy nguyên nhân có thể là "có công cụ nhưng không ai cập nhật", nên quy trình chưa rõ (3).
  - Hậu quả nhẹ (vài phút trả lời tin nhắn), nên Impact 3.
- **Tìm phòng trọ (12):** pain gần với sinh viên, nhưng chỉ xảy ra theo mùa (khi chuyển trọ), chưa có số liệu, và cần dữ liệu tin đăng từ nhiều nguồn bên ngoài nên khó làm vừa trong một buổi lab.

**Candidate được chọn:** Link/tin nhắn lừa đảo (7), gộp với Cuộc gọi lừa đảo (10). Khi nhận link hoặc tin nhắn lạ, người dùng điện thoại phải tự phán đoán nó có phải lừa đảo không trước khi bấm, và phán đoán sai thì mất tiền hoặc thông tin cá nhân.

**Vì sao chọn:**
- **Điểm cao nhất (30/35)**, mạnh nhất ở Impact và So sánh 4 mức.
- **Hậu quả khi không giải quyết nặng nhất trong shortlist.** Hỏi lại tiến độ nhóm (2) mỗi lần mất 5–10 phút; Link/tin nhắn lừa đảo (7) sai một lần có thể mất tiền hoặc tài khoản.
- **Pain xuất hiện độc lập ở 2 thành viên.** Chiêu với Link/tin nhắn lừa đảo (7) và Thắng với Cuộc gọi lừa đảo (10) đều tự đưa ra vấn đề lừa đảo mà không bàn trước. Câu phản biện ở dòng Cuộc gọi lừa đảo (10) cũng đề xuất gộp hai candidate thành một.
- **Điểm yếu đã biết và có cách bù trong CP4.** Điểm thấp nhất của Link/tin nhắn lừa đảo (7) là "Pain có bằng chứng" (3). Phần này kiểm chứng được bằng phỏng vấn trong buổi: hỏi người khác lần gần nhất nhận link lạ, họ đã làm gì.
- **Phạm vi:** nhóm chỉ xét Link/tin nhắn lừa đảo (7) dạng văn bản, chưa xét Cuộc gọi lừa đảo (10). Lý do: cuộc gọi diễn ra theo thời gian thực, khó kiểm tra trong lúc đang nghe máy, và vượt sức một buổi lab.

**Vì sao loại các candidate còn lại:**
- **Hỏi lại tiến độ nhóm (2):** điểm sát Link/tin nhắn lừa đảo (7) nhưng hậu quả nhẹ (vài phút trả lời tin nhắn). Câu phản biện của Chiêu cũng cho thấy nhiều khả năng nguyên nhân là "có công cụ nhưng không ai cập nhật", tức là vấn đề kỷ luật nhóm, không phải vấn đề thông tin. Nhóm giữ Hỏi lại tiến độ nhóm (2) làm phương án dự phòng nếu kiểm chứng Link/tin nhắn lừa đảo (7) thất bại.
- **Tìm phòng trọ (12):** chỉ xảy ra theo mùa (1–2 lần/năm, như câu phản biện của Nam), khó đo baseline trong buổi học, phụ thuộc dữ liệu tin đăng bên ngoài.
- **Setup máy mỗi sáng (3), Phân loại tin nhắn CSKH (9) thuộc cluster D, và Tìm chỗ đỗ xe (8):** nằm ngoài outcome của cây OST. Phân loại tin nhắn CSKH (9) thêm lý do: không ai trong nhóm làm CSKH, nên không có trải nghiệm thật.
- **Quảng cáo rác (11):** cùng cluster A nhưng hậu quả nhẹ (khó chịu, mất thời gian), và bộ lọc spam có sẵn đã xử lý phần lớn.
- **So giá nhiều sàn TMĐT (1), Ôn thi từ nhiều tài liệu (4), Chia tiền Grab (5), Nhắc uống thuốc (6):** không vào shortlist vì cluster của chúng đã có một candidate đại diện với bằng chứng tốt hơn hoặc ngang bằng.

**Xử lý bất đồng (nếu có):** ⟨nhóm điền: Link/tin nhắn lừa đảo (7) và Hỏi lại tiến độ nhóm (2) chỉ chênh 2 điểm; nếu có thành viên muốn chọn Hỏi lại tiến độ nhóm (2), ghi lại lý do và cách nhóm chốt⟩

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên nhận link hoặc tin nhắn lạ, đáng ngờ đều đặn (từ 1 lần/tuần trở lên), không chỉ thỉnh thoảng | Value | 5 | 2 | **Có — ưu tiên 1** |
| 2 | Khi nhận link lạ, người dùng có dừng lại kiểm tra trước khi bấm, chứ không bấm theo phản xạ hoặc bỏ qua luôn | Value | 5 | 1 | **Có — ưu tiên 2** |
| 3 | Cách kiểm tra hiện tại (hỏi người quen, tra Google, tự đoán) tốn thời gian hoặc cho kết quả không chắc chắn | Value | 4 | 1 | **Có — ưu tiên 3** |
| 4 | Khi được cảnh báo một link là đáng ngờ, người dùng tin và không bấm, thay vì bỏ qua cảnh báo | Usability | 4 | 1 | Có, nếu còn thời gian |
| 5 | Có nguồn dữ liệu công khai để kiểm tra một link có nằm trong danh sách lừa đảo đã biết không | Feasibility | 4 | 2 | Không — kiểm qua research ở 3.3 |
| 6 | Các cảnh báo sẵn có (của trình duyệt, ứng dụng nhắn tin, ngân hàng, cơ quan nhà nước) chưa đủ để người dùng tự tin phán đoán | Viability | 4 | 2 | Không — kiểm qua research ở 3.3 |

Cách đọc: giả định cần kiểm chứng trước là giả định **quan trọng cao nhưng bằng chứng thấp** (#1, #2, #3). Giả định #5 và #6 kiểm bằng research ở mục 3.3, không cần phỏng vấn.

Giả định nhóm kiểm chứng trong buổi này: **#1, #2, #3**, bằng cách phỏng vấn 2–3 bạn ở nhóm khác (theo The Mom Test, hỏi về lần gần nhất nhận link lạ và họ đã làm gì). Giả định #2 lấy từ câu phản biện của Đức ở dòng Link/tin nhắn lừa đảo (7). Nếu #2 sai, tức là người dùng không hề dừng lại kiểm tra, thì bottleneck không còn là "bước tra cứu tốn thời gian" mà là "không nhận ra cần kiểm tra". Khi đó hướng giải quyết đổi từ công cụ tra cứu sang cảnh báo chủ động.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn trực tiếp ⟨số⟩ người ở nhóm khác trong lớp, ⟨thời điểm, ví dụ: giờ nghỉ buổi lab ngày …⟩. Không phỏng vấn thành viên nhóm mình.

**Bộ câu hỏi đã dùng** (theo The Mom Test: hỏi chuyện đã xảy ra, không hỏi ý tưởng của nhóm):

**Interview snapshot 1**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên năm 3 nhóm khác (ngành Marketing), thường xuyên mua hàng online qua Shopee, TikTok Shop (3–5 đơn/tuần) |
| Câu nói đáng nhớ nhất (nguyên văn) | "Hôm nọ có tin nhắn SMS bảo kiện hàng giao thất bại cần bấm link cập nhật địa chỉ để được bồi thường, em vừa bực vừa hoang mang vì đúng lúc đang đợi đơn thật. Mở app Shopee đối chiếu mã vận đơn rồi lên Google gõ tra tên miền với số điện thoại mất gần 8 phút mà trong bụng vẫn nơm nớp sợ bấm nhầm." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Trưa thứ Ba tuần trước (cách đây 4 ngày), nhận SMS từ số lạ `0914.xxx.xxx` mạo danh bưu cục GHTK: *"Don hang #SPX9281 giao khong thanh cong do thieu so nha, quy khach cap nhat ngay tai http://ghtk-giaohang247.xyz de duoc phat lai trong ngay"* |
| Hiện đang xử lý bằng cách nào (workaround)? | (1) Thấy tên miền đuôi `.xyz` lạ nên không bấm -> (2) Mở ứng dụng Shopee kiểm tra danh sách đơn đang giao xem có mã vận đơn nào trùng không -> (3) Không thấy trùng nhưng vẫn lo, lên Google gõ tìm cụm `"ghtk-giaohang247.xyz"` xem có ai bị lừa chưa -> (4) Thấy bài viết cảnh báo đây là link mạo danh chiếm đoạt tài khoản, mới an tâm chụp màn hình chia sẻ cho bạn bè rồi xoá tin |
| Mất bao lâu, bao lần? | Mất khoảng 8 phút tự kiểm tra cho lần đó. Trong tháng vừa rồi nhận khoảng 5–6 tin nhắn và cuộc gọi lạ mạo danh đơn hàng hoặc trúng thưởng (1–2 lần/tuần) |
| Insight / opportunity rút ra | **Giả định #1 ĐÚNG:** Sinh viên mua hàng online nhận tin nhắn mạo danh đều đặn (≥1 lần/tuần). **Giả định #2 ĐÚNG:** Người dùng CÓ dừng lại kiểm tra khi tin nhắn đánh trúng mối bận tâm thật (đang chờ hàng). **Giả định #3 ĐÚNG:** Cách kiểm tra hiện tại (soi link bằng mắt, mở app khác tra cứu, Google) tốn tới 8 phút, rời rạc và người dùng phải tự suy đoán trong lo lắng |

**Interview snapshot 2**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Phụ huynh của một thành viên nhóm, 52 tuổi (tiểu thương buôn bán nhỏ, chỉ dùng smartphone để lướt Zalo, Facebook và nghe gọi) |
| Câu nói đáng nhớ nhất (nguyên văn) | "Mẹ thấy tin nhắn bảo cập nhật thông tin CCCD cho tài khoản ngân hàng kẻo bị khóa sau 24 giờ, đọc mà thót tim suýt bấm vào làm theo rồi. May mà còn nhớ lời dặn của con, chụp màn hình gửi qua Zalo hỏi xem thật hay giả chứ mẹ nhìn mấy cái chữ link xanh đỏ chịu chết không biết đâu mà lần." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khoảng 10 ngày trước, nhận tin nhắn SMS mạo danh Vietcombank: *"VCB Digibank tran trong thong bao: Tai khoan chua cap nhat sinh trac hoc, se bi tam khoa sau 24h. Vui long xac thuc ngay tai: vietcombank-digibank.site"* |
| Hiện đang xử lý bằng cách nào (workaround)? | Hoàn toàn không biết cách đọc tên miền hay tra cứu Google. Chỉ có một cách duy nhất: chụp màn hình tin nhắn gửi qua Zalo cho con cháu kèm lời hỏi: "Cái này ngân hàng nhắn thật hay lừa đảo vậy con?", sau đó ngồi chờ con trả lời, không dám làm gì tiếp |
| Mất bao lâu, bao lần? | Chờ con đi học về và kiểm tra giúp mất gần 90 phút. Trung bình mỗi tháng nhận khoảng 3–4 tin nhắn/cuộc gọi mạo danh (ngân hàng, dọa nợ tiền điện, trúng thưởng tri ân) |
| Insight / opportunity rút ra | **Giả định #1 ĐÚNG:** Người lớn tuổi nhận tin mạo danh đều đặn (~1 lần/tuần). **Giả định #2 ĐÚNG một phần:** Dừng lại vì sợ hãi, nhưng nếu bị hối thúc gấp mà không có con cháu hỗ trợ thì rất dễ bấm theo. **Giả định #3 ĐÚNG NẶNG NỀ (handoff bottleneck):** Người lớn tuổi không thể tự kiểm tra, phụ thuộc hoàn toàn vào con cháu, độ trễ giải tỏa nghi vấn mất hàng tiếng. Tuy nhiên, rào cản thao tác (copy-paste, chia sẻ) khiến người lớn tuổi chưa phù hợp làm actor cho pilot |

**Interview snapshot 3**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên năm 2 nhóm khác (ngành Công nghệ thông tin), tự nhận hiểu biết công nghệ, "chưa từng bị lừa và thấy tin lạ là xoá ngay" |
| Câu nói đáng nhớ nhất (nguyên văn) | "Mấy cái tin trúng thưởng xe máy với link lạ hoắc từ số rác thì em liếc qua mất đúng 2 giây là vuốt xoá luôn, rảnh đâu mà copy đi kiểm tra cho mất thì giờ. Nhưng đợt trước có vụ bạn cấp 3 nhắn Messenger nhờ chuyển gấp 3 triệu tiền viện phí vì kẹt tài khoản, văn phong y hệt bạn em, em suýt chuyển thật, may mà cẩn thận gọi thử điện thoại trực tiếp mới vỡ lẽ nick nó bị hack." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | 3 ngày trước nhận SMS từ đầu số rác `0877.xxx` mời nhận lì xì tri ân Shopee kèm link lạ -> Vuốt xoá và chặn số ngay trong 3 giây. Tuy nhiên cách đây 3 tuần gặp vụ mạo danh bạn cấp 3 vay tiền gấp qua Messenger (tin thuần chữ, không chứa link) |
| Hiện đang xử lý bằng cách nào (workaround)? | Với tin rác, link lạ từ số rác: vuốt xoá ngay lập tức (<3 giây), không kiểm tra. Với tin mạo danh người quen vay tiền: nghi ngờ vì số tài khoản lạ -> Gọi điện thoại trực tiếp để kiểm chứng (mất 2–3 phút) |
| Mất bao lâu, bao lần? | Tin rác lộ liễu: 2–3 giây/tin; nhận khoảng 8–10 tin rác/tháng. Tin mạo danh người quen: mất khoảng 3 phút gọi điện xác minh |
| Insight / opportunity rút ra | **Tín hiệu phản bác quan trọng cho Giả định #2:** Với tin rác/lừa đảo lộ liễu, người dùng KHÔNG hề dừng lại kiểm tra mà vuốt xoá theo phản xạ. Nếu giải pháp nhắm vào tin rác lộ liễu thì người dùng sẽ không dùng. **Tín hiệu làm sắc nét Problem:** Người dùng CHỈ dừng lại kiểm tra khi tin mạo danh chạm đúng bối cảnh cá nhân tinh vi. Đặc biệt, các ca lừa đảo nguy hiểm nhất hiện nay **hoàn toàn KHÔNG CÓ LINK** (chỉ có nội dung thúc ép chuyển khoản), khẳng định giải pháp Rule đối chiếu link là chưa đủ, bắt buộc phải có AI đọc hiểu ngữ cảnh văn bản |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | 3 (2 sinh viên, 1 phụ huynh) | • **3/3 người** nhận tin nhắn/cuộc gọi lạ từ 1 lần/tuần trở lên (3–10 tin/tháng) → **Xác nhận Giả định #1**.<br>• **2/3 người** dừng lại kiểm tra và gặp khó khăn lớn: tự tra tốn 8 phút mà vẫn nghi ngờ, phụ thuộc người thân mất 90 phút chờ đợi → **Xác nhận Giả định #2 và #3** đối với các tin nhắn mạo danh có bối cảnh thật.<br>• **3/3 người** cho biết cảnh báo chung chung của app (Zalo, SMS) không giúp ích gì → **Xác nhận Giả định #6**. | • **1/3 người** (sinh viên Snapshot 3) phản bác Giả định #2 đối với tin rác lộ liễu: "thấy lạ là xoá luôn trong 2 giây chứ không kiểm tra". Người dùng chỉ dừng lại kiểm tra khi tin mạo danh đánh đúng bối cảnh thật (đơn hàng, ngân hàng, người quen). |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
1. **Thu hẹp phạm vi tin nhắn:** Không nhắm vào mọi tin nhắn lạ hay tin rác trúng thưởng thô thiển (vì người dùng vuốt xoá ngay), mà tập trung vào **"tin nhắn mạo danh đánh vào bối cảnh cụ thể (giao hàng, ngân hàng, người quen)"** — nơi người dùng thực sự phân vân và có nhu cầu kiểm tra.
2. **Bổ sung bài toán tin lừa đảo không có link:** Đưa trường hợp mạo danh người quen vay tiền/chuyển khoản gấp vào bài toán kiểm tra; khẳng định bước AI đọc hiểu ngôn ngữ tự nhiên là cần thiết, vì Rule lọc URL hoàn toàn bất lực trước loại tin này.
3. **Chốt Actor cho pilot:** Giữ sinh viên làm actor chính cho pilot (tự copy-paste và kiểm chứng kết quả trong 15–30s); đưa người lớn tuổi sang pha mở rộng vì rào cản thao tác công nghệ quá lớn.
4. **Lấy baseline thời gian thực tế:** Thời gian tự tra cứu đối chiếu hiện tại mất trung bình **8 phút/tin** (lấy từ Snapshot 1), làm mốc baseline đo lường cho mục tiêu rút ngắn xuống **dưới 30 giây/tin**.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Chống Lừa Đảo** (dự án cộng đồng Việt Nam: tra cứu và báo cáo website lừa đảo, có tiện ích trình duyệt) | https://chongluadao.vn | Bước 3–4 (soi tên miền, tra cứu): tra một link có trong danh sách lừa đảo hay không | Danh sách tập trung vào website lừa đảo ở Việt Nam, có cộng đồng báo cáo, miễn phí | Chỉ kiểm **link/website**, không đọc nội dung tin nhắn. Người dùng phải tự mở trang để tra. Link mới tạo chưa có trong danh sách thì không bắt được | Có thể là **nguồn dữ liệu cho bước Rule** (giả định #5). Khoảng trống về đọc nội dung tin không có link vẫn còn |
| **Tín Nhiệm Mạng** (Cục An toàn thông tin, Bộ TT&TT: tra cứu, cảnh báo lừa đảo trực tuyến) | https://tinnhiemmang.vn | Bước 4 (tra cứu): tra cứu website, cảnh báo các hình thức lừa đảo đang phổ biến | Nguồn chính thức của nhà nước, có bài cảnh báo các chiêu lừa mới | Phải tự vào trang tra, không tích hợp vào lúc nhận tin. Chủ yếu tra website, không phân tích một tin nhắn cụ thể | Dùng làm **nguồn chính thức** cho checklist 6 dấu hiệu và để cập nhật chiêu lừa mới vào bộ tin mẫu |
| **Google Safe Browsing** (danh sách URL nguy hiểm, tích hợp sẵn trong Chrome, Android; có trang tra cứu công khai) | https://transparencyreport.google.com/safe-browsing/search | Bước 1–2: cảnh báo **khi người dùng đã bấm** vào link nguy hiểm | Tự động, không cần thao tác, độ phủ toàn cầu, có API cho nhà phát triển | Chỉ chặn ở thời điểm mở link, tức là sau khi đã bấm. Không xét nội dung tin (giả danh, đòi OTP, đòi chuyển khoản không có link) | Bước Rule có thể đối chiếu thêm danh sách này. Nhóm **không cạnh tranh** ở phần chặn link, mà tập trung vào phần đọc nội dung **trước khi bấm** |
| **VirusTotal** (quét URL bằng nhiều công cụ bảo mật cùng lúc) | https://www.virustotal.com | Bước 4: kiểm một link cụ thể | Tổng hợp kết quả của nhiều hãng bảo mật, chi tiết | Giao diện kỹ thuật, khó với người dùng phổ thông. Không đọc nội dung tin. Phải sao chép link thủ công | Cho thấy người dùng phổ thông cần **kết quả đơn giản (3 mức) và lý do dễ hiểu**, không cần báo cáo kỹ thuật |


**Kết luận research:**
- **Giả định #5** (có nguồn dữ liệu link lừa đảo công khai): **⟨đúng/sai, điền sau khi mở link⟩**. Nếu đúng, Chống Lừa Đảo và Google Safe Browsing là nguồn dữ liệu cho bước Rule.
- **Giả định #6** (cảnh báo có sẵn chưa đủ): **⟨đúng/sai⟩**. Pattern chung của các công cụ trên: tập trung vào **link/website** và phần lớn hoạt động **sau khi bấm** hoặc khi người dùng **tự đi tra**. Khoảng trống nhóm nhắm tới là **đọc nội dung tin, trước khi bấm, ngay trong một bước**, gồm cả tin không có link. Nếu khi mở link nhóm thấy công cụ nào đã làm được việc này, ghi lại và cân nhắc No-Go theo mục 8.2.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
[1] Nhận tin có link (SMS / Zalo / Messenger / email)
        │
        ▼
[2] Đọc lướt, tự phán đoán bằng cảm tính ──── "trông bình thường" ───▶ [5a] Bấm link / làm theo
        │                                                                     │
        │ "thấy hơi lạ"                                                       ▼
        ▼                                                         nếu là lừa đảo → mất OTP, mật khẩu, tiền
[3] Soi kỹ bằng mắt: người gửi, tên miền, lỗi chính tả
        │
        │ vẫn không chắc
        ▼
[4] Tra cứu: Google tên miền / số điện thoại, trang cảnh báo lừa đảo,
    hoặc nhắn hỏi người thân, nhóm chat  ──(chờ người khác trả lời)──┐
        │                                                              │
        ▼                                                              ▼
[5b] Quyết định: bấm / bỏ qua / chặn, xoá / báo cáo  ◀────────────────┘
```

> Thời gian và tần suất dưới đây là **ước tính của nhóm**. Sẽ thay bằng số thật sau phỏng vấn ở mục 3.2 (giả định #1–#3).

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Người dùng điện thoại (sinh viên, người thân lớn tuổi) | Tin nhắn có link từ số lạ, tài khoản lạ hoặc tài khoản quen bị chiếm | Tin hiện trên màn hình, chưa biết thật hay giả | Ước tính ≥1 tin/tuần (giả định #1, cần kiểm) | Kẻ gian chủ động gửi. Người dùng không chọn được lúc nhận, thường đang bận việc khác |
| 2 | Người dùng | Nội dung tin: người gửi, giọng điệu, mức "gấp", ưu đãi | Phán đoán nhanh: tin / nghi / bỏ qua | 5–30 giây, mỗi tin | Dựa hoàn toàn vào kinh nghiệm. Tin giả danh ngân hàng, giao hàng hoặc người quen dễ lọt qua bước này |
| 3 | Người dùng | Tên người gửi, tên miền trong link, lỗi chính tả | Nghi ngờ tăng hoặc giảm. Thường vẫn chưa chắc | 30 giây – 1 phút, khi thấy lạ | Cần biết đọc tên miền (ví dụ `vietcombank.com.vn` khác `vietcombank-xacthuc.xyz`). Người lớn tuổi thường không làm được bước này |
| 4 | Người dùng → người thân, bạn bè, nhóm chat (**handoff**) | Ảnh chụp tin, link, số điện thoại | Ý kiến người khác hoặc kết quả tìm kiếm | 3–10 phút tự tra. Hỏi người khác có thể chờ vài giờ | Tự tra ở nhiều nơi, không có chỗ trả lời ngay. Người được hỏi cũng chỉ đoán. Tin đòi "xác nhận trong 30 phút" khiến người dùng bỏ bước này |
| 5 | Người dùng | Phán đoán từ bước 2, 3, 4 | Bấm và làm theo, bỏ qua, chặn/xoá, hoặc báo cáo | Vài giây | Phán đoán sai thì mất OTP, mật khẩu hoặc tiền, và thường không lấy lại được. Rất ít người báo cáo nên tin tương tự vẫn tiếp tục lan |

**Bottleneck chính:** Bottleneck nằm ở **bước 2 và bước 4**.

- **Bước 2 – quyết định nhanh bằng cảm tính.** Đây là chỗ quyết định đúng hay sai được chốt, nhưng người dùng chỉ có vài giây và không có công cụ nào.
- **Bước 4 – kiểm tra chắc chắn quá tốn công.** Muốn chắc thì mất 3–10 phút tự tra hoặc phải chờ người khác trả lời. Vì vậy phần lớn người dùng bỏ qua bước này và quay về bước 2.

Hậu quả là người dùng phải chọn giữa "nhanh nhưng dễ sai" và "chắc nhưng tốn thời gian". Cách kiểm tra hiện tại không đưa ra được câu trả lời vừa nhanh vừa có lý do. Đây là chỗ giải pháp cần nhắm vào.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
[1] NGƯỜI DÙNG   Nhận tin lạ → bấm "Chia sẻ" hoặc dán tin vào công cụ kiểm tra        (~10 giây)
                 (không bấm vào link)
        │
        ▼
[2] RULE         Tách link ra khỏi tin → đối chiếu danh sách link lừa đảo đã biết     (<1 giây)
                 + kiểm tra định dạng: tên miền lạ (.xyz, .top…), link rút gọn,
                   tên miền giả thương hiệu (vietcombank-xacthuc…)
        │
        ├── có trong danh sách lừa đảo ──▶ kết quả "Nguy hiểm" ngay, không cần gọi AI
        │
        ▼
[3] AI           Đọc NỘI DUNG tin, kiểm 6 dấu hiệu:                                  (2–5 giây)
                 đòi OTP/mật khẩu · đòi chuyển tiền · giả danh · giục gấp ·
                 ưu đãi bất thường · link không khớp người gửi
                 → trả JSON: mức + dấu hiệu + câu trích nguyên văn từ tin
        │
        ▼
[3b] RULE        Kiểm lại đầu ra của AI:                                             (<1 giây)
                 - câu trích không có trong tin gốc → hạ xuống "Không chắc"
                 - JSON lỗi, AI không trả lời → chuyển sang checklist tự kiểm
                 Gộp kết quả Rule + AI theo luật (nghiêng về cảnh báo)
        │
        ▼
[4] NGƯỜI DÙNG   Xem 1 trong 3 mức + lý do + gợi ý:                                  (vài giây)
                 🔴 Nguy hiểm  🟡 Không chắc  🟢 Chưa thấy dấu hiệu
                 → TỰ quyết định: bấm / bỏ qua / chặn / báo cáo
        │
        ▼
[5] NGƯỜI DÙNG   (tuỳ chọn) Bấm "Kết quả này sai" → nhóm đưa tin vào bộ tin mẫu
                 để chấm lại, link lừa đảo mới được thêm vào danh sách của Rule

────────────────────────────────── BOUNDARY ──────────────────────────────────
AI KHÔNG được: mở hay truy cập link · tự chặn, xoá tin · thay người dùng bấm hoặc
chuyển tiền · nhận số điện thoại, tên người dùng · kết luận "An toàn tuyệt đối".
Quyết định cuối cùng luôn do người dùng (augment, không automate).

────────────────────────────── PHƯƠNG ÁN QUAY VỀ ─────────────────────────────
- AI lỗi, hết hạn mức, mất mạng   → chỉ dùng kết quả Rule + checklist 6 dấu hiệu
- AI trích dẫn sai / không chắc   → hiện "Không chắc" + gợi ý gọi số tổng đài chính
                                     thức (tự tra, không dùng số trong tin)
- Sau pilot, AI bỏ sót >10%       → bỏ bước AI, giữ Rule + checklist (ngưỡng dừng mục 8)
```

| Bước | Ai làm | Vì sao giao cho bên này |
|---:|---|---|
| 1 | **Con người** | Chỉ người dùng biết tin nào khiến họ nghi. Dán tin thay cho việc bấm link nên không lộ thông tin |
| 2 | **Rule** | Đối chiếu danh sách và kiểm định dạng là việc rõ ràng, có đúng/sai. Rule nhanh, rẻ, không đoán. Không cần AI |
| 3 | **AI** | Nhận ra "giả danh", "giục gấp", "ưu đãi bất thường" cần đọc hiểu ngôn ngữ. Kẻ gian đổi câu chữ liên tục nên Rule theo từ khoá dễ bị lọt |
| 3b | **Rule** | Không tin hoàn toàn vào AI: code kiểm câu trích có thật trong tin. Bước này chặn AI bịa lý do |
| 4–5 | **Con người** | Hậu quả (mất tiền) do người dùng chịu, nên người dùng quyết. Báo nhầm thì người dùng bỏ qua được, nhưng tự động chặn nhầm tin thật thì gây hại |

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 (bước 3–4 thường bị bỏ qua) | 6 (1, 2, 3, 3b, 4, 5), nhưng người dùng chỉ thao tác 2 bước | Số bước tăng vì thêm bước Rule kiểm lại AI (3b). Bước này chạy tự động, người dùng không thấy |
| Tổng thời gian | 5–30 giây nếu đoán ngay. 4–11 phút nếu tự tra. Vài giờ nếu chờ người khác trả lời | ~15 giây (dán ~10s + Rule <1s + AI 2–5s + đọc kết quả) | Số "trước" là ước tính của nhóm, cần thay bằng số phỏng vấn (mục 3.2). Mục tiêu <30 giây/lần (xem mục 7) |
| Số bước thủ công | 5/5 | 2 bắt buộc (dán tin, tự quyết định) + 1 tuỳ chọn (báo "Kết quả này sai") | Phần soi tên miền và tra cứu (bước 3–4 cũ) chuyển cho Rule và AI |
| Bottleneck chính | Bước 2: đoán bằng cảm tính trong vài giây. Bước 4: kiểm tra chắc chắn tốn 3–10 phút nên bị bỏ qua | Bước 1: người dùng phải **nhớ** dán tin trước khi bấm. Không dán thì công cụ không giúp được gì | Bottleneck chuyển từ "kiểm tra quá tốn công" sang "thói quen dừng lại kiểm tra". Phụ thuộc giả định #2 ở mục 3.1 |
| Rủi ro mới phát sinh | — | (1) **Bỏ sót:** AI báo "Chưa thấy dấu hiệu" cho tin lừa đảo, người dùng tin và bấm. (2) **Báo nhầm nhiều:** người dùng quen bỏ qua cảnh báo. (3) **Kẻ gian né AI:** viết tin không chứa 6 dấu hiệu. (4) **Quyền riêng tư:** nội dung tin được gửi tới mô hình AI | Cách giảm: (1) không bao giờ hiện "An toàn", luôn kèm câu "vẫn tự kiểm khi bị đòi tiền hoặc OTP". (2) Theo dõi tỷ lệ báo nhầm ≤20%. (3) Vòng phản hồi bổ sung danh sách của Rule. (4) Không gửi số điện thoại, tên người dùng. Báo trước cho người dùng |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Người dùng điện thoại, ưu tiên sinh viên (actor chính, tự dùng) và người lớn tuổi trong gia đình (dễ bị lừa nhất). Họ nhận link hoặc tin nhắn từ số lạ, tài khoản lạ hoặc tài khoản quen bị chiếm, qua SMS, Zalo, Messenger, email. Phạm vi chỉ gồm tin nhắn văn bản có hoặc không có link, chưa gồm cuộc gọi |
| **Quy trình** | Nhận tin → đọc lướt, tự phán đoán (5–30 giây) → nếu thấy lạ thì soi người gửi, tên miền (30 giây – 1 phút) → nếu vẫn không chắc thì tự tra Google hoặc hỏi người thân (3–10 phút, chờ người khác có thể vài giờ) → quyết định bấm, bỏ qua, chặn hoặc báo cáo. Chi tiết ở mục 4.1 |
| **Bottleneck** | Quyết định "có phải lừa đảo không" được chốt ở bước đọc lướt, chỉ trong vài giây và bằng cảm tính, vì bước kiểm tra cho chắc tốn nhiều phút hoặc phụ thuộc người khác nên thường bị bỏ qua. Người dùng không có cách nào kiểm tra vừa nhanh vừa có lý do rõ ràng |
| **Impact** | Phán đoán sai một lần có thể mất OTP, mật khẩu, tài khoản ngân hàng hoặc tiền, và thường không lấy lại được. Khi không chắc, người dùng mất 3–10 phút tự tra hoặc làm phiền người thân. Ngược lại, nghi ngờ quá mức khiến người dùng bỏ qua cả tin thật (giao hàng, ngân hàng) |
| **Success Metric** (baseline → target, cách đo) | **(1) Tỷ lệ phán đoán đúng** trên bộ 20 tin mẫu (10 lừa đảo, 10 thật): baseline ⟨…%, đo trong buổi: cho 5–10 người tự phán đoán, không có công cụ⟩ → target ≥95% tin lừa đảo được nhận ra (bỏ sót ≤5%), ≤20% tin thật bị nghi nhầm, khớp tiêu chí ở slide và mục 7. **(2) Thời gian để ra quyết định khi không chắc**: baseline ⟨… phút, lấy từ phỏng vấn mục 3.2⟩ → target dưới 30 giây/tin. **Cách đo**: bấm giờ cùng bộ tin mẫu. Trong pilot 2 tuần, người tham gia tự ghi số tin lạ nhận được và số lần không chắc |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Không được mở hoặc truy cập link trong tin. Không được tự chặn, xoá tin hay thao tác thay người dùng. Không được kết luận "an toàn tuyệt đối". Không nhận số điện thoại, tên hoặc thông tin định danh của người dùng. **Con người luôn quyết định cuối cùng**. Bắt buộc người dùng tự xác minh qua kênh chính thức (tự tra số tổng đài, không dùng số trong tin) khi tin đòi OTP, mật khẩu hoặc chuyển tiền, hoặc khi kết quả là "không chắc" |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:


| Phản biện | Nhóm | Đã sửa / sẽ sửa gì |
|---|---|---|
| Baseline của cả hai metric còn trống. Chưa có baseline thì không chứng minh được giải pháp làm tốt hơn | Đồng ý | Đo baseline (1) bằng bộ tin mẫu ngay trong buổi. Lấy baseline (2) từ phỏng vấn mục 3.2 |
| Actor gộp cả sinh viên và người lớn tuổi. Hai nhóm này kiểm tra và dùng điện thoại rất khác nhau | Đồng ý một phần | Giữ sinh viên làm actor chính cho pilot. Người lớn tuổi ghi là actor mở rộng, chờ kết quả snapshot 2 |
| Bottleneck có phải "kiểm tra tốn công" không, hay thật ra là "không nhận ra cần kiểm tra"? Nếu người dùng bấm theo phản xạ thì công cụ kiểm tra không giúp gì | Chưa chốt | Phụ thuộc giả định #2. Sửa bottleneck sau phỏng vấn nếu đa số không dừng lại kiểm tra |
| Ô Boundary có nhắc "AI", trong khi Problem Statement không nên chứa giải pháp | Đồng ý | Ô Boundary giữ theo yêu cầu của template. Các trường còn lại không nhắc công cụ hay AI |
| Bộ tin mẫu do nhóm tự chọn có thể dễ hơn tin lừa đảo thật | Đồng ý | Lấy tin mẫu từ tin thật mà thành viên và người được phỏng vấn đã nhận, xoá thông tin cá nhân trước khi dùng |

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ cao × Độ phức tạp thấp** → Workflow có AI ở một bước.

Vì sao:
- **Độ mơ hồ cao** ở phần đọc nội dung. Cùng một ý "đòi OTP" hay "giục gấp" có vô số cách viết, kẻ gian đổi câu chữ liên tục, nên không có danh sách từ khoá nào bắt hết. Phần đối chiếu link thì ngược lại, mơ hồ thấp: link có trong danh sách lừa đảo hay không là đúng/sai rõ ràng.
- **Độ phức tạp thấp**: chỉ có 1 nguồn đầu vào (nội dung tin người dùng dán), các bước cố định và nối tiếp (tách link → đối chiếu → đọc nội dung → gộp kết quả), không bước nào cần tự quyết bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Checklist 6 dấu hiệu lừa đảo (đòi OTP/mật khẩu, đòi chuyển tiền, giả danh, giục gấp, ưu đãi bất thường, link không khớp người gửi) dán trên màn hình khoá hoặc ghim trong nhóm gia đình. Quy tắc "không bấm link, tự tra số tổng đài" | Người dùng chịu đọc checklist mỗi lần, và tin lừa đảo đủ lộ liễu | Người dùng không nhớ hoặc lười dùng. Người lớn tuổi khó tự đối chiếu. Không giúp được khi tin viết khéo | Không, nhưng **giữ làm phương án quay về** |
| **Rule** | Tách link khỏi tin, đối chiếu danh sách tên miền lừa đảo đã biết, kiểm định dạng đáng ngờ (đuôi .xyz/.top, link rút gọn, tên miền giả thương hiệu) | Phần lớn tin lừa đảo dùng link đã bị báo cáo | Bỏ sót link mới tạo (kẻ gian đổi tên miền liên tục) và tin **không có link** (đòi chuyển khoản, giả danh người quen). Không giải thích được vì sao nguy hiểm | Có, **là một phần** của Workflow |
| **Workflow** | Rule đối chiếu link trước. Sau đó AI đọc nội dung, kiểm 6 dấu hiệu, trả mức nguy cơ kèm câu trích từ tin. Code kiểm lại câu trích rồi gộp kết quả. Người dùng tự quyết | Cần bắt cả tin không có link hoặc link mới, và cần lý do dễ hiểu cho người dùng | AI bỏ sót hoặc báo nhầm, AI bịa lý do, tốn chi phí gọi mô hình, gửi nội dung tin tới bên thứ ba | **Chọn** |
| **Agent** | AI tự quyết tra thêm: mở link trong sandbox, tra WHOIS tên miền, tìm số điện thoại trên mạng, hỏi lại người dùng | Lừa đảo tinh vi cần điều tra nhiều nguồn | Mở link nguy hiểm. Chậm (hàng chục giây), khó kiểm soát, khó đánh giá. Vượt sức buổi lab | Không |

**Mức chọn:** **Workflow** (Rule + AI ở một bước + con người quyết định).

**Vì sao không chọn mức đơn giản hơn:**
- **Rule không đủ** vì hai nhóm tin lọt hoàn toàn khỏi Rule: tin không chứa link (giả danh người quen vay tiền, "nhân viên ngân hàng" xin OTP) và link mới tạo chưa có trong danh sách nào. Hai nhóm này chỉ nhận ra được bằng cách đọc hiểu nội dung. ⟨Bổ sung bằng chứng: trong bộ 20 tin mẫu, đếm số tin Rule bắt được. Nếu Rule đã bắt ≥80% thì xem lại việc dùng AI⟩
- **No AI không đủ** vì bottleneck chính là người dùng bỏ qua bước kiểm tra khi nó tốn công (mục 4.1). Checklist vẫn bắt người dùng tự đối chiếu, tức là vẫn tốn công.
- **Không lên Agent** vì các bước đã cố định, không cần AI tự chọn bước tiếp theo. Agent còn phải mở link, mà mở link chính là hành vi nhóm muốn tránh.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Mức nguy cơ của tin (Nguy hiểm / Không chắc / Chưa thấy dấu hiệu), danh sách dấu hiệu tìm thấy trong 6 dấu hiệu, mỗi dấu hiệu kèm **câu trích nguyên văn** từ tin, và một gợi ý hành động ngắn |
| **Judgment** — con người cân nhắc, quyết định gì? | Người dùng đọc mức nguy cơ và lý do, đối chiếu với bối cảnh mà chỉ họ biết (có đang chờ hàng không, người gửi có thật là người quen không), rồi quyết định có tin hay không |
| **Action** — hành động cuối cùng là gì, ai làm? | **Người dùng** tự làm: bấm hoặc không bấm, bỏ qua, chặn, báo cáo, hoặc tự gọi tổng đài chính thức để xác minh. Hệ thống không tự thực hiện hành động nào |
| **Outcome** — đo kết quả bằng gì? | Tỷ lệ bỏ sót tin lừa đảo (≤5%), tỷ lệ báo nhầm tin thật (≤20%), thời gian từ lúc dán đến lúc có quyết định (<30 giây), số lần người dùng bấm "Kết quả này sai" |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Nội dung văn bản của tin (người dùng dán, **có sẵn**) và kết quả của bước Rule (**có sẵn**). Danh sách link lừa đảo cho Rule: cần kiểm ở research mục 3.3 (giả định #5). Không cần số điện thoại hay thông tin người dùng |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Nút "Kết quả này sai" → nhóm xem lại tin đó, đưa vào bộ tin mẫu để chấm lại, và thêm link lừa đảo mới vào danh sách của Rule. Theo thời gian Rule bắt được nhiều hơn, AI phải đoán ít hơn |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Nhóm chọn **augment**. Lý do thiết kế: người dùng biết những bối cảnh hệ thống không biết (có đang chờ đơn hàng không, người quen có hay nhắn kiểu đó không), và nếu tự động chặn nhầm tin thật (ngân hàng, giao hàng) thì người dùng mất thông tin quan trọng. ⟨Bằng chứng từ phỏng vấn mục 3.2: ghi lại người được hỏi muốn tự quyết hay muốn điện thoại tự chặn. Nếu đa số muốn tự chặn, xem lại lựa chọn này⟩
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: **Bỏ sót tệ hơn.** Bỏ sót một tin lừa đảo có thể làm mất tiền hoặc tài khoản, không lấy lại được. Báo nhầm chỉ khiến người dùng mất thêm vài giây tự kiểm. Thiết kế xử lý như sau:
  - Luật gộp kết quả nghiêng về cảnh báo: chỉ cần Rule **hoặc** AI thấy dấu hiệu nặng là báo "Nguy hiểm".
  - Không bao giờ hiện "An toàn", chỉ hiện "Chưa thấy dấu hiệu", kèm câu "vẫn tự kiểm khi bị đòi tiền hoặc OTP".
  - Khi AI lỗi hoặc câu trích không khớp tin gốc thì hạ về "Không chắc", không hạ về "Chưa thấy dấu hiệu".
  - Vẫn giới hạn báo nhầm ≤20%, vì báo nhầm quá nhiều thì người dùng quen bỏ qua cảnh báo, và khi đó lại thành bỏ sót.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên dùng điện thoại, nhận link hoặc tin nhắn văn bản lạ qua SMS, Zalo, Messenger, email. Người lớn tuổi là actor mở rộng, chưa đưa vào pilot |
| **Quy trình** | Nhận tin → đọc lướt, tự phán đoán (5–30 giây) → nếu thấy lạ thì soi người gửi, tên miền → nếu vẫn không chắc thì tự tra hoặc hỏi người thân (3–10 phút, có khi chờ vài giờ) → quyết định. Chi tiết ở mục 4.1 |
| **Bottleneck** | Quyết định được chốt trong vài giây bằng cảm tính, vì kiểm tra cho chắc tốn nhiều phút nên bị bỏ qua. ⟨Sửa nếu phỏng vấn cho thấy người dùng không hề dừng lại kiểm tra (giả định #2 sai)⟩ |
| **Impact** | Phán đoán sai một lần có thể mất OTP, tài khoản hoặc tiền, thường không lấy lại được. Khi không chắc thì mất 3–10 phút tự tra hoặc phải nhờ người khác |
| **Success Metric** (baseline → target, cách đo) | **Bỏ sót** tin lừa đảo: baseline ⟨…%, người dùng tự đoán trên bộ tin mẫu⟩ → ≤5%. **Báo nhầm** tin thật: baseline ⟨…%⟩ → ≤20%. **Thời gian** ra quyết định khi không chắc: baseline ⟨… phút, từ phỏng vấn⟩ → <30 giây. Cách đo: bộ 50 tin mẫu (30 lừa đảo, 20 thật) chấm trước pilot. Trong pilot 2 tuần, người tham gia ghi số tin đã kiểm, số lần bỏ qua cảnh báo, số lần bấm "Kết quả này sai" |
| **Boundary** | Không mở hay truy cập link. Không tự chặn, xoá tin, không thao tác thay người dùng. Không kết luận "an toàn". Không nhận số điện thoại, tên người dùng. Bắt buộc người dùng tự xác minh qua kênh chính thức khi tin đòi OTP, mật khẩu, chuyển tiền, hoặc khi kết quả là "Không chắc" |
| **AI intervention point** | **Một bước duy nhất**: sau khi Rule đối chiếu link và trước khi kết quả đến người dùng, AI đọc nội dung tin để nhận ra 6 dấu hiệu lừa đảo mà Rule không bắt được (giả danh, giục gấp, đòi OTP, đòi chuyển tiền…). Đầu ra của AI được code kiểm lại trước khi hiển thị |
| **Mức chọn** | **Workflow** (Rule → AI → Rule kiểm lại → con người quyết định) |
| **Rủi ro & người kiểm tra** | (1) AI bỏ sót: **luật gộp nghiêng về cảnh báo**, và **người dùng** là người kiểm cuối. (2) AI bịa lý do: **code** kiểm câu trích phải có trong tin gốc. (3) Báo nhầm quá nhiều làm người dùng bỏ qua cảnh báo: **nhóm** theo dõi tỷ lệ báo nhầm hằng tuần trong pilot. (4) Chất lượng giảm theo thời gian khi kẻ gian đổi chiêu: **nhóm** chấm lại bộ tin mẫu mỗi tuần, cập nhật từ phản hồi người dùng |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Sinh viên và người lớn tuổi, cả hai là actor | Sinh viên là actor chính. Người lớn tuổi để ngoài pilot | Phản biện ở mục 5: hai nhóm dùng điện thoại rất khác nhau. Pilot với sinh viên dễ tuyển người và dễ đo hơn |
| Success Metric | Tỷ lệ phán đoán đúng trên bộ 20 tin mẫu | Tách thành bỏ sót ≤5% và báo nhầm ≤20%, bộ 50 tin mẫu (30/20) | Theo PAIR, hai kiểu sai có mức nghiêm trọng khác nhau nên phải đo riêng. 20 tin quá ít để đo được tỷ lệ 5% |
| Boundary | Ghi chung "con người quyết định" | Ghi rõ ai kiểm ở từng rủi ro (người dùng, code, nhóm) | Để trả lời được câu "nếu AI sai, ai phát hiện, ai sửa" |
| (mới) AI intervention point, Mức chọn, Rủi ro & người kiểm tra | — | Thêm theo mục 6 | Bắt buộc ở v1 |
| ⟨Bottleneck, Actor⟩ | | ⟨cập nhật sau phỏng vấn⟩ | ⟨ghi điều phỏng vấn làm nhóm đổi ý⟩ |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Không bỏ sót tin lừa đảo | Trên bộ 50 tin mẫu, ≥95% tin lừa đảo được xếp "Nguy hiểm" hoặc "Không chắc" | Có tin lừa đảo bị xếp "Chưa thấy dấu hiệu" vượt quá 5% |
| 2 | Không báo nhầm quá nhiều | ≤20% tin thật bị xếp "Nguy hiểm" | Hơn 20% tin thật bị cảnh báo, người dùng sẽ quen bỏ qua |
| 3 | Không bịa lý do | 100% câu trích trong lý do có nguyên văn trong tin gốc | Có câu trích không có trong tin, hoặc nêu dấu hiệu không có trong tin |
| 4 | Lý do dễ hiểu | Người dùng đọc trong <10 giây và nói lại được vì sao tin nguy hiểm | Lý do chung chung ("tin này có vẻ đáng ngờ") hoặc dùng thuật ngữ kỹ thuật |
| 5 | Đúng định dạng và đủ nhanh | Trả đúng JSON với các trường `muc`, `dau_hieu`, `goi_y`, trong <5 giây | JSON lỗi, thiếu trường, hoặc quá 5 giây (khi đó chuyển sang checklist) |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Cao** | Hậu quả của lừa đảo là có thật và nặng, nhưng chưa có bằng chứng người dùng chịu **dừng lại** để dán tin vào công cụ trước khi bấm (giả định #2). Đây là bottleneck mới ở mục 4.3. ⟨Hạ xuống TB hoặc Thấp nếu phỏng vấn cho thấy đa số đã có thói quen kiểm tra⟩ |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **TB** | Thao tác đơn giản (dán tin, đọc 3 mức màu), lý do có câu trích nên kiểm được bằng mắt. Rủi ro: người dùng quen bỏ qua cảnh báo nếu báo nhầm nhiều, và người lớn tuổi khó dùng thao tác "Chia sẻ"/dán |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **TB** | Mô hình ngôn ngữ đọc tiếng Việt và trả JSON là khả thi. Bộ tin mẫu tự thu được từ tin thật của thành viên. Chưa chắc có danh sách link lừa đảo công khai, cập nhật để Rule dùng (giả định #5, chờ research mục 3.3) |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **TB** | Chi phí gọi mô hình thấp với vài tin mỗi người mỗi tuần. Rủi ro: nội dung tin gửi tới bên thứ ba (quyền riêng tư), chưa rõ ai cập nhật danh sách lâu dài. Có thể đã có công cụ sẵn đủ tốt (giả định #6, chờ research mục 3.3) |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:** Value đang ở mức Cao vì giả định quan trọng nhất (người dùng có dừng lại kiểm tra không) chưa được kiểm chứng. Đây là rủi ro kiểm chứng được nhanh bằng phỏng vấn và một pilot nhỏ, nên chọn Not Yet thay vì No-Go. Ba rủi ro còn lại ở mức TB, có cách giảm rõ ràng. Nhóm đã viết được tiêu chí đánh giá, nghĩa là nhóm hiểu "tốt" nghĩa là gì.

**Nếu Go — pilot nhỏ nhất:** (áp dụng khi các điều kiện bên dưới được xác nhận) 5–10 sinh viên dùng trong 2 tuần. Bản đơn giản nhất: một trang web hoặc chatbot để dán tin vào, Rule đối chiếu danh sách link nhỏ, AI đọc nội dung, hiện 3 mức kèm lý do. Trước pilot, chấm trên bộ 50 tin mẫu, phải đạt tiêu chí 1–3 mới cho người dùng thật thử.

**Nếu Not Yet — cần kiểm chứng gì trước:**
1. **Giả định #2** (phỏng vấn mục 3.2): đa số người được hỏi có dừng lại kiểm tra tin lạ không. Nếu không, đổi bottleneck thành "không nhận ra cần kiểm tra", và hướng giải quyết đổi sang cảnh báo chủ động.
2. **Giả định #1** (phỏng vấn): người dùng nhận tin lạ ≥1 lần/tuần.
3. **Giả định #6** (research mục 3.3): công cụ có sẵn (cảnh báo của Zalo, nhà mạng, ngân hàng, các trang tra cứu lừa đảo) đã đủ chưa. Nếu đã đủ, chuyển sang hướng dẫn dùng công cụ có sẵn, không làm mới.
4. **Rule đủ chưa**: chạy riêng phần Rule trên bộ tin mẫu. Nếu Rule đã bắt ≥80% tin lừa đảo, hạ xuống mức Rule + checklist.

**Nếu No-Go — nên làm gì thay AI:** Checklist 6 dấu hiệu và quy tắc "không bấm link, tự tra số tổng đài", ghim trong nhóm chat gia đình và lớp, kết hợp hướng dẫn dùng tính năng cảnh báo có sẵn của điện thoại và ứng dụng nhắn tin.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): Nếu sau **2 tuần pilot** mà tỷ lệ bỏ sót trên bộ tin mẫu **>10%**, hoặc **hơn một nửa** cảnh báo "Nguy hiểm" bị người dùng bỏ qua, thì bỏ bước AI và quay về **Rule + checklist 6 dấu hiệu**.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**
- **Ít bằng chứng:** chỉ phỏng vấn ⟨số⟩ người, đều là sinh viên cùng khoá hoặc người thân, nên chưa đại diện cho người lớn tuổi, nhóm dễ bị lừa nhất.
- **Số liệu thời gian là ước tính:** các con số ở mục 4.1 và 4.3 chưa được đo bằng bấm giờ thật.
- **Chưa kiểm giả định #2:** chưa biết người dùng có chịu dừng lại để kiểm tra không, mà toàn bộ giải pháp phụ thuộc vào việc này.
- **Phạm vi hẹp:** chỉ xét tin nhắn văn bản, chưa xét cuộc gọi, ảnh chụp màn hình hay mã QR.
- **Chưa chạy thử:** chưa đo Rule và AI trên bộ tin mẫu, nên các target ≤5% và ≤20% mới là mục tiêu, chưa phải kết quả.

**Hướng tiếp theo:**
1. Phỏng vấn thêm 3–5 người, trong đó ít nhất 2 người lớn tuổi, để kiểm giả định #1 và #2.
2. Thu bộ 50 tin mẫu từ tin thật (đã xoá thông tin cá nhân), đo baseline khi người dùng tự đoán.
3. Hoàn thành research mục 3.3: nếu công cụ có sẵn đã đủ thì dừng, chuyển sang hướng dẫn dùng công cụ đó.
4. Chạy riêng Rule trên bộ tin mẫu. Nếu Rule đã bắt ≥80% thì hạ xuống Rule + checklist, không dùng AI.
5. Nếu các điều kiện trên đạt: pilot 2 tuần với 5–10 sinh viên, áp dụng ngưỡng dừng ở mục 8.2.

## 10. Tài liệu tham khảo

**Phương pháp:**
- Double Diamond, Design Council
- Job Stories, Alan Klement
- Opportunity Solution Tree, Teresa Torres, *Continuous Discovery Habits*
- *The Mom Test*, Rob Fitzpatrick
- Lean UX (Problem Statement), Jeff Gothelf
- Building Effective Agents (No AI / Rule / Workflow / Agent), Anthropic
- AI Canvas, Agrawal, Gans, Goldfarb, *Prediction Machines*
- People + AI Guidebook, Google PAIR
- Bốn rủi ro sản phẩm, Marty Cagan, SVPG

**Giải pháp đã có (mục 3.3):**
- Chống Lừa Đảo: https://chongluadao.vn
- Tín Nhiệm Mạng: https://tinnhiemmang.vn
- Google Safe Browsing: https://transparencyreport.google.com/safe-browsing/search
- VirusTotal: https://www.virustotal.com

**Tài liệu của nhóm:**
- Slide bảo vệ đề tài: [report/assets/cp6-defense-slides.html](../assets/cp6-defense-slides.html)
