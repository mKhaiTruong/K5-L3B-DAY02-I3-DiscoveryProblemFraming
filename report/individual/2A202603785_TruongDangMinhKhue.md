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

| Hoạt động                  | Tôi đã làm gì?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Kết quả / ảnh hưởng tới bài nhóm                                                                                                                                                                                                                                                                                                                     |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pitch Problem Card         | Tham gia xây dựng và trình bày các Problem Card, trong đó tập trung vào tác dụng của AI và cách AI hoạt động trong cards của teammates                                                                                                                                                                                                                                                                                                                                                                                                                        | Giúp nhóm mô tả vấn đề, xác định người dùng, quy trình và pain point ban đầu, dẫn đến lựa chọn cuối là Vendor Invoice Reconciliation.                                                                                                                                                                                                                |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (5) "Ông có chắc rằng việc đọc lại và tổng hợp 5 đến 8 nguồn tài liệu là một vấn đề phổ biến với sinh viên vừa đi học và làm chưa, hay đây chỉ là khó khăn từ thói quen ghi chú cá nhân? (8) Nếu việc kiểm tra chứng từ chỉ mất có khoảng 5 phút cho 1 lượt thôi thì tần suất phát sinh hồ sơ có đủ lớn để justify chi phí phát triển và vận hành AI không?" (12) "Việc sử dụng AI để chỉnh sửa CV có khiến nội dung trở nên thiếu tính cá nhân hóa, giống các CV được tạo hàng loạt và làm giảm đánh giá của HR đối với ứng viên không?" | Giúp các nhóm nhìn lại giả định về mức độ phổ biến của pain point, giá trị kinh tế và tác động đến người dùng.                                                                                                                                                                                                                                       |
| Nhận phản biện             | Câu hỏi tôi nhận được: Nguyễn Đình Nam đã hỏi tôi cả 3 câu rất hay về cả 3 card tôi chọn. Đại ý là về: với data nhạy cảm như data y tế, nếu AI làm sai (cung cấp tài liệu y khoa sai, tóm tắt sai hoặc bỏ sót thông tin, bỏ sót dấu hiệu viêm) thì tôi có cách xử lý nào không                                                                                                                                                                                                                                                                                | Tôi đã sửa gì: Tôi rà soát lại các Problem Card liên quan đến y tế, bổ sung rủi ro, đồng thời, làm rõ giới hạn của AI với nhóm: chỉ hỗ trợ tra cứu/tóm tắt hoặc đưa ra kết quả tham khảo, không thay thế quyết định của bác sĩ; các thông tin quan trọng cần được đối chiếu với nguồn y khoa đáng tin cậy và bác sĩ phải kiểm tra trước khi sử dụng. |
| Gom cluster / cây OST      | Tham gia tổng hợp các vấn đề được đề xuất, phân nhóm theo quy trình và pain point, xét duyệt diagram cuối                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Giúp nhóm nhìn hiểu các vấn đề có liên quan và chắc rằng diagram không bị lệch                                                                                                                                                                                                                                                                       |
| Chọn candidate problem     | Tham gia đánh giá và lựa chọn Vendor Invoice Reconciliation dựa trên actor, quy trình, mức độ đau, tác động và khả năng triển khai trong phạm vi lab.                                                                                                                                                                                                                                                                                                                                                                                                         | Nhóm thống nhất tập trung vào quy trình đối chiếu Invoice – PO – GRN trước khi thanh toán.                                                                                                                                                                                                                                                           |
| Kiểm chứng / research      | Thực hiện phỏng vấn và tổng hợp interview snapshots; tìm hiểu quy trình đối chiếu chứng từ, thời gian xử lý, cách làm hiện tại và các trường hợp sai lệch. Tham khảo thêm tài liệu MISA, FAST và công nghệ trích xuất chứng từ.                                                                                                                                                                                                                                                                                                                               | Bổ sung bằng chứng thực tế cho pain point: đối chiếu thủ công tốn thời gian, sai lệch chứng từ có thể làm chậm thanh toán. Đồng thời xác định các giả định cần kiểm chứng thêm.                                                                                                                                                                      |
| Quy trình nhóm             | Tham gia thống nhất format Problem Card, tổng hợp thông tin từ các thành viên và cập nhật nội dung vào báo cáo chung cuối, đồng thời hỗ trợ nhóm tạo branch riêng và merge individual reports                                                                                                                                                                                                                                                                                                                                                                 | Giúp thông tin giữa các thành viên được trình bày thống nhất và dễ so sánh.                                                                                                                                                                                                                                                                          |
| Problem Statement          | Tham gia xây dựng Problem Statement từ v0 đến v1, làm rõ actor, process, bottleneck, impact, success metrics và boundary.                                                                                                                                                                                                                                                                                                                                                                                                                                     | Chuyển mô tả vấn đề ban đầu thành bài toán cụ thể, có tiêu chí đánh giá và phạm vi rõ ràng hơn.                                                                                                                                                                                                                                                      |
| Mức can thiệp AI           | Phân tích các phương án No AI, Rule, Workflow và Agent; đề xuất Workflow kết hợp AI trích xuất dữ liệu, Rule đối chiếu và kế toán xác minh. Đồng thời nhờ AI làm rõ các bước cần làm                                                                                                                                                                                                                                                                                                                                                                          | Xác định Workflow là mức can thiệp phù hợp, tránh để AI tự quyết định tính hợp lệ hoặc phê duyệt thanh toán.                                                                                                                                                                                                                                         |
| Quyết định                 | Tham gia đánh giá, kiểm tra hầu hết mọi reports cũng như ý kiến của mọi người, nhằm đảm bảo final group report không bị loạn                                                                                                                                                                                                                                                                                                                                                                                                                                  | Xác định các rủi ro cần kiểm chứng và độ chính xác của việc trích xuất, đối chiếu chứng từ.                                                                                                                                                                                                                                                          |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                                                                                           | AI hữu ích ở đâu?                                                                             | AI sai hoặc hời hợt ở đâu?                                                                                                                                | Tôi sửa gì bằng nhận định của mình?                                                                                                                  |
| :----------------------------- | :--------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| CP1 Scan                       | Hỗ trợ brainstorm, phân tích và sắp xếp các vấn đề tiềm năng thành các nhóm pain point.                          | Đưa ra nhiều góc nhìn và giúp hệ thống hóa các vấn đề nhanh hơn.                              | Một số vấn đề còn chung chung, thiếu actor, bằng chứng thực tế hoặc ước lượng tác động.                                                                   | Đối chiếu với thông tin từ thành viên và phỏng vấn, loại bỏ các vấn đề thiếu cơ sở hoặc khó triển khai.                                              |
| CP2 Problem Card               | Hỗ trợ diễn đạt Problem Card, xác định actor, quy trình, pain point và impact.                                   | Giúp chuẩn hóa cách trình bày và phát hiện những thông tin còn thiếu.                         | Có xu hướng đưa ra giả định về thời gian, tần suất và mức độ ảnh hưởng khi chưa có dữ liệu.                                                               | Chỉ giữ lại thông tin có bằng chứng; đánh dấu những con số và giả định cần kiểm chứng thay vì xem chúng là sự thật.                                  |
| CP4 Research                   | Hỗ trợ tìm hiểu quy trình đối chiếu Invoice–PO–GRN, chức năng phần mềm kế toán và công nghệ trích xuất chứng từ. | Giúp định hướng nguồn nghiên cứu và hiểu thêm các công nghệ có thể áp dụng.                   | Thông tin về chức năng phần mềm có thể không tương ứng với phiên bản doanh nghiệp đang sử dụng; tài liệu kỹ thuật không chứng minh được hiệu quả thực tế. | Phân biệt thông tin từ tài liệu tham khảo với kết quả phỏng vấn; xác định việc kiểm tra chức năng MISA/FAST là giả định cần xác minh.                |
| CP5 Quy trình                  | Hỗ trợ mô tả quy trình AS-IS và đề xuất quy trình TO-BE.                                                         | Giúp phân tách các bước xử lý, xác định bottleneck và xây dựng workflow có AI, Rule và Human. | Đề xuất ban đầu có thể tự động hóa quá nhiều, chưa làm rõ trường hợp dữ liệu thiếu, sai hoặc không đọc được.                                              | Bổ sung bước kiểm tra thủ công, xử lý ngoại lệ và giữ quyền xác minh cuối cùng cho kế toán.                                                          |
| CP5–6 Problem Statement        | Hỗ trợ viết và cải thiện Problem Statement v0 → v1, xác định success metrics và boundary.                        | Giúp chuyển mô tả vấn đề thành bài toán cụ thể, có tiêu chí đánh giá và phạm vi rõ ràng.      | Một số chỉ tiêu như giảm 30% thời gian và độ chính xác 95% có thể mang tính tùy ý nếu chưa có baseline và dữ liệu thử nghiệm.                             | Xem các chỉ tiêu là mục tiêu đề xuất cho pilot, phân biệt extraction accuracy với khả năng phát hiện sai lệch và bổ sung điều kiện đánh giá thực tế. |
| CP6 Mức can thiệp / quyết định | Hỗ trợ so sánh No AI, Rule, Workflow và Agent; đánh giá Value, Usability, Feasibility, Viability.                | Giúp hệ thống hóa ưu nhược điểm của từng mức can thiệp và các rủi ro triển khai.              | Có thể đánh giá quá lạc quan về tính khả thi và giá trị khi chưa xác minh phần mềm hiện tại, chất lượng dữ liệu và chi phí triển khai.                    | Giúp chọn Workflow kết hợp AI + Rule + Human; đề xuất Conditional Go với pilot nhỏ thay vì triển khai rộng ngay lập tức.                             |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

- Rằng các problems liên quan đến dữ liệu người dùng ngày càng cần được ứng dụng. Ngoài ra, tôi nghĩ bài toán y tế là cần thiết nên có thể sẽ được đánh giá là cần thiết nhưng rốt cuộc nó chưa phải là pain point đủ lớn và chi phí cũng đắt đỏ để ứng dụng.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

- Có, nhóm đã nghĩ đến việc dùng AI để đọc và đối chiếu hóa đơn trong lúc đang thảo luận từ khá sớm. Sau đó chúng tôi chậm lại và làm rõ: kế toán đang check chứng từ nào, đối chiếu thông tin gì và bước nào thực sự tốn thời gian. Nhóm quay lại xác định bằng cách thu thập thông tin qua phỏng vấn và sau đó mới thiết kế. Solution lúc này được thu nhỏ thành AI trích xuất dữ liệu, có đầy đủ rules đối chiếu và con người xác minh.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

- Có. Khi bị phản biện cards liên quan đến y tế, về AI cung cấp tài liệu y khoa sai, tóm tắt thiếu thông tin hoặc bỏ sót dấu hiệu bệnh, hay liệu problem này có thật sự phổ biến hay không. Tôi phải nhấn mạnh vai trò HỖ TRỢ của AI, yêu cầu kiểm tra thông tin liên quan và bác sĩ sẽ đưa ra quyết định cuối cùng, nhưng về vấn đề phổ biến phải tùy vào đất nước văn hóa.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

- Có. Tôi nhận thấy thời gian kiểm tra chứng từ không cố định như một con số chung. Có trường hợp đơn giản chỉ mất vài phút, nhưng khi có nhiều mặt hàng hoặc sai lệch thì có thể kéo dài từ 30 phút đến vài giờ. Một cuộc phỏng vấn khác ghi nhận khoảng 10 phút cho một hóa đơn, trong đó phần tốn thời gian nhất là đối chiếu hợp đồng, báo giá và nghiệm thu. Điều này cho thấy độ phức tạp của chứng từ và trường hợp sai lệch quan trọng hơn việc chỉ lấy một con số thời gian trung bình.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

- Theo tôi, khó nhất là làm sao để những thông tin phỏng vấn rời rạc tạo thành một vấn đề cụ thể, xong khi đã xác định được vấn đề, vấn đề có thật sự đúng hướng hay không. Ngoài ra, việc chọn success metrics cũng khó vì thời gian xử lý giữa các loại hóa đơn khác nhau và domain knowledge của chúng tôi không quá sâu.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

- Nếu làm lại, tôi cần phải đọc bài kĩ hơn vì làm bài lab này quá mất thời gian, bằng cách xác định rõ hơn vai trò của từng người và làm sao để mục thảo luận problem mượt mà hơn. Tôi cũng phải hiểu context và tác dụng của AI để giúp phản biện tốt hơn, hiểu solution và opportunity giúp phân biệt các problem dễ dàng hơn nhiều.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

- Problem nhóm tôi chọn là Vendor Invoice Reconciliation: hỗ trợ kế toán đối chiếu hóa đơn với đơn đặt hàng và phiếu nhận hàng trước khi thanh toán. Quy trình hiện tại khá lằng nhằng, phải yêu cầu kế toán kiểm tra mã hàng, tên hàng, số lượng, đơn giá và thành tiền trên nhiều chứng từ. Những step thủ công ở trên cộng với việc đối chiếu và xử lý sai lệch là bottleneck chính. Đề xuất là (1) đo thời gian xử lý và độ chính xác trích xuất thông tin, (2) khả năng phát hiện saii lệch. Về Giải pháp thì phải đảm bảo AI không được phép tự tạo dữ liệu còn thiếu, cũng không được phép tự kết luận như tính hợp lệ hoặc phê duyệt thanh toán. Kế toán vẫn phải là người chịu trách nhiệm dùng tool. Nhóm chọn mức 'Workflow', trong đó AI trích xuất thông tin, cùng với ruleset thực hiện đối chiếu theo quy tắc và HITL, tức là người ở giữa, kiểm tra các trường hợp bất thường. Nhóm quyết định Conditional Go, nhưng phải xác minh khả năng của phần mềm kế toán hiện tại có đủ ổn hay không trước khi mở rộng.

---

## 7. Tài liệu tham khảo

### 7.1. Tài liệu và nguồn nghiên cứu bên ngoài

1. Microsoft. (n.d.). _Invoice data extraction – Azure AI Document Intelligence_. Microsoft Learn. https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/prebuilt/invoice?view=doc-intel-4.0.0

2. MISA. (n.d.). _Mua hàng – AMIS Kế toán_. Trung tâm trợ giúp MISA. https://helpact.misa.vn/ac/mua-hang/

3. FAST. (2025). _Nhập mua hàng – FAST Accounting 12_. FAST Help. https://fa12help.fast.com.vn/index.php/fa12help/nhap-mua-hang/

4. FAST. (n.d.). _Chi phí mua hàng – FAST Accounting Online_. FAST Help. https://help.faonline.vn/faohelp/chi-phi-mua-hang/

### 7.2. Nguồn dữ liệu tự thu thập

5. Phỏng vấn người dùng tiềm năng về quy trình kiểm tra và đối chiếu chứng từ (2026). Interview snapshots do nhóm thực hiện.
