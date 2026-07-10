---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---


### Mục tiêu tuần 8:

* Triển khai tìm kiếm sản phẩm hiệu năng cao bằng PostgreSQL Full-text Search (hoặc Elasticsearch).
* Xây dựng bộ lọc tìm kiếm động cho các thông số kỹ thuật của biến thể laptop.
* Tối ưu hóa hiệu năng tìm kiếm với việc lập chỉ mục (indexing) cơ sở dữ liệu phù hợp.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu khái niệm PostgreSQL Full-text Search, TSQuery, TSVector và chỉ mục GIN (Generalized Inverted Index). | 29/09/2025 | 29/09/2025 | <https://www.postgresql.org/docs/current/textsearch.html> |
| 3   | - Cấu hình chỉ mục GIN trên tên sản phẩm, mô tả và các thuộc tính biến thể. | 30/09/2025 | 30/09/2025 |  |
| 4   | - Xây dựng Dynamic Search Specification trong Spring Boot để ghép nối các bộ lọc theo thông số (CPU, RAM, giá, thương hiệu). | 01/10/2025 | 01/10/2025 | <https://spring.io/blog/2011/04/26/advanced-spring-data-jpa-specifications-and-querydsl/> |
| 5   | - Tích hợp API tìm kiếm và lọc trên giao diện Next.js catalog với tính năng gợi ý tự động. | 02/10/2025 | 02/10/2025 |  |
| 6   | - Phân tích hiệu năng truy vấn tìm kiếm và xem kế hoạch thực thi SQL (execution plan) để đảm bảo index hoạt động. | 03/10/2025 | 03/10/2025 |  |


### Kết quả đạt được tuần 8:

* Triển khai thành công công cụ tìm kiếm nâng cao bằng PostgreSQL Full-text Search.
* Xây dựng thành công câu truy vấn tìm kiếm động theo các thông số kỹ thuật tùy chỉnh.
* Tạo trang tìm kiếm phản hồi nhanh với bộ lọc thời gian thực ở Frontend.
* Tối ưu hóa thời gian thực thi tìm kiếm thông qua chỉ mục GIN và xác thực qua query plan.
