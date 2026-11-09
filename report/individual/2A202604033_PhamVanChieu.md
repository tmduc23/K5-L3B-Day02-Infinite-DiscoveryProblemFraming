# Báo cáo cá nhân — 2A202604033_PhamVanChieu

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phạm Văn Chiêu 
- MSSV: 2A202604033
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Infinite
- Link repo nhóm: https://github.com/tmduc23/K5-L3B-Day02-Infinite-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận được tin nhắn hoặc đường link đáng ngờ, tôi muốn kiểm tra mức độ nguy hiểm để tránh mất tiền và thông tin cá nhân | Người dùng Internet, người lớn tuổi, sinh viên | Số tin nhắn đáng ngờ nhận được, số lần gặp website giả mạo, thời gian xác minh |
| 2 | Tốn thời gian | Khi đến một khu vực đông đúc, tôi muốn biết nơi còn chỗ đỗ xe để tiết kiệm thời gian | Người lái xe | Thời gian tìm chỗ đỗ, mất nhiên liệu di chuyển trước khi tìm được chỗ |
| 3 | Lặp lại | Khi nhận quá nhiều câu hỏi từ khách hàng, tôi muốn phân loại và ưu tiên yêu cầu để xử lý nhanh hơn | Nhân viên chăm sóc khách hàng, doanh nghiệp, khách hàng | Số yêu cầu mỗi ngày, thời gian phản hồi trung bình, số yêu cầu tồn đọng |
| 4 | Lặp lại | Khi có thực phẩm dư thừa hoặc sắp hết hạn, tôi muốn tìm cách sử dụng hoặc chia sẻ để tránh lãng phí | Hộ gia đình, nhà hàng, siêu thị, người có hoàn cảnh khó khăn | Lượng thực phẩm bị bỏ mỗi ngày, giá trị thực phẩm thất thoát |
| 5 | Pain từ người khác | Khi muốn học một môn hoặc thực hiện dự án, tôi muốn tìm người có cùng mục tiêu và trình độ để hỗ trợ nhau | Sinh viên | Khó tìm người học cùng, lịch học không trùng khớp |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi gặp lỗi môi trường lập trình, tôi muốn tìm giải pháp đúng phiên bản để sửa lỗi ngay | Sinh viên học lập trình | Gặp lỗi 2–3 lần/tuần; mất nhiều thời gian đọc để sửa |
| 7 | Lặp lại | Khi họp nhóm xong, tôi muốn có ngay danh sách đầu việc để các bạn không quên task | Trưởng nhóm | Mất 25 phút tóm tắt mỗi tuần; 2 lần thành viên quên việc đã nhận |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi có dấu hiệu mưa lớn hoặc ngập lụt, tôi muốn nhận được cảnh báo sớm để chủ động tìm đường khác di chuyển | Người dân vùng thường xuyên ngập lụt | Tần suất ngập, thời gian nhận cảnh báo, khu vực bị ảnh hưởng |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Ý giữ lại: Ý #1 và ý #4 vì đây là các vấn đề thực tế thường xuyên xảy ra trong xã hội, có actor rõ ràng.
- Ý loại bỏ: AI ban đầu gợi ý ý tưởng "Chatbot trả lời mọi thắc mắc học tập" và "Hệ thống tự chặn 100% tin nhắn lừa đảo". Tôi đã loại bỏ vì đây là các giải pháp trá hình mang tính viển vông, không có quy trình cụ thể và thiếu tính khả thi trong thực tế.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Nhận diện link/tin nhắn lừa đảo | Vấn đề nóng, nhiều người bị lừa, quy trình tra cứu rõ ràng. | Độ chính xác khi gặp thủ đoạn lừa đảo mới. |
| 2 | Tìm chỗ đỗ xe giờ cao điểm | Nỗi đau hàng ngày của người đi xe, đo lường được thời gian lãng phí. | Dữ liệu chỗ trống thời gian thực khó thu thập. |
| 3 | Phân loại tin nhắn CSKH quá tải | Quy trình lặp lại, dễ áp dụng từ Rule đến Workflow. | Khó phân biệt câu hỏi khẩn cấp và câu hỏi thông thường. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận link lạ, tôi muốn kiểm tra độ an toàn để tránh bị lừa tiền và lộ thông tin. |
| Actor | Người dùng Internet, sinh viên, người lớn tuổi trong nhà. |
| Thời điểm / bối cảnh | Khi nhận tin nhắn SMS, Telegram, Zalo báo trúng thưởng hoặc khóa tài khoản. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận tin nhắn → 2. Đọc nội dung → 3. Tra cứu trên Google/nhóm lừa đảo → 4. Hỏi người quen → 5. Quyết định mở hay chặn. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Tra cứu thông tin trên mạng mất 10–15 phút nhưng không rõ nguồn tin cậy. |
| Impact (nếu không giải thì sao) | Nguy cơ mất tiền trong tài khoản và lộ lọt thông tin cá nhân. |
| Success metric (baseline → target) | Thời gian kiểm tra giảm từ 15 phút xuống dưới 1 phút; tỷ lệ nhận diện đúng ≥95% |
| Phương án không dùng AI | Tạo danh sách đen (blacklist) các số điện thoại/tên miền lừa đảo để tra cứu thủ công. |
| Giả thuyết về AI (nếu có) | AI phân tích cú pháp tin nhắn và kiểm tra tên miền để cảnh báo rủi ro. |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
1. Nhận tin lạ: 1' → 2. Đọc nội dung: 2' → 3. Tra cứu Google/Mạng: 12' (BOTTLENECK) 
→ 4. Nhắn tin hỏi người quen: 5' → 5. Chặn/Bỏ qua: 1'
==> Tổng thời gian: ~21 phút
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến khu đông đúc, tôi muốn biết bãi xe còn chỗ để gửi ngay và không trễ hẹn. |
| Actor | Người điều khiển phương tiện (xe máy, ô tô), sinh viên. |
| Thời điểm / bối cảnh | Giờ cao điểm tại trung tâm thương mại, phố đi bộ, bệnh viện, trường học. |
| Quy trình hiện tại (3–7 bước) | 1. Đến địa điểm → 2. Vào bãi xe chính → 3. Nhận báo hết chỗ → 4. Chạy xe tìm bãi phụ quanh khu vực → 5. Gửi xe. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: Chạy xe lòng vòng tìm bãi gửi xe khác mất 15–20 phút. |
| Impact (nếu không giải thì sao) | Lãng phí xăng, tắc nghẽn giao thông và trễ giờ học/giờ hẹn quan trọng. |
| Success metric (baseline → target) | Thời gian tìm bãi đỗ giảm từ 20 phút xuống dưới 5 phút. |
| Phương án không dùng AI | Bảng điện tử báo số chỗ trống trước cửa bãi xe hoặc đặt chỗ trước qua Hotline. |
| Giả thuyết về AI | AI dự đoán bãi xe nào còn chỗ trống dựa trên giờ cao điểm và lịch sử. |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
1. Đến nơi: 2' → 2. Vào bãi chính: 3' → 3. Bảo vệ báo hết chỗ: 1' → 4. Đi lòng vòng tìm bãi phụ: 15' (BOTTLENECK) → 5. Gửi xe thành công: 2'
==> Tổng thời gian: ~23 phút
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận nhiều tin nhắn, tôi muốn phân loại câu hỏi để trả lời ca khẩn cấp nhanh hơn. |
| Actor | Nhân viên CSKH, quản trị viên fanpage CLB/sự kiện/bán hàng. |
| Thời điểm / bối cảnh | Các đợt cao điểm khuyến mãi, mở đăng ký vé, mùa tuyển sinh |
| Quy trình hiện tại (3–7 bước) | 1. Khách nhắn tin → 2. Admin đọc từng tin → 3. Phân loại nội dung → 4. Gõ câu trả lời hoặc chuyển tiếp → 5. Đóng hội thoại. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3: Đọc và phân loại từng tin nhắn mất 3–5 phút/tin, gây ứ đọng hàng loạt. |
| Impact (nếu không giải thì sao) | Khách chờ lâu 2–3 tiếng, bỏ đi hoặc phản ánh tiêu cực về dịch vụ. |
| Success metric (baseline → target) | Thời gian phản hồi ban đầu giảm từ 120 phút xuống dưới 10 phút. |
| Phương án không dùng AI | Dùng tin nhắn tự động (Chatbot kịch bản/FAQ) cho 5 câu hỏi thường gặp nhất. |
| Giả thuyết về AI | AI đọc hiểu ý định khách hàng để phân loại tag và gợi ý câu trả lời nháp. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
1. Nhận tin nhắn: 1' → 2. Đọc tin nhắn: 3' (BOTTLENECK) → 3. Phân loại thủ công: 2' → 4. Gõ câu trả lời: 3' → 5. Hoàn tất: 1'
==> Tổng thời gian/tin: ~10 phút
```

### Card muốn pitch nhất

- Card số: #3 (top 3)
- Vì sao: Vấn đề lặp lại hàng ngày, quy trình rõ, đo lường được thời gian phản hồi và số tin tồn đọng.
- Câu hỏi muốn nhóm phản biện: Làm sao phân loại đúng khi khách nhắn tin cộc lốc, viết tắt hoặc dùng tiếng lóng?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| 40 tin/ngày chưa đủ lớn để coi là quá tải đối với doanh nghiệp | Đồng ý | Bổ sung bối cảnh dồn dập vào đợt cao điểm sự kiện hoặc mở bán vé |
| Gợi ý để AI tự động trả lời và đóng tin nhắn luôn với khách | Không đồng ý | Giữ nguyên tắc AI chỉ phân loại tag, con người vẫn kiểm tra trước khi gửi. |
| Chưa có tiêu chí rõ ràng thế nào là tin nhắn "khẩn cấp". | Đồng ý | Định nghĩa rõ ca khẩn cấp là khách khiếu nại dịch vụ hoặc yêu cầu hoàn tiền |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 candidate: Link/tin nhắn lừa đảo (7), Tìm chỗ đỗ xe (8), Phân loại tin nhắn CSKH (9). | Candidate (7) đạt điểm cao nhất (30/35) và được nhóm chọn làm đề tài chính. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:<br>1. Hỏi Đức (Hỏi lại tiến độ #2): *"Vấn đề là thiếu công cụ hay có công cụ nhưng không ai cập nhật?"*<br>2. Hỏi Thắng (Cuộc gọi lừa đảo #10): *"Story này trùng với link lừa đảo, có nên gộp lại không? Đang nghe máy người dùng có kịp đọc cảnh báo không?"*<br>3. Hỏi Nam (Nhắc uống thuốc #6): *"Người lớn tuổi có dùng smartphone thành thạo không, sao hộp chia thuốc chưa giải quyết được?"* | 1. Làm Đức đổi ý, nhận ra do kỷ luật nhóm chứ không phải thiếu công cụ, chuyển (2) thành dự phòng.<br>2. Nhóm đồng ý gộp (10) vào (7) và thu hẹp về tin nhắn văn bản cho vừa sức lab.<br>3. Giúp Nam làm rõ rào cản thao tác công nghệ của người lớn tuổi. |
| Nhận phản biện | Câu hỏi tôi nhận được từ Đức: *"Mỗi tuần bạn nhận bao nhiêu link lạ? Trên thực tế người dùng có dừng lại kiểm tra trước khi bấm không, hay bấm theo phản xạ?"* | Tôi đã sửa gì: Đưa câu hỏi này thành **Giả định #2** trong Assumption Map (mục 3.1) và đưa vào bộ câu hỏi The Mom Test để phỏng vấn thực tế ở CP4. |
| Gom cluster / cây OST | Cùng nhóm gom 12 candidate thành 4 cluster (A, B, C, D) và dựng Cây OST rút gọn từ 1 Outcome chung. | Đưa candidate (7) vào Cluster A; gạch bỏ các giải pháp trá hình ("AI phân tích giọng nói", "AI tự lọc rác") để giữ đúng pain gốc. |
| Chọn candidate problem | Chấm điểm shortlist (mục 2.4) và bảo vệ candidate Link/tin nhắn lừa đảo (7). | Candidate (7) được chọn nhờ Impact cao nhất và phân biệt rõ 4 mức can thiệp (No AI/Rule/Workflow/Agent). |
| Kiểm chứng / research | Lập Assumption Map (3.1); soạn bộ câu hỏi The Mom Test; trực tiếp phỏng vấn 3 người (2 sinh viên, 1 phụ huynh); viết 3 Interview Snapshot (3.2). | Xác nhận Giả định #1, #3; phát hiện tín hiệu phản bác ở Giả định #2 (người dùng chỉ dừng lại kiểm tra khi tin mạo danh tinh vi; có lừa đảo không link); chốt baseline tra cứu 8 phút/tin. |
| Quy trình nhóm | Cung cấp dữ liệu từ phỏng vấn; hỗ trợ Đức đối chiếu quy trình hiện tại (mục 4.1) với lời kể của người dùng. | Xác định chính xác bước nghẽn là Bước 3 (tra cứu đối chiếu mất 8 phút) và bước nhờ người thân (chờ 90 phút). |
| Problem Statement | Cung cấp số liệu baseline (8 phút/tin, 1–2 lần/tuần) và insight từ phỏng vấn cho Thắng và Đức. | Giúp hoàn thiện Problem Statement v0 và v1 có success metric đo được (giảm xuống dưới 30s) và boundary không tự ý chặn/xóa tin. |
| Mức can thiệp AI | Phân tích ca lừa đảo mạo danh không có link từ kết quả phỏng vấn. | Thuyết phục nhóm Rule lọc URL là chưa đủ, bắt buộc phải dùng AI đọc hiểu ngữ cảnh văn bản (Workflow) và giữ Human-in-the-loop. |
| Quyết định | Cùng Nam và cả nhóm đánh giá 4 rủi ro (mục 8) và xác định ngưỡng dừng. | Đồng thuận chốt quyết định **Not Yet** vì rủi ro Value còn cao (Giả định #2 mới kiểm chứng trên 3 người), cần thêm dữ liệu trước khi Go. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm các vấn đề thực tế theo 4 lăng kính sau khi đã tự scan được 5 ý ban đầu. | Mở rộng góc nhìn sang các vấn đề quản lý chi phí, CSKH và đời sống thường ngày. | Gợi ý các giải pháp viển vông, solution trá hình như "Chatbot trả lời mọi thắc mắc học tập" hay "Hệ thống tự chặn 100% lừa đảo". | Loại bỏ các ý tưởng AI-first đó; chỉ giữ lại các vấn đề có quy trình rõ ràng và đo lường được bằng thời gian/tần suất thật. |
| CP2 Problem Card | Đóng vai "PM hoài nghi" để phản biện các Problem Card (đặc biệt Card #1 và Card #3). | Chỉ ra baseline 15 phút kiểm tra là ước chừng trí nhớ; nhắc nhở về rủi ro khi gặp thủ đoạn lừa đảo mới. | Đề xuất giải pháp tự động chặn hoặc xóa luôn tin nhắn của người dùng (tự động hóa hoàn toàn). | Bác bỏ việc tự động xóa tin vì nguy cơ chặn nhầm OTP quan trọng; kiên quyết giữ nguyên tắc Human-in-the-loop (AI chỉ cảnh báo, người dùng tự quyết). |
| CP4 Research | Liệt kê danh sách các công cụ bảo mật và kiểm tra URL lừa đảo đang có ở Việt Nam và quốc tế. | Tìm nhanh được các công cụ phổ biến như Chongluadao.vn, Google Safe Browsing, VirusTotal. | Cho rằng các công cụ này đã giải quyết trọn vẹn bài toán lừa đảo rồi. | Tự mở link kiểm tra thực tế và phát hiện các công cụ này chỉ quét link sau khi đã bấm hoặc khi đã có trong blacklist; bỏ trống hoàn toàn việc đọc hiểu nội dung tin nhắn văn bản trước khi bấm. |
| CP5 Quy trình | Chuyển đổi mô tả các bước thành cú pháp sơ đồ ASCII và rà soát các nhánh rẽ quy trình. | Định dạng sơ đồ luồng mạch lạc, phân tách rõ các bước con người, Rule và AI. | Bỏ quên phương án quay về khi AI gặp lỗi (mất mạng, lỗi JSON) và không có bước con người kiểm tra. | Bổ sung bước 3b (Rule kiểm tra câu trích nguyên văn của AI) và thiết lập cơ chế fallback sang checklist 6 dấu hiệu nếu AI bị lỗi. |
| CP5–6 Problem Statement | Soi lỗ hổng logic trong Problem Statement v0/v1 và kiểm tra tính khả thi của Success Metric. | Nhắc nhở metric phải có baseline đo lường cụ thể và bộ dữ liệu test mẫu phải đủ lớn (nâng từ 20 lên 50 mẫu). | Đề xuất gộp chung tỷ lệ nhận diện đúng thành 1 chỉ số duy nhất mà không phân biệt giữa bỏ sót và báo nhầm. | Tách riêng 2 metric độc lập: Bỏ sót ≤ 5% (ưu tiên số 1 vì nguy cơ mất tiền) và Báo nhầm ≤ 20% (theo khuyến nghị của Google PAIR). |
| CP6 Mức can thiệp / quyết định | Phản biện ma trận rủi ro và lựa chọn mức độ can thiệp giữa Rule, Workflow và Agent. | Gợi ý các rủi ro kỹ thuật khi gọi API mô hình ngôn ngữ và rủi ro quyền riêng tư khi gửi nội dung tin nhắn. | Hướng nhóm chọn giải pháp Agent tự động quét mạng xã hội và sandbox mở link để điều tra. | Kiên quyết chọn Workflow vì Agent quá nguy hiểm (mở link độc) và vi phạm nguyên tắc "chọn mức đơn giản nhất đủ dùng"; thống nhất quyết định "Not Yet" vì rủi ro Value còn cao. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe Đức pitch về "So giá sàn TMĐT" và "Hỏi lại tiến độ nhóm", Nam pitch về "Ôn thi từ nhiều tài liệu" và "Nhắc uống thuốc", Thắng pitch về "Cuộc gọi lừa đảo", tôi nhận ra ranh giới mong manh giữa một nỗi đau có thật và một giải pháp trá hình. Ban đầu các bạn hay đặt tên theo công cụ (như "cần một nơi cập nhật chung"), nhưng khi bị chất vấn thì nhận ra nhiều vấn đề xuất phát từ hành vi và kỷ luật con người chứ không phải thiếu phần mềm. Tôi học được cách lắng nghe có phản biện: phải luôn hỏi "người dùng đang đau đớn ở bước cụ thể nào", tần suất có đủ nhiều không và thiệt hại có đo lường được bằng tiền hay thời gian không trước khi vội vàng nghĩ đến công nghệ.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm bị "solution-first" rõ nhất ở giai đoạn đầu CP3 khi Thắng đưa ra ý tưởng "AI phân tích giọng nói và số điện thoại cuộc gọi", còn Đức muốn "Bảng so sánh tổng hợp sẵn tiến độ". Lúc gom vào cây OST, nhóm giật mình nhận ra mình đang viết tính năng AI thay vì mô tả nỗi đau của người dùng. Nhóm đã xử lý dứt khoát bằng cách gạch bỏ thẳng tay mọi câu chữ chứa từ "AI" hay "tính năng", chỉ giữ lại câu hỏi cốt lõi: "Người dùng đang kẹt ở bước nào trong quy trình?". Nhờ đó, cả nhóm mới quy tụ về outcome chung là giảm số phút tự tra cứu và giảm thiểu số lần phán đoán sai lầm.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã đổi ý hoàn toàn sau câu hỏi phản biện của Đức khi tôi pitch candidate Link lừa đảo: Đức hỏi *"Trên thực tế người dùng có dừng lại kiểm tra trước khi bấm không, hay họ bấm theo phản xạ?"*. Ban đầu tôi đinh ninh rằng ai nhận link lạ cũng sẽ cảnh giác tra cứu. Câu hỏi của Đức làm tôi nhận ra đây là một giả định vô cùng mạo hiểm (Giả định #2 trong Assumption Map). Khi tôi trực tiếp đi phỏng vấn bạn sinh viên ở Snapshot 3, bạn ấy thẳng thắn chia sẻ: *"Mấy tin rác trúng thưởng em vuốt xóa trong 2 giây chứ rảnh đâu mà copy đi kiểm tra"*. Nhờ đó, tôi đã chủ động đề xuất nhóm đổi ý: không dàn trải giải quyết mọi tin nhắn rác lộ liễu, mà chỉ tập trung vào các tin mạo danh đánh trúng bối cảnh thực tế (giao hàng, ngân hàng, người quen) — nơi người dùng thực sự băn khoăn và có hành vi dừng lại kiểm tra.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Quá trình phỏng vấn người thật mang lại cho tôi hai bất ngờ lớn. Thứ nhất, khi phỏng vấn mẹ của bạn trong nhóm (Snapshot 2), tôi bất ngờ khi thấy người lớn tuổi hoàn toàn bất lực trước việc đọc tên miền hay tra cứu Google; họ phải chụp màn hình gửi con cháu và chờ đợi trung bình tới 90 phút trong lo âu sợ hãi. Thứ hai, bạn sinh viên IT (Snapshot 3) tiết lộ rằng các vụ lừa đảo nguy hiểm nhất mà bạn ấy từng suýt dính bẫy lại **hoàn toàn không có link**, chỉ là tin nhắn giả mạo bạn bè nhắn tin thúc ép chuyển tiền gấp. Điều này làm sụp đổ suy nghĩ ban đầu của tôi rằng chỉ cần dùng Rule lọc URL là giải quyết xong bài toán lừa đảo.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất là viết **Success Metric** và xác định ranh giới **Boundary**. Rất dễ sa đà vào viết các câu chữ mơ hồ như "giúp người dùng an toàn hơn" hay "tiết kiệm thời gian". Nhóm đã phải dựa vào dữ liệu phỏng vấn thật để lượng hóa baseline (tự tra cứu mất 8 phút/lần) và đặt target cụ thể (dưới 30 giây/lần), đồng thời chia nhỏ metric thành tỷ lệ bỏ sót (≤ 5%) và tỷ lệ báo nhầm (≤ 20%). Về Boundary, nhóm phải đấu tranh để giữ vững nguyên tắc: AI tuyệt đối không được tự ý xóa tin nhắn hay kết luận "an toàn tuyệt đối", quyền quyết định sau cùng bắt buộc phải thuộc về con người (Human-in-the-loop).

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu được làm lại, tôi sẽ phỏng vấn thêm ít nhất 2–3 người lớn tuổi nữa ngay từ đầu thay vì chỉ hỏi sinh viên, vì người lớn tuổi mới là nhóm đối tượng chịu tổn thương và mất mát tài chính nặng nề nhất. Ngoài ra, tôi sẽ phản biện nhóm quyết liệt hơn ở quyết định khoanh vùng Actor: nhóm chọn sinh viên cho an toàn và dễ làm pilot, nhưng tôi nghĩ điều đó vô tình né tránh tệp người dùng đang đau đớn nhất. Nếu có thời gian, tôi sẽ thúc đẩy việc thiết kế giao diện dạng bot chat Zalo để người lớn tuổi chỉ cần bấm chuyển tiếp (forward) tin nhắn là nhận được kết quả, thay vì bắt họ copy-paste đường link quá phức tạp.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán của nhóm xuất phát từ **problem** người dùng điện thoại mất trung bình 8 phút tự tra cứu trong hoang mang hoặc phán đoán sai lầm bằng cảm tính khi nhận tin nhắn lạ, dẫn tới rủi ro mất tiền và tài khoản ngân hàng. **Quy trình** hiện tại bị nghẽn nặng nề ở bước tra cứu thông tin rời rạc hoặc chờ đợi người thân giải đáp. Nhóm thiết kế quy trình mới hướng tới **success metric** đo lường được: giảm thời gian ra quyết định xuống dưới 30 giây/tin, tỷ lệ bỏ sót tin lừa đảo ≤ 5% và tỷ lệ báo nhầm ≤ 20%. **Boundary** được xác lập nghiêm ngặt: AI không bao giờ tự ý xóa tin, không kết luận an toàn tuyệt đối và con người luôn là người đưa ra phán quyết cuối cùng (Human-in-the-loop). Nhóm chọn **mức can thiệp Workflow** kết hợp Rule đối chiếu blacklist URL với AI đọc hiểu ngữ cảnh văn bản, bởi vì Rule thuần túy hoàn toàn bất lực trước các tin lừa đảo không chứa link. Cuối cùng, nhóm đưa ra **quyết định Not Yet** có lập luận chặt chẽ: rủi ro Value còn cao do giả định người dùng có dừng lại kiểm tra hay không mới kiểm chứng trên mẫu nhỏ, do đó cần chạy thử nghiệm pilot 2 tuần kèm ngưỡng dừng đo lường được trước khi quyết định Go chính thức.

---

## 7. Tài liệu tham khảo

- Dự án Chống Lừa Đảo: https://chongluadao.vn
- Cổng Tín Nhiệm Mạng (Cục An toàn thông tin, Bộ TT&TT): https://tinnhiemmang.vn
- Google Safe Browsing Transparency Report: https://transparencyreport.google.com/safe-browsing/search
- People + AI Guidebook, Google PAIR
- *The Mom Test*, Rob Fitzpatrick
- Double Diamond Design Model, Design Council UK
