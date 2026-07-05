Indentifiers là gì?
- Để tham chiếu 1 thành phần của chương trình
	- giá trị
	- phương thức
	- interface hoặc 1 lớp
	bằng cách gán label với tên cho nó
	
- Identifier lưu trữ 2 kiểu dữ liệu: 
	- Constants (hằng số):
		- Value sẽ ko thay đổi (PI,...)
		- Value phải được chỉ định khi constant được định nghĩa
	- Variables (biến):
		- Data value có thể thay đổi
		- Cách tốt nhất để tham chiếu đến các program items chưa rõ (Username, filename, service,...)
		- Khai báo và gán kiểu biến cùng initial value cho biến khi khởi tạo
		- Gán lại dữ liệu cho các biến sau
		
- Identifier đặc biệt: Container
	- Tham chiếu được đến nhiều element của chương trình
			- Không cần tạo biến cho mỗi element
			- Nhanh và hiệu quả
	- Ví dụ: Lưu số lượng lớn giá trị
	- Arrays (Mảng):
		- Dạng container đơn giản nhất
		- Số lượng phẩn tử cố định được lưu tuần tự bắt đầu từ index = 0
		- Khi khai báo mảng:
			- Chỉ định kiểu dữ liệu của mảng (int, bool, str)
			- Chỉ định số lượng element tối đa nó có thể chứa
			- `int my_array[50]`
	- Vectors:
		- Kích thước động
		- Tự động thay đổi kích thước khi elements được thêm / xóa - a.k.a 'Dynamic Arrays'
		- Tốn nhiều bộ nhớ hơn
		- Mất nhiều thời gian để truy cập hơn vì được lưu trữ trong các vùng nhớ với vị trí tuần tự
		- `vector <int> my_vector`