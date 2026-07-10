---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---


### Mục tiêu tuần 2:

* Cấu hình Spring Security bên trong ứng dụng.
* Triển khai cơ chế tạo và xác thực mã JWT (JSON Web Token) an toàn.
* Xây dựng thành công các API đăng ký và đăng nhập người dùng.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Cấu hình các quy tắc Spring Security và tắt trạng thái session (xác thực stateless).<br>- Triển khai BCryptPasswordEncoder để mã hóa mật khẩu bảo mật. | 22/04/2025 | 22/04/2025 | <https://spring.io/projects/spring-security> |
| 3   | - Triển khai các lớp User Entity, Repository và Service để lưu trữ dữ liệu người dùng.<br>- Thiết lập logic User details và tải thông tin người dùng. | 23/04/2025 | 23/04/2025 |  |
| 4   | - Tạo lớp tiện ích JWT Provider để tạo, phân tích cú pháp và xác thực mã JWT.<br>- Thêm cấu hình thời hạn hết hạn và ký khóa bí mật. | 24/04/2025 | 24/04/2025 | <https://jwt.io/introduction> |
| 5   | - Triển khai các endpoint Controller cho Đăng nhập và Đăng ký.<br>- Viết các DTO cho yêu cầu và phản hồi xác thực. | 25/04/2025 | 25/04/2025 |  |
| 6   | - Tích hợp giao diện trang Đăng nhập và Đăng ký trên Next.js Frontend.<br>- Thử nghiệm gọi API đăng nhập và lưu trữ token. | 26/04/2025 | 26/04/2025 |  |


### Kết quả đạt được tuần 2:

* Cấu hình thành công Spring Security và các tham số xác thực không trạng thái.
* Triển khai mã hóa mật khẩu an toàn và lưu trữ cơ sở dữ liệu cho người dùng.
* Tạo tiện ích xác thực JWT bảo mật mã hóa thông tin.
* Hoàn thành các API Đăng nhập và Đăng ký hoạt động chính xác.
* Xây dựng các biểu mẫu xác thực trên Next.js frontend.
