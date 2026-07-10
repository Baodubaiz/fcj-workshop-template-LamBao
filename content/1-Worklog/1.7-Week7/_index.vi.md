---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Tích hợp Redis vào dự án backend Spring Boot.
* Triển khai Redis Caching cho các dữ liệu ít thay đổi như danh mục sản phẩm (categories).
* Lưu trữ mã OTP và cấu hình session trong Redis có thời gian hết hạn (TTL).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Chạy thực thể Redis ở local.<br>- Thêm các dependency Spring Boot Data Redis starter và cấu hình thuộc tính kết nối. | 22/09/2025 | 22/09/2025 | <https://redis.io/docs/> |
| 3   | - Triển khai cache Redis cho API danh sách danh mục sản phẩm bằng `@Cacheable` và cấu hình xóa cache (`@CacheEvict`) khi cập nhật danh mục. | 23/09/2025 | 23/09/2025 | <https://spring.io/guides/gs/caching/> |
| 4   | - Triển khai lưu trữ tạm thời mã OTP trong Redis, áp dụng TTL 5 phút cho việc xác thực mã. | 24/09/2025 | 24/09/2025 |  |
| 5   | - Chuyển việc lưu trữ danh sách session hoạt động hoặc token bị thu hồi từ bộ nhớ RAM sang Redis. | 25/09/2025 | 25/09/2025 |  |
| 6   | - Đo lường sự khác biệt về hiệu năng API và tạo benchmark so sánh truy vấn PostgreSQL DB trực tiếp với hit cache Redis. | 26/09/2025 | 26/09/2025 |  |


### Kết quả đạt được tuần 7:

* Tích hợp thành công Redis vào cơ sở hạ tầng ứng dụng.
* Triển khai bộ nhớ đệm Redis cho danh mục sản phẩm, giảm tải đáng kể cho database.
* Bảo mật hệ thống OTP với cơ chế tự động hủy bằng cách tận dụng tính năng Redis TTL.
* Di chuyển kiểm tra phiên làm việc người dùng sang tầng cache Redis để tăng khả năng mở rộng.
* Đo lường thời gian phản hồi API giảm mạnh khi sử dụng Redis.
