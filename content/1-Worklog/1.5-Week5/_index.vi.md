---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Xây dựng dịch vụ backend và logic đồng bộ cho giỏ hàng mua sắm.
* Kết hợp dữ liệu giỏ hàng Local Storage ở frontend với giỏ hàng DB khi người dùng đăng nhập.
* Phát triển hệ thống gieo dữ liệu (data seeding) để đổ dữ liệu cấu hình laptop thực tế vào DB.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Thiết kế thực thể Cart và CartItem, ánh xạ quan hệ với User.<br>- Tạo các API REST để thêm, cập nhật và xóa sản phẩm khỏi giỏ hàng. | 08/09/2025 | 08/09/2025 |  |
| 3   | - Triển khai logic giỏ hàng ở Next.js sử dụng Local Storage dành cho khách truy cập vãng lai. | 09/09/2025 | 09/09/2025 | <https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage> |
| 4   | - Viết logic đồng bộ ở Next.js và Spring Boot để gộp các mặt hàng trong Local Storage vào giỏ hàng DB của người dùng sau khi đăng nhập. | 10/09/2025 | 10/09/2025 |  |
| 5   | - Viết một script python crawl dữ liệu hoặc script batch seed ở backend để nhập các mẫu laptop thực tế (Dell, Mac, Asus) vào DB. | 11/09/2025 | 11/09/2025 | <https://spring.io/guides/gs/batch-processing/> |
| 6   | - Kiểm thử luồng đồng bộ giỏ hàng từ đầu đến cuối và giải quyết các trường hợp xung đột (ví dụ: sản phẩm đã tồn tại ở cả hai nơi). | 12/09/2025 | 12/09/2025 |  |


### Kết quả đạt được tuần 5:

* Thiết kế và triển khai thành công mô hình cơ sở dữ liệu Cart và các dịch vụ backend.
* Triển khai thành công cơ chế giỏ hàng Local Storage phía Next.js.
* Tạo logic đồng bộ mượt mà gộp giỏ hàng vãng lai vào DB khi xác thực thành công.
* Đổ thành công dữ liệu phong phú về các dòng laptop thực tế vào database bằng script batch import.
