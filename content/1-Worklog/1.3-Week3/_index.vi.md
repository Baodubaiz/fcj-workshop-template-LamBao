---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Tích hợp Frontend và Backend với khả năng xử lý lỗi và theo dõi log hợp lý.
* Triển khai middleware theo dõi RequestID giúp truy vết luồng log.
* Chuẩn bị các cấu hình Docker để đóng gói các dịch vụ riêng lẻ.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tạo bộ lọc theo dõi RequestID trong Spring Boot để gán UUID duy nhất vào header của mỗi HTTP request gửi đến. | 29/04/2025 | 29/04/2025 |  |
| 3   | - Cấu hình Axios Interceptors trong Next.js để tự động gửi RequestID kèm theo.<br>- Lưu trữ và tự động chèn mã JWT vào header Authorization. | 30/04/2025 | 30/04/2025 | <https://axios-http.com/docs/interceptors> |
| 4   | - Phát triển bộ xử lý ngoại lệ toàn cục (Global Exception Handler) trong Spring Boot để trả về các phản hồi lỗi đồng nhất. | 01/05/2025 | 01/05/2025 |  |
| 5   | - Triển khai Next.js middleware để bảo vệ các trang Dashboard/Admin riêng tư và kiểm tra tính hợp lệ của token. | 02/05/2025 | 02/05/2025 | <https://nextjs.org/docs/app/building-your-application/routing/middleware> |
| 6   | - Viết Dockerfile ban đầu cho cả Backend (build đa giai đoạn cho JAR) và Frontend (Next.js runner).<br>- Tham số hóa cấu hình thông qua file env. | 03/05/2025 | 03/05/2025 | <https://docs.docker.com/engine/reference/builder/> |


### Kết quả đạt được tuần 3:

* Triển khai thành công Middleware Logging ghi nhận RequestID giúp gỡ lỗi thuận tiện.
* Cấu hình thành công Axios Interceptors xử lý token và theo dõi RequestID tự động.
* Tạo thành công hệ thống xử lý lỗi toàn cục cho phản hồi đồng nhất.
* Chuẩn bị sẵn sàng các file Dockerfile chuẩn cho FE và BE liên kết biến môi trường.
