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

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
