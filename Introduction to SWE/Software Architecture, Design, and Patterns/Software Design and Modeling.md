Dựa trên nội dung bài giảng **[Software Design and Modeling](https://www.coursera.org/learn/introduction-to-software-engineering/lecture/7ivJf/software-design-and-modeling)**, tôi xin tóm tắt các điểm chính để bạn nắm bắt nhanh như sau:

### 1. Hai cách tiếp cận chính trong thiết kế

* **Thiết kế cấu trúc (Structured Design):** Chia nhỏ vấn đề thành các module và sub-module.
* *Nguyên tắc:* Các module cần **gắn kết (cohesive)** (các thành phần cùng chức năng ở gần nhau) và **kết nối lỏng lẻo (loosely coupled)** (thay đổi ở module này ít ảnh hưởng đến module khác).
* **Mô hình hành vi (Behavioral Models):** Mô tả hệ thống làm gì (chức năng) mà không cần quan tâm đến cách nó thực thi (kỹ thuật).

### 2. Ngôn ngữ mô hình hóa thống nhất (UML)

UML là ngôn ngữ hình ảnh tiêu chuẩn để biểu diễn kiến trúc và thiết kế hệ thống.

* **Lợi ích:**
	* Lập kế hoạch tính năng trước khi viết code (tiết kiệm thời gian, chi phí).
	* Giúp nhân sự mới nắm bắt dự án nhanh hơn.
	* Cầu nối giao tiếp giữa người làm kỹ thuật và không làm kỹ thuật.
	* Hỗ trợ lập trình viên điều hướng mã nguồn dễ dàng hơn.

### 3. Hai loại sơ đồ UML phổ biến

* **Sơ đồ chuyển trạng thái (State Transition Diagram):** Thể hiện các trạng thái khác nhau của hệ thống và các sự kiện gây ra sự thay đổi giữa các trạng thái đó (Ví dụ: trạng thái bệnh nhân trong phòng khám: đang đợi -> đang kiểm tra -> gặp bác sĩ).
* **Sơ đồ tương tác (Interaction Diagram):** Thể hiện cách các đối tượng trong hệ thống giao tiếp với nhau theo thời gian (Ví dụ: Sơ đồ trình tự - Sequence Diagram mô tả việc người dùng đặt lịch hẹn trên cổng thông tin).
