# [IT-206-K25] Báo cáo Bài tập 1 - Session 9: Nhận diện và sửa kế hoạch Sprint Review

> 👤 **Học viên:** Hoàng Công Dũng | **Mã SV:** PTIT-HCM-009
> 🏫 **Môn học:** it206-k25-HoangCongDung

---

## Phần 1 - Rà kế hoạch

Sau khi kiểm tra kế hoạch Sprint Review hiện tại của RikkeiAssist, em nhận thấy có nhiều điểm chưa phù hợp với tinh thần của Scrum Guide. Cụ thể, buổi họp đang bị biến thành một buổi báo cáo tiến độ và nghiệm thu hành chính thay vì là buổi trao đổi hai chiều để kiểm tra kết quả và thích ứng.

Dưới đây là bảng phân tích chi tiết từng mục trong kế hoạch hiện tại, căn cứ theo các quy tắc nghiệp vụ (QT1 - QT4) và cách sửa lại cho đúng chuẩn:

- Hành trình demo PBI-41: Khách hàng truy cập website của cửa hàng -> Nhập mã đơn hàng vào khung chat hoặc ô tra cứu -> Hệ thống trả về trạng thái đơn hàng chính xác lấy từ cơ sở dữ liệu thử nghiệm.
- Câu hỏi mở cho Stakeholders: 'Anh/chị có góp ý gì về tốc độ phản hồi của tính năng tra cứu đơn hàng và mức độ rõ ràng của thông tin hiển thị không?'
- Cách ghi nhận Feedback: Product Owner ghi nhận toàn bộ ý kiến vào Product Backlog, không cam kết đưa vào Sprint kế tiếp ngay lập tức.

| Mã | Phù hợp / Chưa phù hợp | Quy tắc làm căn cứ | Cách sửa ngắn gọn cho K-01 đến K-04 |
| --- | --- | --- | --- |
| K-01 | Phù hợp | QT1 | Giữ nguyên: Product Owner nhắc lại Sprint Goal để mọi người nhớ mục tiêu trọng tâm của Sprint. |
| K-02 | Chưa phù hợp | QT1 | Sửa lại: Không báo cáo phần trăm hoàn thành hay giải thích lý do nhóm bận. Thay vào đó, Developers trực tiếp trình bày các PBI đã hoàn thành và chia sẻ thực tế kỹ thuật. |
| K-03 | Chưa phù hợp | QT2 | Sửa lại: Chỉ trình bày và demo PBI-41 (đã Done). PBI-42 và PBI-44 chưa Done tuyệt đối không được giới thiệu là Increment. Hành trình demo User Journey cho PBI-41: Khách hàng vào website RikkeiAssist -> gõ từ khóa 'tra cứu đơn hàng' -> hệ thống hiển thị chính xác trạng thái đơn hàng thời gian thực. |
| K-04 | Chưa phù hợp | QT3, QT4 | Sửa lại: Bỏ việc chủ cửa hàng nghiệm thu toàn bộ. Chuyển sang trao đổi hai chiều với câu hỏi mở: 'Anh/chị đánh giá như thế nào về tính năng tra cứu đơn hàng trên web, và trải nghiệm này đã giúp giảm tải cho nhân viên cửa hàng chưa?'. Mọi Feedback được ghi nhận vào Product Backlog để PO cân nhắc, không hứa làm ngay. |

## Phần 2 - Trạng thái PBI

Việc minh bạch trạng thái của từng Product Backlog Item là cốt lõi của Sprint Review. Căn cứ theo điều kiện Done (chạy trên môi trường thử nghiệm, hoàn thành kiểm thử chính và không còn lỗi mức nghiêm trọng cao), em phân loại 3 PBI của Sprint 11 như sau:

- Điều kiện Done được áp dụng nghiêm ngặt dựa trên tiêu chí kỹ thuật thực tế.
- PBI chưa Done được công bố minh bạch bằng số liệu kiểm thử cụ thể, thể hiện tính chuyên nghiệp của Scrum Team.

| PBI | Done / Chưa Done | Câu thông báo trong Sprint Review |
| --- | --- | --- |
| PBI-41 | Done | PBI-41 về tra cứu trạng thái đơn trên website đã hoàn tất việc chạy thử nghiệm, đạt 60/60 ca kiểm thử và không còn lỗi nghiêm trọng. Nhóm xin phép được demo tính năng này ngay bây giờ. |
| PBI-42 | Chưa Done | PBI-42 tra cứu trạng thái đơn từ mạng xã hội chưa được xem là Done vì vẫn còn 4 ca kiểm thử lỗi dịch vụ đơn hàng chưa đạt. Nhóm đang tiếp tục khắc phục ở Sprint sau. |
| PBI-44 | Chưa Done | PBI-44 nhận diện khiếu nại nghiêm trọng chưa được xem là Done vì còn 1 lỗi mức nghiêm trọng cao và 6/80 ca bị phân loại sai. Nhóm sẽ hoàn thiện trước khi đưa vào sản phẩm chính thức. |

## Phần 3 - Xử lý tình huống

Dựa trên các bẫy dữ liệu và ràng buộc của đề bài, em xin trả lời Product Owner như sau:

1. Về việc giấu dữ liệu: 'PBI-42 và PBI-44 chưa được xem là Done vì vẫn còn lỗi nghiêm trọng và các ca kiểm thử chưa đạt. Chúng ta tuyệt đối không được giấu 6 ca phân loại sai hay làm mờ số liệu để Sprint trông có vẻ thành công, vì Sprint Review là buổi kiểm tra thực tế chứ không phải báo cáo thành tích.'

2. Về việc hứa hẹn với Stakeholders: 'Feedback từ Chủ cửa hàng muốn AI tự trả lời nhiều hơn sẽ được ghi nhận và xem xét đưa vào Product Backlog, chúng ta không được tự động hứa sẽ làm ngay mọi Feedback trong Sprint sau mà phải dựa trên năng lực và định hướng của nhóm.'

3. Về thành phần tham dự: 'Chúng ta có mời Trưởng nhóm CSKH tham dự buổi Sprint Review này. Lý do là vì Trưởng nhóm CSKH có góc nhìn muốn chuyển hội thoại cho nhân viên sớm khi AI không chắc chắn, đây là mảnh ghép cực kỳ quan trọng để điều chỉnh Sprint Goal và cải thiện tính năng chăm sóc khách hàng đa kênh của RikkeiAssist.'

- Không giấu giếm số liệu lỗi, đảm bảo tính minh bạch tuyệt đối trong Scrum.
- Quản lý chặt chẽ Product Backlog Feedback, tránh tình trạng ôm đồm cam kết quá tải.
- Mời đúng stakeholder có góc nhìn liên quan trực tiếp để buổi Review đạt hiệu quả tối đa.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
