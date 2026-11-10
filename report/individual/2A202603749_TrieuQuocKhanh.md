# Báo cáo cá nhân — 2A202603749_TrieuQuocKhanh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Triệu Quốc Khánh
- MSSV: 2A202603749
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: I3
- Link repo nhóm: https://github.com/mKhaiTruong/K5-L3B-DAY02-I3-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                                       | Ai chịu ảnh hưởng?               | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                                                                      |
| --: | --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu đồ án tốt nghiệp, tôi muốn nắm nhanh nội dung chính của các bài báo liên quan, để biết hướng nào đã có người làm và hướng nào còn trống | Sinh viên làm đồ án              | 3 paper/tuần × khoảng 45 phút/paper, tức khoảng 135 phút/tuần                                                                                  |
|   2 | Lặp lại                           | Khi ứng tuyển thực tập hoặc việc làm, tôi muốn chỉnh CV cho khớp từng tin tuyển dụng, để không bị loại ở vòng lọc hồ sơ                             | Sinh viên năm cuối đi xin việc   | 5 CV/tuần × khoảng 13–18 phút/CV (riêng bước sửa CV 10–15 phút), tức khoảng 65–90 phút/tuần                                                    |
|   3 | Tốn thời gian                     | Khi nhiều môn có deadline trùng nhau, tôi muốn biết việc nào cần làm trước, để không nộp trễ bài quan trọng                                         | Sinh viên học nhiều môn cùng lúc | 4 deadline trùng trong 1 tuần; 2 lần nộp trễ trong tuần đó                                                                                     |
|   4 | Lặp lại                           | Khi tới cuối tháng, tôi muốn biết mình đã chi bao nhiêu và chi vào đâu, để không hết tiền trước kỳ nhận tiền                                        | Bản thân                         | Khoảng 80 giao dịch/tháng rải ở 3 nơi (2 app ngân hàng, 1 ví MoMo); mỗi cuối tháng mất khoảng 20 phút xem lại lịch sử; lặp lại 3 tháng gần đây |
|   5 | Lặp lại                           | Khi có hàng nhập kho, tôi muốn chép phiếu nhập vào hệ thống, để số tồn kho khớp với thực tế                                                         | Nhân viên nhập liệu, kế toán kho | 15 phiếu/tuần × khoảng 12 phút/phiếu, tức khoảng 180 phút (3 giờ)/tuần; khoảng 1 lần nhập sai/tháng                                            |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                           | Vì sao chọn                                                                                           | Điều còn chưa chắc                                                                       |
| ---: | --------------------------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
|    1 | Chép phiếu nhập kho (#5)          | Lặp lại hằng tuần, tốn nhiều thời gian nhất (khoảng 180 phút/tuần), quy trình các bước cố định, dễ vẽ | Lỗi nhập sai có gây thiệt hại đáng kể không; nhà cung cấp có gửi được file điện tử không |
|    2 | Tổng hợp chi tiêu cuối tháng (#4) | Lặp lại mỗi tháng, dữ liệu nằm rải ở 3 nơi, quy trình đơn giản dễ vẽ                                  | Impact nhỏ (khoảng 20 phút/tháng); chưa rõ hậu quả thật của việc không tổng hợp          |
|    3 | Chỉnh CV theo tin tuyển dụng (#2) | Lặp lại hằng tuần khi đi xin việc, tốn khoảng 65–90 phút/tuần, bước sửa CV là bước nghẽn rõ           | Chưa biết CV chỉnh có giúp qua vòng lọc nhiều hơn không                                  |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                                                |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi có hàng nhập kho, tôi muốn chép phiếu nhập giấy vào phần mềm MISA, để số tồn kho khớp với thực tế                                                                   |
| Actor                                     | Nhân viên nhập liệu phụ trách phiếu nhập kho                                                                                                                            |
| Thời điểm / bối cảnh                      | Mỗi khi hàng về kèm phiếu nhập giấy, khoảng 15 phiếu/tuần                                                                                                               |
| Quy trình hiện tại (3–7 bước)             | 1. Lấy phiếu giấy · 2. Mở MISA, tạo phiếu nhập mới · 3. Tìm mã hàng, gõ số lượng từng dòng, kiểm tra lại · 4. Lưu phiếu                                                 |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: tìm mã hàng + gõ số lượng + kiểm tra, khoảng 10 phút/phiếu (chiếm hơn 80% thời gian)                                                                            |
| Impact (nếu không giải thì sao)           | Khoảng 180 phút/tuần cho 1 người; khoảng 1 lần nhập sai/tháng làm lệch tồn kho, lỗi chỉ được phát hiện muộn khi kho đóng hàng hoặc khi khách nhận hàng                  |
| Success metric (baseline → target)        | Thời gian/phiếu từ khoảng 12 phút xuống dưới 6 phút; số lỗi bị phát hiện ở khâu đóng hàng hoặc khách nhận hàng từ 1/tháng xuống 0                                       |
| Phương án không dùng AI                   | Lập sẵn danh sách mã hàng hay nhập để tra nhanh; đề nghị nhà cung cấp gửi kèm file Excel để nhập vào MISA (nếu MISA hỗ trợ nhập từ Excel); dán mã vạch và dùng máy quét |
| Giả thuyết về AI (nếu có)                 | Chụp ảnh phiếu giấy, AI đọc và điền nháp các dòng hàng + số lượng; nhân viên đối chiếu từng dòng với phiếu trước khi lưu vào MISA                                       |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 12 phút/phiếu, 15 phiếu/tuần (khoảng 180 phút/tuần)

[1 Lấy phiếu giấy: 1'] → [2 Mở MISA, tạo phiếu mới: 1']
→ [3 Tìm mã hàng + gõ số lượng + kiểm tra: 10'] ← BOTTLENECK
→ [4 Lưu phiếu: 1']

Lỗi (khoảng 1 lần/tháng) chỉ được phát hiện muộn: kho đóng hàng / khách nhận hàng
```

### Problem Card #2

| Trường                                    | Nội dung                                                                                                                                                    |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi tới cuối tháng, tôi muốn biết mình đã chi tổng cộng bao nhiêu và chi vào đâu, để không hết tiền trước kỳ nhận tiền                                      |
| Actor                                     | Bản thân (sinh viên dùng ví MoMo liên kết 2 tài khoản ngân hàng MB và VietinBank)                                                                           |
| Thời điểm / bối cảnh                      | Cuối mỗi tháng; khoảng 80 giao dịch/tháng; thanh toán bằng MoMo trước, hết tiền thì MoMo lấy từ MB, MB hết thì sang VietinBank                              |
| Quy trình hiện tại (3–7 bước)             | 1. Mở MoMo xem lịch sử giao dịch · 2. Mở app MB xem lịch sử · 3. Mở app VietinBank xem lịch sử · 4. Cộng tổng các khoản chi                                 |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: cộng tổng từ 3 nguồn. Các khoản chuyển giữa MoMo và ngân hàng xuất hiện ở cả 2 nơi nên dễ tính trùng, cuối cùng không ra được con số tổng chắc chắn |
| Impact (nếu không giải thì sao)           | Mất khoảng 20 phút/tháng nhưng vẫn không biết tháng này đã tiêu hết bao nhiêu; không kiểm soát được chi tiêu, đã lặp lại 3 tháng gần đây                    |
| Success metric (baseline → target)        | Từ "không biết tổng chi" → biết được tổng chi tháng; thời gian tổng hợp từ khoảng 20 phút xuống dưới 5 phút                                                 |
| Phương án không dùng AI                   | Dùng tính năng thống kê chi tiêu có sẵn trong MoMo hoặc app ngân hàng (nếu có); gom thanh toán về 1 nguồn chính; ghi chi tiêu vào 1 file Excel mỗi tuần     |
| Giả thuyết về AI (nếu có)                 | Chưa thấy cần AI: dữ liệu đã có sẵn, chỉ cần cộng và loại trùng theo quy tắc cố định                                                                        |
| Cảm nhận nhanh                            | No AI / Rule                                                                                                                                                |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 20 phút/tháng, khoảng 80 giao dịch/tháng

[1 Mở MoMo xem lịch sử: khoảng 5'] → [2 Mở MB xem lịch sử: khoảng 5']
→ [3 Mở VietinBank xem lịch sử: khoảng 5']
→ [4 Cộng tổng từ 3 nguồn: khoảng 5'] ← BOTTLENECK (dễ tính trùng khoản chuyển giữa MoMo và ngân hàng)

Kết quả: vẫn không biết chắc tổng chi tháng
```

### Problem Card #3

| Trường                                    | Nội dung                                                                                                                                                   |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi ứng tuyển thực tập hoặc việc làm, tôi muốn chỉnh CV cho khớp từng tin tuyển dụng, để không bị loại ở vòng lọc hồ sơ                                    |
| Actor                                     | Sinh viên năm cuối đang ứng tuyển vị trí thực tập / việc làm                                                                                               |
| Thời điểm / bối cảnh                      | Mỗi khi gửi hồ sơ, khoảng 5 CV/tuần                                                                                                                        |
| Quy trình hiện tại (3–7 bước)             | 1. Đọc tin tuyển dụng · 2. So yêu cầu với CV hiện tại · 3. Sửa CV theo yêu cầu nhà tuyển dụng · 4. Xuất PDF · 5. Gửi                                       |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: sửa CV theo yêu cầu, khoảng 10–15 phút/lần, chiếm phần lớn thời gian của cả quy trình                                                              |
| Impact (nếu không giải thì sao)           | Khoảng 65–90 phút/tuần; CV không khớp yêu cầu dễ bị loại ở vòng lọc hồ sơ; hiện 5 CV/tuần nhận 2 email phản hồi, 0 lời mời phỏng vấn                       |
| Success metric (baseline → target)        | Thời gian sửa CV từ khoảng 10–15 phút xuống dưới 5 phút/CV; số lời mời phỏng vấn từ 0/5 CV/tuần lên ít nhất 1/5 CV/tuần                                    |
| Phương án không dùng AI                   | Chuẩn bị sẵn CV gốc với các khối dự án/kỹ năng theo từng nhóm vị trí, mỗi lần chỉ chọn khối phù hợp; lập checklist từ khóa thường gặp trong tin tuyển dụng |
| Giả thuyết về AI (nếu có)                 | AI so tin tuyển dụng với CV, chỉ ra kỹ năng hoặc từ khóa còn thiếu; tôi tự quyết định sửa gì, không để AI tự viết thêm kinh nghiệm không có thật           |
| Cảm nhận nhanh                            | No AI / Workflow                                                                                                                                           |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 13–18 phút/CV, 5 CV/tuần (khoảng 65–90 phút/tuần)

[1 Đọc tin tuyển dụng: khoảng 1'] → [2 So với CV: khoảng 1']
→ [3 Sửa CV theo yêu cầu: 10–15'] ← BOTTLENECK
→ [4 Xuất PDF: khoảng 0,5'] → [5 Gửi: khoảng 0,5']
```

### Card muốn pitch nhất

- Card số: 1 (Chép phiếu nhập kho vào MISA)
- Vì sao: tốn nhiều thời gian nhất (khoảng 180 phút/tuần), lặp lại đều, có lỗi thật (khoảng 1 lần/tháng bị phát hiện muộn), quy trình rõ để so sánh No AI / Rule / Workflow / Agent
- Câu hỏi muốn nhóm phản biện: Nếu nhà cung cấp gửi được file Excel để nhập thẳng vào MISA thì còn cần AI đọc phiếu giấy không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                                   | Đồng ý?         | Đã sửa gì                                                                                                                                   |
| ---------------------------------------------------------------------------------------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Baseline 12 phút/phiếu chỉ ước lượng từ trí nhớ; phiếu ít dòng và nhiều dòng tốn thời gian khác nhau | Đồng ý          | Ghi rõ "khoảng" trong card; sẽ bấm giờ thật một số phiếu để có baseline chính xác trước khi đưa vào Problem Statement                       |
| 1 lần sai/tháng là ít; chưa rõ thiệt hại của mỗi lần sai                                             | Đồng ý một phần | Giữ lỗi trong Impact nhưng xác định impact chính là thời gian; đưa "mức thiệt hại khi nhập sai" vào danh sách giả định cần kiểm chứng ở CP4 |
| Giả thuyết AI đọc phiếu giấy có thể đọc sai số lượng, tạo ra đúng loại lỗi đang muốn tránh           | Đồng ý          | Thêm vào giả thuyết AI: nhân viên đối chiếu từng dòng với phiếu trước khi lưu                                                               |
| Chưa kiểm phương án đơn giản nhất: MISA có tra mã nhanh hoặc nhập từ Excel không                     | Đồng ý          | Giữ "nhập từ Excel" và "mã vạch" trong phương án không dùng AI; đặt thành câu hỏi phản biện cho nhóm và kiểm lại ở CP4                      |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Kết quả / ảnh hưởng tới bài nhóm                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pitch Problem Card         | Pitch Card #1: chép phiếu nhập kho vào MISA (khoảng 15 phiếu/tuần × 12 phút, khoảng 180 phút/tuần; khoảng 1 lần nhập sai/tháng). Câu hỏi nhờ nhóm phản biện: nếu nhà cung cấp gửi được file Excel để nhập thẳng vào MISA thì còn cần AI đọc phiếu giấy không?                                                                                                                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:<br>(1) #4 Quản lý việc và deadline phân tán (Trịnh Tuấn Phong): "Tháng vừa rồi bạn bỏ sót mấy deadline? Sót vì không biết hạn hay vì không kịp làm?"<br>(2) #7 Employee Onboarding Tracker (Nguyễn Đình Nam): "Đã có Excel, phần mềm nhân sự hoặc nhắc việc tự động chưa, và nó thiếu gì?"<br>(3) #9 Vendor Invoice Reconciliation (Nguyễn Đình Nam): "Phần mềm kế toán công ty đã có sẵn chức năng đối chiếu hóa đơn chưa?"                                                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được:<br>(1) #10 (Trịnh Tuấn Phong): thời gian mất ở gõ số lượng hay tìm mã hàng; nếu chuẩn hóa danh mục, quét barcode hoặc điền sẵn từ PO (rule) thì đã giải được 80% chưa?<br>(2) #11 (Trịnh Tuấn Phong): các khoản chuyển MoMo và ngân hàng khác nhau ở đâu; nếu một rule khớp cặp giao dịch là loại được trùng thì phần nào buộc phải dùng AI?<br>(3) #12 (Trương Đặng Minh Khuê): AI sửa CV có làm nội dung thiếu cá nhân hóa, giống CV hàng loạt, và giảm đánh giá của HR không? | Tôi đã sửa gì: Chưa sửa nội dung card #10. Đổi một phần cách nhìn: không còn coi AI đọc phiếu là cách duy nhất.                                                                                                                                                                                                                                                                                                                                                                  |
| Gom cluster / cây OST      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Chọn candidate problem     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Kiểm chứng / research      | Phỏng vấn 1 người làm khâu kiểm tra hóa đơn (vai trò: chăm sóc khách hàng, đảm nhận cả kiểm tra hóa đơn) và gửi kết quả vào nhóm.                                                                                                                                                                                                                                                                                                                                                                       | Kết quả: 5 phút/hóa đơn × 15 hóa đơn/tuần (75 phút/tuần); bước tốn thời gian và dễ sai nhất là so lô/hạn dùng; MISA không tự đối chiếu, mọi bước làm thủ công; khi sai lệch (lô/hạn dùng, chênh nhẹ số lượng/đơn giá) công việc ngưng để đối soát với kho/nhà cung cấp, làm biên bản hoặc điều chỉnh hóa đơn rồi mới nhập MISA và thanh toán. Xác nhận giả định sai lệch gây chậm thanh toán; lệch với giả định của nhóm về bottleneck (mã, số lượng, đơn giá). Mẫu chỉ 1 người. |
| Quy trình nhóm             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Problem Statement          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Mức can thiệp AI           |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Quyết định                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                                                                                      | AI hữu ích ở đâu?                                                                                                                                                                         | AI sai hoặc hời hợt ở đâu?                                                                                      | Tôi sửa gì bằng nhận định của mình?                                                                                                                               |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CP1 Scan                       |                                                                                                             |                                                                                                                                                                                           |                                                                                                                 |                                                                                                                                                                   |
| CP2 Problem Card               | Nhờ AI phản biện Card #1 (bảng "AI đã phản biện card thế nào" ở mục 3)                                      | Chỉ ra 4 điểm yếu: baseline 12 phút chỉ là ước lượng; 1 lỗi/tháng là ít, chưa rõ thiệt hại; AI đọc phiếu có thể đọc sai số lượng; chưa kiểm phương án đơn giản (MISA nhập Excel, mã vạch) | Chỉ đồng ý một phần ở điểm "1 lỗi/tháng là ít", vì impact chính của card là thời gian chứ không phải số lần lỗi | Ghi "khoảng" cho baseline; thêm bước nhân viên đối chiếu từng dòng vào giả thuyết AI; đưa mức thiệt hại và phương án Excel/mã vạch thành câu cần kiểm chứng ở CP4 |
| CP4 Research                   | Chỉ dùng AI để sắp xếp ghi chép sau phỏng vấn thành bảng snapshot; không dùng AI để hỏi hay tạo câu trả lời | Phát hiện câu trả lời đánh số lệch với 5 câu hỏi và thiếu câu 5; chỉ ra bottleneck người được hỏi nêu khác giả định của nhóm                                                              | Chưa thấy AI sai ở bước này; AI không có số liệu về tần suất sai lệch nên chỉ gợi ý hỏi thêm                    | Hỏi lại người được phỏng vấn để bổ sung câu 5 trước khi gửi nhóm                                                                                                  |
| CP5 Quy trình                  |                                                                                                             |                                                                                                                                                                                           |                                                                                                                 |                                                                                                                                                                   |
| CP5–6 Problem Statement        |                                                                                                             |                                                                                                                                                                                           |                                                                                                                 |                                                                                                                                                                   |
| CP6 Mức can thiệp / quyết định |                                                                                                             |                                                                                                                                                                                           |                                                                                                                 |                                                                                                                                                                   |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Sau khi nghe top 3 problem của các thành viên trong nhóm, em nhận ra điểm chung của problem là nhiều card dùng đối chiếu, tổng hợp nhiều nguồn thủ công.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, nhóm phải loại bỏ AI đọc phiếu, OCR, dashboard vì là solution đội lốt opportunity.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Trước khi Phong hỏi, em nghĩ nút thắt của card #10 là tìm mã, gõ số lượng. Câu hỏi của Phong đã tách bước đó thành mất thời gian ở gõ số lượng hay tìm đúng mã hàng, điều mà em chưa phân biệt được. Em đổi ý ở chỗ nghi ngờ AI đọc phiếu là cách duy nhất. Sau đó em hỏi trực tiếp người làm việc đó để đối chiếu và kiểm chứng.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Trước khi phỏng vấn, nhóm giả định bottleneck là so mã hàng, số lượng, đơn giá. Sau khi hỏi thì nhận ra bước tốn thời gian nhất là so lô và hạn dùng. Kết quả làm thay đổi suy nghĩ về cách sử dụng AI vào bài toán.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Vì em vẫn đang là sinh viên năm cuối, nên điều khó nhất khi viết Problem Statement là không biết việc gì khiến mình làm đi làm lại tốn thời gian nhất để viết, phải mất lúc lâu mới nghĩ ra được.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, em sẽ phản biện nhóm mạnh hơn vẫn là card 9. Theo em nghĩ thì trong công ty nếu chỉ có ít người đi công tác thì kế toán không mất nhiều thời gian để đối chiếu giấy tờ để hoàn tiền cho người được hỗ trợ công tác.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

Kế toán phải đối chiếu thủ công mã hàng giữa hóa đơn (Invoice), đơn đặt hàng (PO) và phiếu nhận hàng (GRN), tốn 10–20 phút với hóa đơn nhiều mặt hàng và dễ chậm thanh toán khi có sai lệch. Quy trình hiện tại có 6 bước, điểm nghẽn nằm ở bước đối chiếu Invoice với PO, Invoice với GRN và xử lý sai lệch (liên hệ mua hàng, kho, nhà cung cấp). Nhóm đo thành công bằng việc giảm ít nhất 30% thời gian đối chiếu. AI không được tự tạo dữ liệu còn thiếu, tự kết luận hóa đơn hợp lệ, tự duyệt hoặc thanh toán, và kế toán phải kiểm tra khi dữ liệu thiếu hoặc có sai lệch. Nhóm chọn mức Workflow gồm AI trích xuất, Rule đối chiếu, AI tóm tắt sai lệch, kế toán xác minh. Nhóm chọn Go phạm vi nhỏ, vì có bằng chứng ban đầu nhưng baseline và chức năng MISA/FAST chưa xác minh.

## 7. Tài liệu tham khảo

-
