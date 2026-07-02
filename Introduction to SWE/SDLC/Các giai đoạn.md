Có 6 giai đoạn : Planning -> Design -> Development -> Testing -> Deployment ->
Maintenance -> Planning ...

Gốc gác ban đầu của SDLC là Waterfall method

- Planning: SRS - Các yêu cầu được thu thập -> Đánh giá -> Ghi chép lại rồi sau đó đánh giá độ ưu tiên
	- Các nhân tố sau cần được đảm bảo : 
		- Người dùng và mục tiêu chung của giái pháp
		- Nguồn dữ liệu đầu ra và đầu vào
		- Tuân thủ pháp lý và quy định
		- Xác định rủi ro
		- Đảm bảo chất lượng
		- Phân bổ nguồn nhân lực và tài chính
		- Lập kế hoạch dự án
	- Chi phí nhân lực và hạ tầng được ước tính và cân nhắc dựa trên các hạn chế về thời gian
	- Các nhóm của dự án đc xác định và các vai trò của từng thành viên được đề xuất
	- Dev team sẽ dựng prototype trong TH các bên liên quan k đưa ra được yêu cầu hay cần xác nhận lại yêu cầu
- Design : Design Document (will be use in the next phase)
	- Các yêu cầu từ SRS sẽ được dùng để phát triển kiến trúc phần mềm 
	- Các prototype sẽ có thể đc xây dựng trong giai đoạn này
- Development: Khi team dev bắt đầu quá trình code khi mà design document đã hoàn thành
	- Design document sẽ được dùng để xác định và phân công công việc
- Testing: 
	- Code cần được test kĩ lưỡng để đảm bảo tính ổn định, an toàn và đáp ứng yêu cầu trong SRS
	- Bugs reported -> tracked -> fixed -> retested
- Deployment: phần mềm được triển khai vào môi trường production và cung cấp cho ng dùng
	- Có thể được dựng theo các giai đoạn (stages):
	- Môi trường dev -> Môi trường UAT (staged) -> Môi trường Production
- Maintenance:
	- Tìm lỗi trên UI hoặc xác định các yêu cầu khác ko được liệt kê trong SRS
	- Nếu phát hiện lỗi, các lỗi đó sẽ được prior ở giai đoạn phát triển sau hoặc sửa dưới dạng label hot-fix
	  
![[Pasted image 20260701111234.png]]