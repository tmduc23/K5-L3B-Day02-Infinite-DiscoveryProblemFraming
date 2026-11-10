# Báo cáo cá nhân — 2A202604022_VuTrongThang

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Trọng Thắng
- MSSV: 2A202604022
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Infinite.
- Link repo nhóm: https://github.com/tmduc23/K5-L3B-Day02-Infinite-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1) .

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ  người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi thường xuyên nhận tin nhắn quảng cáo, tôi muốn lọc chúng tự động để hộp thư không bị quá tải. | Người sử dụng điện thoại | Cần kiểm tra nhiều số điện thoại lạ; tần suất cần khảo sát. |
| 2 | Tốn thời gian | Khi nhận được cuộc gọi có nội dung đáng ngờ, tôi muốn nhanh chóng xác minh thông tin người gọi, để không mất thời gian tự tìm kiếm và kiểm tra. | | |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi nghi ngờ một cuộc gọi có dấu hiệu lừa đảo, tôi muốn tổng hợp thông tin từ nhiều nguồn, để đánh giá mức độ đáng tin cậy. | Người nhận cuộc gọi | Phải đối chiếu số điện thoại, nội dung cuộc gọi và cảnh báo từ cộng đồng. |
| 4 | Pain từ người khác | Khi người thân nhận được cuộc gọi yêu cầu cung cấp thông tin cá nhân hoặc chuyển tiền, tôi muốn giúp họ xác minh cuộc gọi, để hạn chế nguy cơ bị lừa đảo. | Người lớn tuổi, người thân và gia đình | Người thân có thể thiếu kinh nghiệm nhận biết thủ đoạn lừa đảo; cần ghi nhận trường hợp thực tế. |
| 5 | | | | |
| 6 | | | | |
| 7 | | | | |


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Nhận diện cuộc gọi lừa đảo | Cuộc gọi lừa đảo ngày càng gây nguy cơ mất tiền và thông tin cá nhân. AI có thể phân tích số điện thoại, giọng nói và nội dung cuộc gọi để phát hiện dấu hiệu đáng ngờ, giúp người dùng chủ động phòng tránh. | Làm thế nào để AI phân biệt chính xác cuộc gọi lừa đảo và cuộc gọi hợp pháp? Có đủ dữ liệu cuộc gọi để huấn luyện mô hình không? |
| 2 | Nhận diện quảng cáo rác | Người dùng thường xuyên bị làm phiền bởi quảng cáo không mong muốn qua tin nhắn, email và mạng xã hội. AI có thể phân tích nội dung để tự động nhận diện và lọc quảng cáo rác. | Làm thế nào để phân biệt quảng cáo rác với quảng cáo hợp pháp? AI có nhận diện được nhiều hình thức quảng cáo khác nhau không? |
| 3 | Tìm phòng trọ tại khu vực đông đúc | Sinh viên thường gặp khó khăn khi tìm phòng trọ phù hợp về giá cả, vị trí và tiện nghi. AI có thể đề xuất phòng phù hợp, phân tích giá thuê và phát hiện tin đăng có dấu hiệu lừa đảo. | Làm thế nào để cập nhật thông tin phòng trọ chính xác và liên tục? Làm sao xác minh phòng còn trống, giá thuê và độ tin cậy của người đăng? |

### Problem Card #1 Nhận diện cuộc gọi lừa đảo

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận cuộc gọi từ số lạ, tôi muốn nhận biết dấu hiệu lừa đảo, để bảo vệ thông tin và tài sản cá nhân. |
| Actor | Người sử dụng điện thoại. |
| Thời điểm / bối cảnh | Khi nhận cuộc gọi từ số lạ hoặc người tự xưng là cơ quan, ngân hàng. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận cuộc gọi. 2. Nghe nội dung. 3. Nhận thấy dấu hiệu bất thường. 4. Tìm kiếm số điện thoại trên Internet. 5. Quyết định nghe tiếp hoặc ngắt máy. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Khó xác minh danh tính người gọi và độ tin cậy của thông tin. |
| Impact (nếu không giải thì sao) | Có nguy cơ mất tiền hoặc lộ thông tin cá nhân. |
| Success metric (baseline → target) | Tăng tỷ lệ nhận diện chính xác cuộc gọi lừa đảo; giảm cảnh báo sai. |
| Phương án không dùng AI | ra cứu số điện thoại và danh sách cảnh báo lừa đảo. |
| Giả thuyết về AI (nếu có) AI phân tích nội dung cuộc gọi và phát hiện dấu hiệu lừa đảo.| |
| Cảm nhận nhanh |  Agent  |

Quy trình nháp hiện tại:

```text

```

### Problem Card #2 nhận diện quảng cáo rác

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được cuộc gọi hoặc tin nhắn quảng cáo không mong muốn, tôi muốn nhận diện nội dung quảng cáo rác, để tránh bị làm phiền và tiếp xúc với thông tin không cần thiết. |
| Actor | Người sử dụng điện thoại. |
| Thời điểm / bối cảnh | Khi nhận cuộc gọi hoặc tin nhắn quảng cáo từ số lạ. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận cuộc gọi hoặc tin nhắn. 2. Kiểm tra số điện thoại và nội dung. 3. Đánh giá mục đích liên hệ. 4. Xác định có phải quảng cáo rác không. 5. Bỏ qua hoặc chặn liên hệ. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Khó phân biệt quảng cáo hợp pháp, quảng cáo không mong muốn và nội dung lừa đảo. |
| Impact (nếu không giải thì sao) | Mất thời gian, bị làm phiền và có nguy cơ tiếp xúc với nội dung không an toàn. |
| Success metric (baseline → target) | Tăng độ chính xác nhận diện quảng cáo rác, giảm tỷ lệ phân loại nhầm. |
| Phương án không dùng AI | Lọc theo từ khóa, danh sách số điện thoại quảng cáo đã biết và chặn thủ công. |
| Giả thuyết về AI (nếu có) | AI phân tích số điện thoại và nội dung cuộc gọi hoặc tin nhắn để phân loại quảng cáo rác. |
| Cảm nhận nhanh | Rule / Workflow  |

Quy trình nháp hiện tại:

```text

```

### Problem Card #3 Tìm phòng trọ tại khu vực đông đúc

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần tìm phòng trọ tại khu vực đông dân cư, tôi muốn tìm được phòng phù hợp với ngân sách và nhu cầu, để tiết kiệm thời gian tìm kiếm. |
| Actor | Sinh viên và người lao động cần thuê trọ. |
| Thời điểm / bối cảnh | Khi tìm phòng trọ tại các thành phố hoặc khu vực đông dân cư. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định ngân sách. 2. Tìm tin đăng trên các hội nhóm và website. 3. So sánh giá và vị trí. 4. Liên hệ chủ trọ. 5. Đến xem phòng. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Tin đăng phân tán, khó kiểm chứng và khó so sánh phòng trọ. |
| Impact (nếu không giải thì sao) | Mất nhiều thời gian, có thể gặp tin giả hoặc phòng không đúng mô tả. |
| Success metric (baseline → target) | Giảm thời gian tìm phòng phù hợp và số tin đăng không chính xác phải liên hệ. |
| Phương án không dùng AI | Sử dụng bộ lọc giá, khu vực và tiện ích trên website tìm trọ. |
| Giả thuyết về AI (nếu có) | AI tổng hợp, lọc và đề xuất phòng phù hợp với nhu cầu người thuê. |
| Cảm nhận nhanh |  Workflow  |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số: 1 – Nhận diện cuộc gọi lừa đảo.
- Vì sao: Đây là vấn đề có thể gây thiệt hại trực tiếp về tiền bạc và thông tin cá nhân. Tôi muốn tìm hiểu cách ứng dụng AI để hỗ trợ người dùng nhận biết các cuộc gọi đáng ngờ, đặc biệt là những người chưa có nhiều kinh nghiệm nhận diện lừa đảo.
- Câu hỏi muốn nhóm phản biện: Làm thế nào để phân biệt cuộc gọi lừa đảo với cuộc gọi hợp pháp? Việc phân tích nội dung cuộc gọi có khả thi không và người dùng có thể nhận cảnh báo kịp thời không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Khó phân biệt chính xác cuộc gọi lừa đảo và cuộc gọi hợp pháp. | Có | Cần xác định rõ dấu hiệu nhận diện và đánh giá tỷ lệ cảnh báo sai. |
| Cần dữ liệu cuộc gọi thực tế để phân tích và kiểm chứng. | Có | Không mặc định AI có thể nhận diện chính xác nếu chưa có dữ liệu phù hợp. |
| Việc cảnh báo trong lúc người dùng đang nghe điện thoại có thể không thuận tiện. | Có | Cân nhắc thu hẹp phạm vi sang nhận diện tin nhắn và đường link lừa đảo. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Đưa ra 3 ý tưởng: nhận diện cuộc gọi lừa đảo, lọc quảng cáo không mong muốn, tìm phòng trọ phù hợp. | Bổ sung 3 candidate để nhóm xem xét. Ý tưởng cuộc gọi lừa đảo được liên hệ với candidate nhận diện link/tin nhắn lừa đảo của Chiêu. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Đặt câu hỏi về: (1) mức độ cần thiết của việc tự động thiết lập máy tính mỗi sáng; (2) tần suất đi Grab nhiều điểm dừng và việc chia tiền có thực sự gây tranh cãi; (3) bằng chứng thực tế từ nhân viên CSKH và cách xác định tin nhắn khẩn cấp. | Giúp kiểm tra pain có đủ lớn không, vấn đề có thường xuyên xảy ra không, giải pháp hiện tại đã đáp ứng chưa và người đưa ra ý tưởng có bằng chứng thực tế không. |
| Nhận phản biện | Câu hỏi tôi nhận được: Nhận phản biện từ Chiêu về việc ý tưởng nhận diện cuộc gọi lừa đảo khá trùng với nhận diện link/tin nhắn lừa đảo; người dùng có kịp đọc cảnh báo khi đang nghe điện thoại không. | Tôi đã sửa gì: Đề xuất gộp hai candidate thành hướng nhận diện lừa đảo. Sau đó nhóm chọn phạm vi link/tin nhắn văn bản, chưa xử lý cuộc gọi vì khó kiểm tra trong thời gian thực và vượt phạm vi buổi lab. |
| Gom cluster / cây OST | Ý tưởng cuộc gọi lừa đảo của tôi được xếp vào Cluster A cùng link/tin nhắn lừa đảo và quảng cáo rác. | Góp phần hình thành Opportunity A: người dùng phải tự phán đoán tin nhắn, cuộc gọi hoặc quảng cáo có đáng tin không. Tuy nhiên, báo cáo không ghi riêng tôi là người trực tiếp xây dựng cluster hoặc cây OST. |
| Chọn candidate problem | Đóng góp ý tưởng cuộc gọi lừa đảo, sau đó được nhóm gộp với candidate link/tin nhắn lừa đảo. | Candidate lừa đảo được chọn vào shortlist và đạt 30/35 điểm. Báo cáo ghi rõ pain này xuất hiện độc lập ở Chiêu và tôi. Nhóm cuối cùng chỉ giữ phạm vi tin nhắn/link văn bản. |
| Kiểm chứng / research | Báo cáo có ghi nhận ý tưởng của tôi là một trong hai nguồn khiến nhóm nhận thấy vấn đề lừa đảo xuất hiện độc lập. Không ghi rõ tôi trực tiếp phỏng vấn hay thực hiện research công cụ. | Nhóm phỏng vấn 3 người, phát hiện người dùng chỉ thực sự dừng lại kiểm tra khi tin nhắn đánh vào bối cảnh cá nhân; đồng thời thu hẹp phạm vi bài toán. Không nên nhận toàn bộ kết quả phỏng vấn là công việc cá nhân nếu không trực tiếp thực hiện. |
| Quy trình nhóm | Không có phần nào trong báo cáo ghi rõ tôi trực tiếp xây dựng quy trình trước/sau. | Nhóm mô tả quy trình hiện tại và quy trình tương lai: người dùng nhập tin, Rule kiểm tra link, AI phân tích nội dung, Rule kiểm tra lại và người dùng tự quyết định. |
| Problem Statement | Không có ghi nhận cá nhân cụ thể về việc tôi trực tiếp viết Problem Statement. | Nhóm thu hẹp actor chính thành sinh viên; tập trung vào tin nhắn mạo danh trong bối cảnh cụ thể; xác định bottleneck, impact, success metric và boundary. |
| Mức can thiệp AI | Không có ghi nhận cá nhân cụ thể về việc tôi trực tiếp xây dựng AI Canvas hoặc lựa chọn kiến trúc. |Nhóm chọn Workflow: Rule → AI → Rule kiểm tra lại → con người quyết định. AI chỉ hỗ trợ đọc hiểu nội dung tin, không tự chặn hoặc thao tác thay người dùng. |
| Quyết định | Không có ghi nhận tôi là người trực tiếp đưa ra quyết định cuối cùng. | Nhóm chọn Not Yet vì chưa xác minh chắc chắn giả định quan trọng: người dùng có thực sự dừng lại kiểm tra tin nhắn trước khi bấm hay không. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Hỗ trợ phân tích các vấn đề, bóc tách nhu cầu người dùng và phân biệt vấn đề thực tế với ý tưởng giải pháp. | Giúp mở rộng góc nhìn, diễn đạt vấn đề rõ ràng hơn và nhận ra những khía cạnh cần xem xét. | Có thể đưa ra các ý tưởng nghe hợp lý nhưng chưa có bằng chứng về tần suất, mức độ nghiêm trọng hoặc nhu cầu thực tế. | Không mặc định ý tưởng AI đưa ra là vấn đề đáng giải quyết. Cần xem xét trải nghiệm thực tế, actor và bottleneck trước khi lựa chọn. |
| CP2 Problem Card | Hỗ trợ diễn đạt Job Story, Actor, quy trình và Bottleneck cho các vấn đề được đưa ra. | Giúp chuẩn hóa cấu trúc Problem Card và làm rõ mối liên hệ giữa hoàn cảnh, nhu cầu và kết quả mong muốn. | Có thể biến một giải pháp thành Problem Statement, chẳng hạn đưa AI tự động lọc quảng cáo hoặc đề xuất phòng trọ vào phần mô tả vấn đề. | Phân biệt rõ opportunity với solution. Ví dụ, vấn đề của quảng cáo rác là người dùng phải tự xem và xóa từng quảng cáo, không phải thiếu một công cụ AI lọc quảng cáo. |
| CP4 Research | Hỗ trợ tổng hợp thông tin, phân tích giả định cần kiểm chứng và tìm hiểu các công cụ chống lừa đảo hiện có. | Giúp hệ thống hóa các giả định Value, Usability, Feasibility, Viability; hỗ trợ so sánh Chống Lừa Đảo, Tín Nhiệm Mạng, Google Safe Browsing và VirusTotal. | Thông tin từ AI không tự chứng minh người dùng thực sự gặp vấn đề. Việc liệt kê công cụ cũng chưa đủ để kết luận các giải pháp hiện tại không đáp ứng nhu cầu. | Dựa vào phỏng vấn thực tế để kiểm chứng. Nhóm phát hiện người dùng chỉ dừng lại kiểm tra khi tin nhắn đánh vào bối cảnh cá nhân; đồng thời nhận ra tin lừa đảo không có link cũng cần được xem xét. |
| CP5 Quy trình | Hỗ trợ mô tả và hệ thống hóa quy trình trước/sau khi có giải pháp. | Giúp chia quy trình thành từng bước, xác định Actor, Input, Output và thời gian xử lý; dễ nhận diện bottleneck. | Quy trình mô tả trên lý thuyết có thể chưa phản ánh đúng hành vi thực tế. Không phải người dùng nào cũng dừng lại kiểm tra tin nhắn đáng ngờ. | Điều chỉnh quy trình dựa trên phỏng vấn. Không coi mọi tin nhắn lạ đều cần kiểm tra; tập trung vào tin mạo danh đánh trúng bối cảnh thật khiến người dùng phân vân. |
| CP5–6 Problem Statement | Hỗ trợ tổ chức các thành phần Actor, Process, Bottleneck, Impact, Success Metric và Boundary. | Giúp trình bày Problem Statement có cấu trúc, xác định tiêu chí đánh giá và so sánh phiên bản v0 với v1. | Nếu chỉ dựa vào giả định ban đầu, Problem Statement có thể quá rộng, gộp nhiều nhóm người dùng khác nhau và đặt metric chưa có baseline. | Thu hẹp actor chính thành sinh viên cho pilot, đưa người lớn tuổi sang giai đoạn mở rộng; tách tỷ lệ bỏ sót và báo nhầm; không coi target là kết quả đã đạt được. |
| CP6 Mức can thiệp / quyết định | Hỗ trợ phân tích các mức No AI, Rule, Workflow, Agent và đánh giá rủi ro khi đưa AI vào sản phẩm. | Giúp so sánh ưu nhược điểm từng mức, xác định AI nên can thiệp ở đâu và xây dựng AI Canvas. | Dùng AI quá nhiều có thể làm giải pháp phức tạp không cần thiết. AI có thể bỏ sót tin lừa đảo hoặc bịa lý do cảnh báo; không nên giao toàn bộ quyết định cho AI. | Chọn Workflow: Rule kiểm tra link → AI đọc hiểu nội dung → Rule kiểm tra lại → người dùng quyết định. Giữ boundary rõ ràng và chọn Not Yet vì giả định về hành vi người dùng vẫn cần kiểm chứng. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Tôi nhận ra một ý tưởng hữu ích chưa chắc đã là một vấn đề đáng giải quyết. Cần xem xét tần suất xảy ra, mức độ ảnh hưởng và nhu cầu thực tế của người dùng. Ví dụ, tôi đã đặt câu hỏi về mức độ cần thiết của việc tự động thiết lập máy tính và tần suất xảy ra tranh chấp khi chia tiền Grab.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có. Nhóm đôi lúc tập trung vào việc xây dựng công cụ AI nhận diện lừa đảo trước khi hiểu rõ vấn đề. Sau đó, nhóm quay lại phân tích người dùng, quy trình hiện tại và những khó khăn họ gặp phải. Tôi hiểu rằng cần xác định đúng vấn đề trước khi chọn giải pháp.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Tôi từng đề xuất nhận diện cuộc gọi lừa đảo, nhưng được phản biện rằng ý tưởng này có phần trùng với nhận diện tin nhắn và đường link. Ngoài ra, cảnh báo khi người dùng đang nghe điện thoại có thể không thuận tiện. Tôi nhận ra cần thu hẹp phạm vi để đề tài thực tế và dễ triển khai hơn.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Tôi chú ý đến việc người dùng có thể chỉ kiểm tra tin nhắn khi nội dung liên quan trực tiếp đến hoàn cảnh cá nhân. Điều này cho thấy việc phát hiện lừa đảo không chỉ phụ thuộc vào công nghệ mà còn phụ thuộc vào hành vi người dùng.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất là mô tả đúng vấn đề mà không đưa giải pháp vào quá sớm. Tôi phải xác định rõ người dùng, khó khăn, bottleneck và tác động thay vì chỉ tập trung vào ý tưởng xây dựng AI.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Tôi sẽ tìm hiểu kỹ hơn về người dùng, tần suất xảy ra vấn đề và các công cụ hiện có. Tôi cũng sẽ phản biện mạnh hơn về phạm vi đề tài và sự cần thiết của AI, tránh sử dụng AI chỉ vì dự án có chủ đề AI.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Vấn đề nhóm lựa chọn là người dùng khó nhận biết tin nhắn và đường link lừa đảo. Quy trình hiện tại gồm nhận tin nhắn, kiểm tra dấu hiệu bất thường và quyết định có tương tác hay không. Metric cần quan tâm là khả năng phát hiện lừa đảo và tỷ lệ cảnh báo nhầm. Boundary xác định phạm vi tin nhắn, đường link và nhóm người dùng được hỗ trợ. Nhóm định hướng kết hợp Rule và AI để phân tích nội dung. Sau đó, Rule hỗ trợ kiểm tra kết quả và người dùng quyết định cuối cùng. Nhóm chọn Not Yet vì vẫn cần kiểm chứng thêm các giả định trước khi triển khai.

---

## 7. Tài liệu tham khảo
Chống Lừa Đảo. https://chongluadao.vn/

Tín Nhiệm Mạng – Cục An toàn thông tin. https://tinnhiemmang.vn/

Google Safe Browsing. https://safebrowsing.google.com/

VirusTotal. https://www.virustotal.com/

Google. Google Search. https://www.google.com/

-
