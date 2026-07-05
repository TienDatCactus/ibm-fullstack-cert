Kiến trúc phần mềm (Software Architecture) có thể được hiểu một cách đơn giản như sau:

### 1. Bản chất của Kiến trúc phần mềm

Đây là **bản thiết kế tổng thể (blueprint)** của cả hệ thống. Nó xác định:

* Cách tổ chức và cấu trúc các thành phần trong hệ thống.
* Cách các thành phần này tương tác với nhau.
* Các nguyên tắc nền tảng để xây dựng hệ thống đó.

### 2. Tại sao kiến trúc lại quan trọng?

* **Là nền tảng giao tiếp:** Giúp các thành viên trong nhóm hiểu rõ hệ thống, đảm bảo sự đồng bộ trong quá trình làm việc.
* **Quyết định sớm, khó thay đổi:** Kiến trúc được hình thành từ những quyết định đầu tiên. Nếu sau này muốn thay đổi, chi phí sẽ rất cao và tốn kém.
* **Giải quyết các yếu tố phi chức năng:** Nó đảm bảo hệ thống đạt được các tiêu chuẩn về hiệu năng, khả năng mở rộng (scalability), tính bảo mật, khả năng bảo trì và quản lý.
* **Đảm bảo sự linh hoạt:** Một kiến trúc tốt giúp hệ thống dễ dàng thích nghi khi yêu cầu thay đổi trong quá trình phát triển.

### 3. Ảnh hưởng đến quy trình thực hiện

* **Công nghệ (Tech Stack):** Kiến trúc định hướng việc chọn ngôn ngữ lập trình, thư viện và khung làm việc (framework) phù hợp với mục tiêu của hệ thống.
* **Môi trường triển khai:** Kiến trúc quyết định môi trường mà phần mềm sẽ chạy, bao gồm hạ tầng như máy chủ (servers), cân bằng tải (load balancers) và cơ sở dữ liệu.

### 4. Các tài liệu/công cụ (Artifacts) dùng để thể hiện kiến trúc

Để giao tiếp thiết kế với các bên liên quan, kỹ sư thường tạo ra:

* **Software Design Document (SDD):** Tài liệu mô tả kỹ thuật, các ràng buộc, yêu cầu và phương pháp luận.
* **Architectural Diagram:** Sơ đồ hiển thị các thành phần, sự tương tác và các mẫu kiến trúc (Architectural Patterns) được sử dụng.
* **UML Diagrams:** Các sơ đồ chuẩn dùng để diễn giải cấu trúc và hành vi của hệ thống bằng ngôn ngữ hình ảnh phổ thông.
