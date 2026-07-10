---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu tuần 4:

* Thiết kế và xây dựng lược đồ cơ sở dữ liệu cho Hệ thống Biến thể Sản phẩm.
* Phát triển các API backend để quản lý sản phẩm và định cấu hình nhiều biến thể laptop.
* Triển khai mô hình Soft Delete (xóa mềm) cho sản phẩm và biến thể sản phẩm.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Thiết kế các bảng cơ sở dữ liệu cho Product, ProductVariant, Attribute và AttributeValue.<br>- Thiết lập các ánh xạ JPA (One-to-Many, Many-to-Many). | 01/09/2025 | 01/09/2025 | <https://hibernate.org/orm/documentation/> |
| 3   | - Triển khai Soft Delete bằng cách thêm cột `is_deleted` và ghi đè hoạt động xóa của Hibernate bằng `@SQLDelete`. | 02/09/2025 | 02/09/2025 |  |
| 4   | - Tạo các lớp controller, service và repository cho ProductVariant.<br>- Thực hiện các thao tác CRUD cho biến thể sản phẩm. | 03/09/2025 | 03/09/2025 |  |
| 5   | - Xây dựng các endpoint API để tạo sản phẩm phức tạp bao gồm nhiều thuộc tính và biến thể (ví dụ: cấu hình RAM, ổ cứng của laptop). | 04/09/2025 | 04/09/2025 |  |
| 6   | - Tạo trang giao diện quản trị sản phẩm trên Next.js frontend để cho phép admin quản lý sản phẩm và biến thể. | 05/09/2025 | 05/09/2025 |  |


### Kết quả đạt được tuần 4:

* Thiết kế thành công lược đồ cơ sở dữ liệu quan hệ hỗ trợ các thuộc tính và biến thể sản phẩm phức tạp.
* Triển khai thành công logic Soft Delete cho sản phẩm và biến thể.
* Hoàn thành các API RESTful quản lý sản phẩm và biến thể kèm kiểm thực dữ liệu.
* Tích hợp các form tạo biến thể trên giao diện Next.js admin.
