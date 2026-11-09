# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trương Đặng Minh Khuê
- MSSV: 2A202603785
- Email trường (không bắt buộc, repo có thể để public): 26ai.khuetdm@vinuni.edu.vn
- Tên nhóm: I3
- Link repo nhóm: https://github.com/mKhaiTruong/K5-L3B-DAY02-I3-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                          | Job Story: Khi… tôi muốn… để…                                                                                                                                                        | Ai chịu ảnh hưởng?                         | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                               |
| --: | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------ | --------------------------------------------------------------------------------------- |
|   1 | Tốn thời gian                      | Khi đọc ảnh X-quang ngực để chẩn đoán viêm phổi, tôi muốn được hỗ trợ nhận diện những vùng nghi ngờ tổn thương, để giảm nguy cơ bỏ sót dấu hiệu bất thường                           | Bác sĩ chẩn đoán hình ảnh, bác sĩ lâm sàng | Cần khảo sát số lượng ảnh X-quang phải đọc mỗi ngày và thời gian đọc trung bình mỗi ảnh |
|   2 | Tốn thời gian / Tổng hợp thông tin | Khi gặp một ca bệnh có biểu hiện bất thường hoặc ít gặp, tôi muốn nhanh chóng tìm được tài liệu và nghiên cứu y khoa liên quan, để có thêm cơ sở tham khảo cho quyết định chuyên môn | Bác sĩ, bác sĩ nội trú                     | Cần khảo sát thời gian tra cứu và số lượng tài liệu phải tham khảo cho mỗi ca           |
|   3 | Lặp lại                            | Khi cần kiểm tra hoặc phân loại thuốc, tôi muốn nhanh chóng xác định nhóm thuốc, hoạt chất và thông tin liên quan, để giảm thời gian tra cứu và hạn chế nhầm lẫn                     | Dược sĩ, bác sĩ, nhân viên quản lý dược    | Cần khảo sát số lượng thuốc phải tra cứu và thời gian xử lý mỗi ngày                    |
|   4 | Tốn thời gian / Tổng hợp thông tin | Khi tiếp nhận bệnh nhân đã từng khám nhiều lần, tôi muốn nhanh chóng nắm được lịch sử bệnh án và quá trình điều trị trước đó, để có đủ thông tin phục vụ quá trình thăm khám         | Bác sĩ, nhân viên y tế                     | Cần khảo sát thời gian đọc hồ sơ và số lượng hồ sơ cần xem mỗi ca                       |
|   5 | Lặp lại / Pain từ người khác       | Khi tiếp nhận nhiều yêu cầu từ bệnh nhân mỗi ngày, tôi muốn phân loại yêu cầu theo nội dung và mức độ ưu tiên, để chuyển đúng bộ phận phụ trách và giảm thời gian chờ phản hồi       | Nhân viên chăm sóc khách hàng, bệnh nhân   | Cần khảo sát số lượng yêu cầu mỗi ngày, thời gian phản hồi và tỷ lệ chuyển sai bộ phận  |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

Giữ lại:

- Tóm tắt hồ sơ bệnh án: AI gợi ý vì bác sĩ thường phải đọc nhiều hồ sơ từ các lần khám trước, việc tổng hợp thông tin có thể tốn thời gian.
- Phân loại yêu cầu bệnh nhân: AI gợi ý vì bệnh viện có thể tiếp nhận nhiều yêu cầu qua các kênh khác nhau, cần phân loại để chuyển đúng bộ phận.

Bỏ qua:

- Chatbot tư vấn sức khỏe tổng quát: Quá rộng, có nguy cơ cung cấp thông tin y tế thiếu chính xác và không phù hợp để thay thế tư vấn chuyên môn.
- Dự đoán bệnh từ triệu chứng: Phạm vi quá lớn, khó xác định dữ liệu đầu vào và tiêu chí đánh giá trong thời gian ngắn.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                                                                 | Vì sao chọn                                                                                                                                                                        | Điều còn chưa chắc                                                                                                                 |
| ---: | --------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
|    1 | Hỗ trợ bác sĩ tìm kiếm và tổng hợp tài liệu y khoa cho các ca bệnh hiếm hoặc bất thường | Bác sĩ là actor rõ ràng; workflow tìm kiếm > đọc > đối chiếu > tổng hợp khá dễ mô tả. Có thể đo thời gian tìm tài liệu và mức độ liên quan của kết quả. Phù hợp để thử nghiệm RAG. | Chưa xác định nguồn tài liệu y khoa đáng tin cậy; cần kiểm chứng độ chính xác và tính cập nhật của thông tin.                      |
|    2 | Tự động tóm tắt hồ sơ bệnh án của bệnh nhân qua nhiều lần khám                          | Workflow tương đối rõ; vấn đề đọc nhiều hồ sơ và tổng hợp thông tin có thể gây tốn thời gian. Có thể đo thời gian đọc hồ sơ và độ đầy đủ của bản tóm tắt.                          | Chưa biết mức độ sẵn có của dữ liệu hồ sơ; cần đảm bảo quyền riêng tư và tránh bỏ sót thông tin quan trọng.                        |
|    3 | Hỗ trợ phát hiện dấu hiệu nghi ngờ viêm phổi trên ảnh X-quang                           | Bottleneck tương đối cụ thể; có thể đánh giá bằng Recall, Precision, F1-score và thời gian đọc ảnh. Giá trị tiềm năng cao nếu giảm được nguy cơ bỏ sót dấu hiệu bất thường.        | Cần dữ liệu ảnh X-quang đã được chuyên gia gán nhãn; yêu cầu kiểm định lâm sàng cao. Chưa xác minh được thời gian đọc ảnh thực tế. |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                                                                                                                                                                                                         |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi gặp các ca bệnh hiếm hoặc có biểu hiện bất thường, tôi muốn nhanh chóng tìm kiếm và tổng hợp các tài liệu y khoa liên quan, để có thêm thông tin tham khảo phục vụ quá trình đánh giá và đưa ra hướng xử trí phù hợp.                                                                                                        |
| Actor                                     | Bác sĩ điều trị / bác sĩ chuyên khoa                                                                                                                                                                                                                                                                                             |
| Thời điểm / bối cảnh                      | Khi tiếp nhận ca bệnh hiếm, phức tạp hoặc có biểu hiện không điển hình.                                                                                                                                                                                                                                                          |
| Quy trình hiện tại (3–7 bước)             | 1. Tiếp nhận và đánh giá tình trạng bệnh nhân. 2. Nhận thấy ca bệnh có biểu hiện bất thường hoặc khó xác định. 3. Tìm kiếm tài liệu y khoa trên các nguồn chuyên ngành. 4. Đọc và chọn lọc các tài liệu liên quan. 5. Đối chiếu thông tin từ nhiều nguồn. 6. Tổng hợp thông tin để tham khảo trong quá trình đánh giá và xử trí. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: Tìm kiếm, đọc và đối chiếu nhiều tài liệu. Thời gian ước tính ban đầu: 30–60 phút/ca (giả định, cần khảo sát thực tế).                                                                                                                                                                                                 |
| Impact (nếu không giải thì sao)           | Bác sĩ mất nhiều thời gian nghiên cứu; có thể bỏ sót tài liệu liên quan hoặc khó tiếp cận thông tin cập nhật, làm chậm quá trình đánh giá ca bệnh.                                                                                                                                                                               |
| Success metric (baseline → target)        | Thời gian tìm kiếm và tổng hợp tài liệu: 30–60 phút → giảm ít nhất 30% (mục tiêu giả định). Ngoài ra: độ chính xác thông tin, mức độ liên quan của tài liệu và tỷ lệ câu trả lời có trích dẫn nguồn kiểm chứng được.                                                                                                             |
| Phương án không dùng AI                   | Xây dựng thư viện tài liệu y khoa được phân loại theo bệnh lý, chuyên khoa và từ khóa; sử dụng bộ lọc và mẫu tổng hợp tài liệu chuẩn hóa.                                                                                                                                                                                        |
| Giả thuyết về AI (nếu có)                 | Sử dụng RAG để tìm kiếm tài liệu từ nguồn y khoa đáng tin cậy, truy xuất các đoạn liên quan và tạo bản tổng hợp kèm trích dẫn để bác sĩ kiểm tra.                                                                                                                                                                                |
| Cảm nhận nhanh                            | Workflow (quy trình tìm kiếm, truy xuất và tổng hợp tài liệu có AI hỗ trợ).                                                                                                                                                                                                                                                      |

Quy trình nháp hiện tại:

```text
1. Bác sĩ tiếp nhận và đánh giá tình trạng bệnh nhân.
2. Bác sĩ nhận thấy ca bệnh có biểu hiện hiếm gặp hoặc bất thường.
3. Bác sĩ tìm kiếm tài liệu y khoa trên các nguồn chuyên ngành.
4. Bác sĩ đọc và chọn lọc những tài liệu liên quan.
5. Bác sĩ đối chiếu thông tin giữa các tài liệu.
6. Bác sĩ tổng hợp kiến thức để tham khảo trong quá trình đánh giá và xử trí ca bệnh.
```

### Problem Card #2

| Trường                                    | Nội dung                                                                                                                                                                                                                                                                                                                                |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi tiếp nhận bệnh nhân đã có nhiều lần khám trước đó, tôi muốn nhanh chóng nắm bắt toàn bộ tiền sử và diễn biến bệnh án, để tiết kiệm thời gian và đưa ra đánh giá phù hợp.                                                                                                                                                            |
| Actor                                     | Bác sĩ điều trị                                                                                                                                                                                                                                                                                                                         |
| Thời điểm / bối cảnh                      | Khi bệnh nhân tái khám, chuyển khoa hoặc được tiếp nhận tại bệnh viện mới.                                                                                                                                                                                                                                                              |
| Quy trình hiện tại (3–7 bước)             | 1. Bác sĩ tiếp nhận hồ sơ bệnh án. 2. Mở và xem lại hồ sơ từ những lần khám trước. 3. Đọc tiền sử bệnh, triệu chứng, kết quả xét nghiệm và chẩn đoán. 4. Đối chiếu thông tin giữa các lần khám. 5. Tổng hợp diễn biến bệnh và quá trình điều trị. 6. Sử dụng thông tin tổng hợp để đánh giá tình trạng hiện tại và đưa ra hướng xử trí. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: Đọc, đối chiếu và tổng hợp nhiều hồ sơ bệnh án. Thời gian ước tính: 15–30 phút/bệnh nhân (giả định, cần khảo sát thực tế).                                                                                                                                                                                                    |
| Impact (nếu không giải thì sao)           | Bác sĩ mất nhiều thời gian xem lại hồ sơ; có thể bỏ sót thông tin quan trọng, khó nắm bắt diễn biến bệnh và làm chậm quá trình khám chữa bệnh.                                                                                                                                                                                          |
| Success metric (baseline → target)        | Thời gian đọc và tổng hợp hồ sơ: 15–30 phút → giảm ít nhất 30% (mục tiêu giả định). Độ chính xác, độ đầy đủ của bản tóm tắt và tỷ lệ thông tin có thể truy xuất về hồ sơ gốc.                                                                                                                                                           |
| Phương án không dùng AI                   | Chuẩn hóa biểu mẫu bệnh án và xây dựng mẫu tóm tắt hồ sơ theo các mục: tiền sử, chẩn đoán, xét nghiệm, thuốc và quá trình điều trị.                                                                                                                                                                                                     |
| Giả thuyết về AI (nếu có)                 | Sử dụng LLM để đọc và tóm tắt hồ sơ bệnh án qua nhiều lần khám, trích xuất các thông tin quan trọng và sắp xếp theo dòng thời gian. Bác sĩ kiểm tra lại nội dung với hồ sơ gốc.                                                                                                                                                         |
| Cảm nhận nhanh                            | Workflow (quy trình tóm tắt hồ sơ có AI hỗ trợ).                                                                                                                                                                                                                                                                                        |

Quy trình nháp hiện tại:

```text
1. Bác sĩ tiếp nhận hồ sơ bệnh án của bệnh nhân.
2. Bác sĩ mở và xem lại các hồ sơ từ những lần khám trước.
3. Bác sĩ đọc thông tin về tiền sử bệnh, triệu chứng, kết quả xét nghiệm và chẩn đoán.
4. Bác sĩ đối chiếu thông tin giữa các lần khám.
5. Bác sĩ tổng hợp diễn biến bệnh và quá trình điều trị.
6. Bác sĩ sử dụng thông tin tổng hợp để đánh giá tình trạng hiện tại và đưa ra hướng xử trí.
```

### Problem Card #3

| Trường                                    | Nội dung                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi phải đọc và đánh giá nhiều ảnh X-quang trong ngày, tôi muốn nhanh chóng nhận diện những vùng phổi có dấu hiệu bất thường, để giảm nguy cơ bỏ sót dấu hiệu nghi ngờ viêm phổi và đưa ra đánh giá kịp thời.                                                                                                                                                                                     |
| Actor                                     | Bác sĩ chẩn đoán hình ảnh                                                                                                                                                                                                                                                                                                                                                                         |
| Thời điểm / bối cảnh                      | Hằng ngày, khi bác sĩ tiếp nhận và phân tích ảnh X-quang ngực của bệnh nhân.                                                                                                                                                                                                                                                                                                                      |
| Quy trình hiện tại (3–7 bước)             | 1. Bệnh nhân được chỉ định chụp X-quang ngực. 2. Hình ảnh được chuyển đến hệ thống để bác sĩ xem xét. 3. Bác sĩ quan sát và phân tích các vùng phổi. 4. Bác sĩ xác định các dấu hiệu bất thường, bao gồm dấu hiệu nghi ngờ viêm phổi. 5. Bác sĩ ghi nhận kết quả và chuyển thông tin cho bác sĩ điều trị. 6. Bác sĩ điều trị kết hợp kết quả với tình trạng bệnh nhân để quyết định hướng xử trí. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: Quan sát và nhận diện các dấu hiệu bất thường trên ảnh X-quang. Thời gian ước tính: khoảng 30 phút/ca (giả định ban đầu, cần xác minh thực tế).                                                                                                                                                                                                                                         |
| Impact (nếu không giải thì sao)           | Bác sĩ có thể mất nhiều thời gian đọc ảnh, đặc biệt khi số lượng ca lớn; tăng nguy cơ bỏ sót các dấu hiệu bất thường và làm chậm quá trình đánh giá bệnh nhân.                                                                                                                                                                                                                                    |
| Success metric (baseline → target)        | Recall (Sensitivity), Precision, F1-score và thời gian đọc ảnh. Mục tiêu giả định: giảm ít nhất 20–30% thời gian đọc ảnh mà vẫn duy trì Recall ở mức cao. Cần xác định baseline và target bằng dữ liệu thực tế.                                                                                                                                                                                   |
| Phương án không dùng AI                   | Sử dụng checklist đọc X-quang chuẩn hóa, quy trình đọc ảnh hai lượt hoặc cơ chế bác sĩ thứ hai kiểm tra các ca nghi ngờ.                                                                                                                                                                                                                                                                          |
| Giả thuyết về AI (nếu có)                 | Sử dụng mô hình Computer Vision để phân tích ảnh X-quang, đánh dấu các vùng có dấu hiệu nghi ngờ viêm phổi và đưa ra cảnh báo hỗ trợ bác sĩ xem xét. AI không thay thế chẩn đoán của bác sĩ.                                                                                                                                                                                                      |
| Cảm nhận nhanh                            | Workflow (AI hỗ trợ phân tích ảnh và đánh dấu vùng nghi ngờ trong quy trình đọc X-quang).                                                                                                                                                                                                                                                                                                         |

Quy trình nháp hiện tại:

```text
1. Bệnh nhân được chỉ định chụp X-quang ngực.
2. Hình ảnh X-quang được chuyển đến hệ thống để bác sĩ xem xét.
3. Bác sĩ quan sát và phân tích các vùng phổi trên ảnh.
4. Bác sĩ xác định các dấu hiệu bất thường, bao gồm dấu hiệu nghi ngờ viêm phổi.
5. Bác sĩ ghi nhận kết quả và chuyển thông tin cho bác sĩ điều trị.
6. Bác sĩ điều trị kết hợp kết quả với tình trạng bệnh nhân để quyết định hướng xử trí.
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: RAG giúp bác sĩ tiếp cận nhanh các tài liệu y khoa đáng tin cậy, đặc biệt với những ca bệnh hiếm hoặc ít gặp, từ đó có thêm cơ sở tham khảo khi đánh giá và lựa chọn hướng xử trí.
- Câu hỏi muốn nhóm phản biện: Nhóm hỏi có bao nhiêu y bác sĩ sẽ dùng RAG để lấy thông tin về bệnh lạ khi mà họ được rèn luyện bài bản.

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                                                                                             | Đồng ý?         | Đã sửa gì                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- | -------------------------------------------------------------------------------------------------------- |
| Chưa chứng minh bác sĩ thực sự gặp khó khăn khi tìm kiếm thông tin về bệnh hiếm; bác sĩ đã được đào tạo chuyên môn và có thể sử dụng các nguồn y khoa hiện có. | Đồng ý một phần | Cần khảo sát bác sĩ về tần suất gặp ca bệnh hiếm, thời gian tìm kiếm tài liệu và mức độ hữu ích của RAG. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card         |                        |                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                   |
| Gom cluster / cây OST      |                        |                                  |
| Chọn candidate problem     |                        |                                  |
| Kiểm chứng / research      |                        |                                  |
| Quy trình nhóm             |                        |                                  |
| Problem Statement          |                        |                                  |
| Mức can thiệp AI           |                        |                                  |
| Quyết định                 |                        |                                  |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ------------------------------ | ---------------------- | ----------------- | -------------------------- | ----------------------------------- |
| CP1 Scan                       |                        |                   |                            |                                     |
| CP2 Problem Card               |                        |                   |                            |                                     |
| CP4 Research                   |                        |                   |                            |                                     |
| CP5 Quy trình                  |                        |                   |                            |                                     |
| CP5–6 Problem Statement        |                        |                   |                            |                                     |
| CP6 Mức can thiệp / quyết định |                        |                   |                            |                                     |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
