---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---


### Mục tiêu tuần 9:

* Tích hợp Message Queue (RabbitMQ hoặc Kafka) cho các hoạt động bất đồng bộ.
* Phát triển luồng thông báo email bất đồng bộ cho mã OTP và đơn hàng.
* Triển khai bộ tính toán cho Hệ thống Voucher.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Thiết lập máy chủ RabbitMQ/Kafka local.<br>- Thêm cấu hình AMQP và thiết lập binding exchange/queue trong Spring Boot. | 10/06/2025 | 10/06/2025 | <https://www.rabbitmq.com/documentation.html> |
| 3   | - Triển khai message publisher gửi tác vụ email tới hàng đợi khi có sự kiện (đăng ký người dùng, xác nhận đơn hàng). | 11/06/2025 | 11/06/2025 | <https://spring.io/guides/gs/messaging-rabbitmq/> |
| 4   | - Viết email consumer bất đồng bộ để nhận tin nhắn từ hàng đợi và gửi email thực tế bằng JavaMailSender. | 12/06/2025 | 12/06/2025 |  |
| 5   | - Thiết kế thực thể Voucher (giảm giá theo phần trăm và số tiền cố định) và lược đồ cơ sở dữ liệu. | 13/06/2025 | 13/06/2025 |  |
| 6   | - Triển khai dịch vụ xác thực và tính toán giảm giá (kiểm tra hạn dùng, giá trị đơn tối thiểu, số lần sử dụng code). | 14/06/2025 | 14/06/2025 |  |


### Kết quả đạt được tuần 9:

* Tích hợp thành công kiến trúc Message Queue giúp phân tách và thực thi tác vụ bất đồng bộ.
* Đẩy các tác vụ gửi email tốn thời gian xuống xử lý nền, giúp tăng tốc độ phản hồi API.
* Thiết kế và triển khai thành công hệ thống quản lý Voucher và công cụ kiểm tra logic.
* Kiểm thử thành công luồng thông báo bất đồng bộ và tính toán giảm giá từ đầu đến cuối.
