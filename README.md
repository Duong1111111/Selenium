**Selenium Login Test - README**

BIT220043 - Nguyễn Văn Dưỡng

Mô Tả Dự Án
 Dự án này là một bài kiểm tra đơn giản về việc thực hiện đăng nhập trên trang web mẫu sử dụng Selenium WebDriver với trình duyệt Microsoft Edge. Bài kiểm tra bao gồm hai tình huống: đăng nhập thành công và đăng nhập thất bại. Các kết quả sẽ được xác nhận thông qua nội dung trả về từ phần tử HTML trong trang web.

Mục Tiêu
1. Xây dựng một ứng dụng web đơn giản với form đăng nhập: Trang web bao gồm hai trường nhập liệu (Tên đăng nhập và Mật khẩu) cùng một nút đăng nhập.
2. Kiểm tra chức năng đăng nhập bằng Selenium WebDriver: Sử dụng Selenium để tự động nhập liệu vào form đăng nhập, nhấn nút đăng nhập, và kiểm tra kết quả trả về.
3. Xác minh kết quả của các tình huống khác nhau: Kiểm tra khi đăng nhập thành công (với tên đăng nhập và mật khẩu chính xác) và đăng nhập thất bại (với tên đăng nhập hoặc mật khẩu sai).
   
Mục Đích
1. Học cách sử dụng Selenium WebDriver: Cung cấp một ví dụ thực tiễn để hiểu cách tự động hóa việc kiểm tra giao diện người dùng của một ứng dụng web.
2. Tự động hóa các bài kiểm tra UI: Giúp tiết kiệm thời gian khi kiểm tra các tính năng của một trang web mà không cần phải làm thủ công.
3. Kiểm tra tính đúng đắn của các chức năng đăng nhập: Đảm bảo hệ thống hoạt động chính xác trong các tình huống người dùng có thể gặp phải.

Cấu Trúc Dự Án
1. index.html: Trang web mẫu với form đăng nhập.
![image](https://github.com/user-attachments/assets/3f905e34-fca1-44b2-a323-f10a79689ea5)

2. LoginTest.java: Lớp Java sử dụng Selenium WebDriver để tự động hóa việc kiểm tra đăng nhập.
![image](https://github.com/user-attachments/assets/b15e6864-5fa1-4ac7-b29a-37e79caa8b1d)

Cấu hình và chạy Selenium Test:
1. Tạo một thư mục mới trong Java project và thêm Selenium WebDriver vào dependency của bạn (nếu sử dụng Maven hoặc Gradle).
2. Tải trang web mẫu (index.html) vào thư mục resources hoặc một thư mục phù hợp trong dự án.
3. Đảm bảo rằng đường dẫn msedgedriver.exe trong mã nguồn trỏ tới vị trí đúng trên hệ thống của bạn.

Chạy thử nghiệm Selenium:
Sau khi cấu hình, bạn có thể chạy LoginTest.java bằng Intelij

Kết Quả Kiểm Tra
Test đăng nhập thành công: Khi người dùng nhập đúng tên đăng nhập (admin) và mật khẩu (1234), thông báo "Đăng nhập thành công!" sẽ hiển thị với màu xanh lá.
Test đăng nhập thất bại: Khi người dùng nhập sai tên đăng nhập hoặc mật khẩu, thông báo "Tên đăng nhập hoặc mật khẩu sai!" sẽ hiển thị với màu đỏ.
Kết quả kiểm tra được in ra màn hình console của Java.
![image](https://github.com/user-attachments/assets/75c54fb3-6786-47f3-89f0-df94c5133c58)

Yêu Cầu
JDK: Phiên bản 8 trở lên.
Selenium WebDriver: Phiên bản mới nhất.
Trình duyệt: Microsoft Edge.
msedgedriver: Phiên bản phù hợp với trình duyệt Edge của bạn.

Kết luận
Dự án này cung cấp một ví dụ cơ bản về cách sử dụng Selenium WebDriver để kiểm tra giao diện người dùng cho một trang web với form đăng nhập. Bạn có thể mở rộng dự án này để thử nghiệm với các tính năng phức tạp hơn như kiểm tra nhiều tình huống đăng nhập, đăng xuất, và các tương tác với UI phức tạp hơn.

