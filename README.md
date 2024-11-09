
# Website Quản Lý Trung Tâm ngoại ngữ
## Thành viên
| | Họ và tên | Vai trò |
| ------------- | ------------- | ------------- |
| | Trương Nhật Thụy  | Product Owner  |
| | Nguyễn Duy Dương | Scrum Master |
| | Nguyễn Minh Khang | Team Leader  |
## 1.Giới thiệu Đề tài
Trung tâm anh ngữ Jane là một trung tâm đào tạo tiếng anh cho học viên từ nhiều độ tuổi khác nhau và đã có một lượng học viên ổn định, để mở rộng hoạt động của trung tâm ban quản lý mong muốn xây dựng một phần mềm quản lý trực tuyến nhằm mở rộng phạm vi cung cấp dịch vụ và tối ưu hóa quy trình quản lý học viên. 

Yêu cầu khách hàng mong muốn:
- Hệ thống trung tâm anh ngữ Jane phải đảm bảo cho học viên, khách hàng và phụ huynh có thể truy cập website để chọn khóa học phù hợp 
- Khách hàng, học viên có thể tìm hiểu thông tin về giáo viên, các chương trình học và chính sách của trung tâm cũng như các ưu đãi đăng ký
- Học viên có thể thanh toán học phí trực tuyến thông qua nhiều phương thức khác nhau hoặc thanh toán trực tiếp tại trung tâm
- Trung tâm tổ chức luyện thi tiếng anh cho học viên
- Trung tâm cấp bằng tiếng anh cho học viên đạt chỉ tiêu
Đội ngũ phát triển thêm:
- Học viên đánh giá về khóa học và giáo viên
- Giáo viên có thể tạo các diễn đàn trao đổi giữa giáo viên và học viên
- Giáo viên đánh giá về tiến độ học tập của học viên
- ## 2.Giới thiệu công nghệ sử dụng
![image]([image](https://github.com/user-attachments/assets/a3ae765c-7155-40ee-aea3-2efe29997e9a)
)

**MVC** là viết tắt của "Model-View-Controller," một mô hình kiến trúc phần mềm được sử dụng rộng rãi trong phát triển ứng dụng web và phần mềm để tách biệt logic ứng dụng thành ba phần chính: Model, View và Controller. Mô hình này giúp cải thiện tổ chức mã nguồn, tăng tính tái sử dụng và dễ bảo trì. Dưới đây là giới thiệu về từng phần trong mô hình MVC:

**Model:**

**Model** là phần chịu trách nhiệm xử lý dữ liệu và logic của ứng dụng.
Nó đại diện cho các đối tượng và dữ liệu trong ứng dụng.
Model quản lý cách dữ liệu được lưu trữ, truy cập và cập nhật, bao gồm các hoạt động như truy vấn cơ sở dữ liệu, xử lý logic kinh doanh, và quản lý tài nguyên dữ liệu.

**View:**

**View** là phần chịu trách nhiệm hiển thị thông tin cho người dùng.
Nó thể hiện giao diện người dùng, thường là các thành phần như trang web, giao diện người dùng đồ họa, hoặc giao diện dòng lệnh.
View không nên chứa logic ứng dụng; nó chỉ nên biết cách hiển thị thông tin mà nó nhận từ Model và cách gửi yêu cầu người dùng đến Controller.

**Controller:**

**Controller** là phần chịu trách nhiệm điều phối và xử lý yêu cầu từ người dùng và giao tiếp với Model và View.
Nó xử lý các sự kiện và yêu cầu từ người dùng, sau đó gọi Model để lấy dữ liệu hoặc cập nhật dữ liệu theo yêu cầu.
**Controller** sau đó cập nhật View để hiển thị thông tin mới cho người dùng.
Mô hình này cho phép tách biệt logic ứng dụng, giao diện người dùng và dữ liệu, giúp dễ dàng quản lý và bảo trì mã nguồn ứng dụng.
MVC cung cấp sự linh hoạt và tổ chức trong phát triển ứng dụng, cho phép nhiều người cùng làm việc trên dự án mà không gây xung đột về mã nguồn. Nó cũng là một mô hình rất phù hợp cho phát triển ứng dụng web, nơi Model quản lý dữ liệu, View xử lý giao diện người dùng, và **Controller** điều phối hành vi và logic ứng dụng.

## Các chức năng đồ án làm được
### 1.Xem Danh Sách Sách.
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/026730ff-0dc5-4cd2-afe1-c693c54465c4)

### 2.Tìm Kiếm Sách.
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/c114b75f-1fc0-4d37-8e81-f9f04cfa87c6)

### 3.Đặt Mượn Sách.
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/568927b6-9990-42db-9450-419dc92ef3c6)

### 4.Đăng Kí và Đăng Nhập.
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/e6e1ad57-432b-4724-8c1a-9d14ee09feff)


### 5.Admin chỉnh sửa,thêm,xóa sách trong thư viện
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/e26ac38e-d1c0-4942-a48d-4826cc6ad053)


### 6.Xem danh sách sản phẩm
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/39170724-672b-4c85-bc6f-e92233fec92b)


### 7.Admin thêm xóa sửa thể loại sách
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/3f4e4a68-5acc-408f-9a37-4e88fe572695)


### 8.Admin xác nhận hoặc xóa đơn hàng khách đặt
![image](https://github.com/DoanVinhThanh/7_QuanLyThuVien_T5_Ca3/assets/135934208/73d8b7fb-8c14-4b53-807c-69378deb8d4b)
