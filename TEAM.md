# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: I3
- Candidate problem nhóm chọn (1 câu): Vendor Invoice Reconciliation — kế toán mất 3–5 phút/hóa đơn (10–20 phút nếu nhiều mặt hàng) để đối chiếu thủ công mã hàng, số lượng, đơn giá giữa Invoice, PO và GRN; nhóm thu hẹp vào bước đối chiếu và xử lý sai lệch.
- Quyết định cuối (Go / Not Yet / No-Go): Go — pilot nhỏ

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Trịnh Tuấn Phong | 2A202603781 | Phản biện chính, nghiên cứu problem | trinhtuanphong123 |
| 2 | Trương Đặng Minh Khuê | 2A202603785 | Điều phối thời gian, ghi chép, phụ trách research | mKhaiTruong |
| 3 | Nguyễn Đình Nam | 2A202603797 | Viết Problem Statement | dinhnam269 |
| 4 | Triệu Quốc Khánh | 2A202603749 | Phụ trách kiểm chứng, vẽ quy trình | qockhah253 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Trương Đặng Minh Khuê | Trịnh Tuấn Phong, Nguyễn Đình Nam, Triệu Quốc Khánh | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Triệu Quốc Khánh | Trịnh Tuấn Phong, Trương Đặng Minh Khuê | Assumption map, 4 interview snapshot |
| CP4 — Research | Trương Đặng Minh Khuê | Nguyễn Đình Nam | Bảng research 4 công cụ (MISA AMIS, MISA ASP, FAST, Dynamics 365 three-way matching) |
| CP5 — Quy trình trước/sau | Triệu Quốc Khánh | Nguyễn Đình Nam | Quy trình 6 bước + bảng before/after |
| CP5 — Problem Statement v0 | Nguyễn Đình Nam | Trịnh Tuấn Phong | Problem Statement v0 (mục 5) |
| CP6 — Mức can thiệp + Problem Statement v1 | Triệu Quốc Khánh | Trịnh Tuấn Phong | Ma trận, AI Canvas, tiêu chí đánh giá, Problem Statement v1 (mục 6–7) |
| CP6 — Quyết định | Trương Đặng Minh Khuê | Cả nhóm | 4 rủi ro + Go/Not Yet/No-Go (mục 8) |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### TruongDangMinhKhue-2A202603785

**Phần việc phụ trách:**

- Nhóm trưởng: fork repo nhóm, mời thành viên làm collaborator, điều phối nhóm qua CP3–CP6.
- Phụ trách research giải pháp đã có (CP4).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 card #1–#3 (Medical Knowledge Retrieval, Medical Record Summarization, Pneumonia Detection on X-ray) để nhóm có thêm lựa chọn trước khi chọn bài.
- Phỏng vấn 1 kế toán công ty đang dùng phần mềm FAST: đã từng phải hủy chứng từ và làm lại khi phát hiện sai lệch; vẫn có thao tác nhập dữ liệu và diễn giải nội dung thủ công (Interview snapshot 1).
- Research 4 giải pháp đã có (MISA AMIS Kế toán, MISA ASP, FAST Accounting, Microsoft Dynamics 365 three-way matching) và chỉ ra khoảng trống: chưa xác minh được khả năng tự động matching 3 bên theo từng dòng hàng (mục 3.3).
- Điều phối gom 12 candidate thành 4 cluster, chốt outcome của cây OST và bảng chấm điểm shortlist (mục 2.2–2.4).

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #1–#3), 2.2–2.4, 3.2 (Interview snapshot 1), 3.3.
- Repo nhóm `mKhaiTruong/K5-L3B-DAY02-I3-DiscoveryProblemFraming`.

**Điều mình học được từ phần nhóm:**

- Học hỏi thêm kinh nghiệm trao đổi giữa các thành viên.


### TrinhTuanPhong-2A202603781

**Phần việc phụ trách:**

- Phản biện chính của nhóm; nghiên cứu problem và tìm giải pháp đã có.
- Phỏng vấn 2 trong 4 người được phỏng vấn ở CP4.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 card #4–#6 (Quản lý việc và deadline phân tán, Đọc tài liệu dài và tổng hợp, Soạn trả lời tin nhắn/email), nêu hậu quả đếm được (2 lần lỡ hẹn trong 2 tháng) thay vì chỉ nói mất thời gian.
- Đặt 2 câu phản biện cho #10 và #11: tách "tìm/khớp mã hàng" khỏi "gõ số lượng"; và hỏi rule khớp cặp giao dịch đối ứng đã đủ chưa — giúp nhóm thấy hai card này dừng ở mức Rule.
- Phỏng vấn 2 người làm chứng từ (Interview snapshot 3–4): xác nhận đối chiếu Invoice–PO–GRN là bottleneck; 3–5 phút/hóa đơn đơn giản, 10–20 phút khi nhiều mặt hàng, 30 phút đến vài giờ khi có sai lệch.
- Research trợ lý cá nhân đã có trên thị trường (Grok Bot của xAI, Meta Muse) kèm link nguồn, dùng để đặt câu hỏi "khác gì họ" và giới hạn kỳ vọng về mức can thiệp AI.
- Rà Boundary và Success Metric của Problem Statement để tách rõ "vấn đề" khỏi "giả thuyết giải pháp" (mục 5, 7).

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #4–#6, câu hỏi phản biện cho #10/#11), 3.2 (Interview snapshot 3–4), 5, 7.
- `report/individual/2A202603781_TrinhTuanPhong.md` mục 2–5, 7.
- Commit trên nhánh `trinhtuanphong`.

**Điều mình học được từ phần nhóm:**

- Phải đo baseline trước khi viết card — con số ước lượng không đủ để bảo vệ bài khi bị hỏi ngược.
- Research xem thị trường đã có gì trước khi vẽ giải pháp, thay vì tưởng mình là người đầu tiên.
- Câu hỏi mạnh nhất khi phản biện một candidate là "nếu bỏ AI đi thì vấn đề còn lại là gì".

### NguyenDinhNam-2A202603797

**Phần việc phụ trách:**

- Viết Problem Statement v0 và v1 (CP5–CP6).
- Pitch candidate mà nhóm chọn (#9).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 card #7–#9 (Employee Onboarding Tracker, Travel Expense Claim Check, Vendor Invoice Reconciliation); #9 được nhóm chọn vì actor rõ và baseline tách được theo bước (2 phút đối chiếu trên 5 phút/hóa đơn).
- Viết Problem Statement v0 (mục 5) và v1 (mục 7) đủ 9 trường, kèm bộ 5 tiêu chí đánh giá đầu ra.
- Đề xuất mức Workflow: AI trích xuất → Rule đối chiếu → AI tóm tắt sai lệch → kế toán xác minh; ghi boundary không tự tạo dữ liệu, không tự kết luận hóa đơn hợp lệ, không tự duyệt/thanh toán.
- Xử lý phản biện "phần mềm kế toán đã có chức năng đối chiếu chưa" bằng hướng khảo sát MISA/FAST ở cấp từng mặt hàng trước khi triển khai.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #7–#9), 5, 6.2–6.4, 7 (Problem Statement v1 + tiêu chí đánh giá).

**Điều mình học được từ phần nhóm:**

- Problem tốt phải chỉ ra dữ liệu nằm ở đâu và bước nào template là đủ, trước khi nghĩ tới AI.


### TrieuQuocKhanh-2A202603749

**Phần việc phụ trách:**

- Phụ trách kiểm chứng (CP4) và vẽ quy trình trước/sau (CP5).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 card #10–#12 (Inventory Receipt Entry, Monthly Spending Summary, CV Tailoring).
- Phỏng vấn 1 nhân viên chăm sóc khách hàng đang dùng MISA: khoảng 5 phút/hóa đơn, 15 hóa đơn/tuần; bước kiểm tra lô và hạn dùng vẫn phải làm thủ công (Interview snapshot 2).
- Đặt câu hỏi then chốt cho #9: "Phần mềm kế toán công ty đã có sẵn chức năng đối chiếu hóa đơn chưa?" — buộc nhóm research MISA/FAST trước khi chọn giải pháp (mục 3.3).
- Vẽ quy trình hiện tại 6 bước và quy trình tương lai, lập bảng before/after (mục 4.1–4.3).

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #10–#12, câu hỏi ở #9), 3.2 (Interview snapshot 2), 3.3, 4.1–4.3, 5.

**Điều mình học được từ phần nhóm:**

- Hiểu rõ vấn đề, thực hiện phân tích chuyên sâu, phát biểu lại bài toán một các dễ hiểu hơn, hiểu xem tại sao nên áp dụng AI vào bài toán.
