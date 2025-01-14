Tài liệu tham khảo: https://chatgpt.com/c/678466c9-e850-8000-b2e0-ae3995927381

Nguyễn Tùng Dương - 22se1

Bit220038

# Tự động hóa kiểm thử đăng nhập Orange HRM
## Tổng quan
Dự án này chứa các kịch bản kiểm thử tự động để kiểm tra chức năng đăng nhập của trang demo Orange HRM sử dụng Selenium WebDriver với Java và framework TestNG.
## Yêu cầu hệ thống
- Java Development Kit (JDK) 23
- Maven
- Trình duyệt Chrome
- Chrome WebDriver

## Cấu trúc dự án
```
em/
├── src/
│   └── test/
│       └── java/
│           └── org/
│               └── example/
│                   └── OrangeLoginTest.java
└── pom.xml
```
## Thư viện phụ thuộc

- Selenium WebDriver 4.27.0
- TestNG 7.10.2
- JUnit 4.13.1 (dùng để kiểm thử)
## Các trường hợp kiểm thử
Hiện tại đã triển khai các trường hợp kiểm thử:
### testLoginTestApplication: Kiểm tra đăng nhập thành công vào trang demo Orange HRM
- Nhập thông tin đăng nhập (tên đăng nhập: admin, mật khẩu: admin123)
- Xác nhận chuyển hướng thành công đến Dashboard
## Cấu hình
- URL cơ sở: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
- Trình duyệt: Chrome
- Trạng thái cửa sổ: Phóng to tối đa




