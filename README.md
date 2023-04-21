# Đề tài: QUẢN LÝ TRUNG TÂM TIẾNG ANH
## Bìa: Gồm hình logo của trung tâm + thanh progress bar 
- Đăng nhập
- Thay đổi mật khẩu
## Trang chủ: 
- Quản lý học viên: cho phép thêm, sửa, xoá thông tin học viên, bao gồm các thông tin như tên, ngày sinh, địa chỉ, số điện thoại, email, học phí đã đóng, khóa học đã đăng ký...

- Quản lý giáo viên: cho phép thêm, sửa, xoá thông tin giáo viên, bao gồm các thông tin như tên, ngày sinh, địa chỉ, số điện thoại, email, trình độ tiếng Anh, lịch dạy, môn học giảng dạy, mức lương...

- Quản lý khóa học: cho phép thêm, sửa, xoá thông tin khóa học, bao gồm các thông tin như mã khóa học, tên khóa học, số buổi học, giáo viên phụ trách, học phí...

- Quản lý kết quả học tập: cho phép nhập điểm cho học viên, tính điểm trung bình của học viên, in báo cáo kết quả học tập của học viên. 

- Quản lý tài chính: cho phép quản lý thu chi, tính toán lợi nhuận của trung tâm, in báo cáo tài chính.

- Quản lý tài khoản người dùng: cho phép quản lý thông tin tài khoản của người dùng, bao gồm tên đăng nhập, mật khẩu, quyền hạn...

- Thống kê: cho phép in ra các báo cáo thống kê về số lượng học viên, giáo viên, khóa học, lớp học, doanh thu, lợi nhuận...
## Database
- Tài khoản
- Học sinh: id, tên, ngày sinh, địa chỉ, số điện thoại, khóa học đã đăng ký, điểm giữa kỳ, điểm cuối kỳ, điểm TB = (gk + ck * 2) / 3
- Giáo viên: id, tên, ngày sinh, địa chỉ, số điện thoại, trình độ tiếng Anh, khóa học giảng dạy
- Khóa học: mã khóa học, tên khóa học, số buổi học, mô tả, học phí, số lượng học viên, số lượng giáo viên dạy, lợi nhuận 

## Các trang chính
- Trang chủ: hiển thị số lượng học sinh, giáo viên, khóa học của trung tâm và 3 khóa học hot nhất
- Học sinh: thêm xóa sửa các trường có trong trang học sinh (lưu ý là phải chọn khóa học rồi mới đc thao tác), đảm bảo input đúng định dạng (ngày sinh phải đúng kiểu ngày sinh, ..), chức năng tìm kiếm học sinh theo tên và mỗi khi thêm xóa sửa xong thì cập nhật lại bảng
- Giáo viên: tương tự học sinh
- Điểm: chỉnh sửa điểm cho học sinh (phải chọn khóa học trc, sau đó thông tin học sinh hiện lên bảng, bấm vào bảng để đưa các thông tin lên trên textbox và thực hiện sửa điểm + tính GPA theo công thức ở trên)
- Khóa học: thêm sửa xóa khóa học, tìm kiếm khóa học, ... (Lưu ý khi sửa, xóa khóa học thì các bảng như học sinh và giáo viên cũng bị ảnh hưởng)
- Thống kê: in ra tổng doanh thu các khóa học, bảng có thể sắp xếp các khóa học theo thứ tự doanh thu tăng/giảm dần và in thông tin trên bảng ra file .txt
## Phân chia công việc
- Doanh: làm bìa + báo cáo
- Vũ: đăng nhập đăng ký, qly tài khoản
- Thuận: quản lý học viên + giáo viên
- Quỳnh: quản lý khóa học + kết quả học tập
- Hưng: thống kê + chức năng tìm kiếm hsinh/khóa học/giáo viên
