---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---


### Mục tiêu tuần 10:

* Docker hóa toàn bộ các dịch vụ riêng lẻ (Frontend, Backend, DB, Redis, Message Queue).
* Tạo file Docker Compose điều phối đa container liên kết các dịch vụ.
* Đảm bảo các cấu hình bảo mật và lưu trữ dữ liệu bền vững (persistence).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tối ưu hóa các Dockerfile sẵn có, giảm kích thước ảnh build bằng multi-stage build và ảnh nền alpine/distroless. | 17/06/2025 | 17/06/2025 | <https://docs.docker.com/compose/> |
| 3   | - Viết file `docker-compose.yml` thống nhất định nghĩa các dịch vụ: `novatech-fe`, `novatech-be`, `postgresql-db`, `redis-cache` và `rabbitmq-queue`. | 18/06/2025 | 18/06/2025 | <https://docs.docker.com/develop/develop-images/multistage-build/> |
| 4   | - Cấu hình mạng nội bộ docker (networks) và các biến môi trường kết nối nội bộ giữa các container. | 19/06/2025 | 19/06/2025 |  |
| 5   | - Cấu hình các Docker Volumes để lưu trữ lâu dài cho dữ liệu PostgreSQL, dữ liệu Redis và RabbitMQ. | 20/06/2025 | 20/06/2025 |  |
| 6   | - Chạy lệnh `docker compose up --build` ở local và thực hiện kiểm thử xác minh toàn diện mọi lớp ứng dụng. | 21/06/2025 | 21/06/2025 |  |


### Kết quả đạt được tuần 10:

* Đóng gói container thành công các ứng dụng Frontend và Backend.
* Xây dựng thành công mạng lưới Docker Compose liên kết toàn bộ dịch vụ phụ trợ.
* Bảo mật thông tin đăng nhập database và queue qua liên kết biến môi trường ngoài.
* Đảm bảo lưu trữ dữ liệu an toàn thông qua cấu hình volume cho container.
* Chạy thành công toàn bộ hệ thống ở local chỉ với một câu lệnh terminal duy nhất.
