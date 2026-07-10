---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Thiết kế cơ chế Giữ hàng (Stock Reservation) để tạm khóa kho trong quá trình thanh toán.
* Xây dựng hệ thống giải phóng tự động để hoàn trả hàng vào kho nếu thanh toán thất bại.
* Kiểm thử hành vi hệ thống trong các kịch bản thanh toán đồng thời cao.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Triển khai các thuộc tính tồn kho trong ProductVariant.<br>- Thiết lập cơ chế khóa bi quan (pessimistic) và lạc quan (optimistic) để tránh race condition khi checkout đông. | 20/05/2025 | 20/05/2025 | <https://docs.jboss.org/hibernate/orm/5.4/userguide/html_single/Hibernate_User_Guide.html#locking> |
| 3   | - Phát triển luồng Tạo đơn hàng thực hiện giữ kho tạm thời ngay khi bắt đầu checkout. | 21/05/2025 | 21/05/2025 |  |
| 4   | - Triển khai tác vụ Spring Boot Scheduler để theo dõi đơn hàng chờ thanh toán và tự động giải phóng kho nếu không thanh toán trong 15 phút. | 22/05/2025 | 22/05/2025 | <https://spring.io/guides/gs/scheduling-tasks/> |
| 5   | - Thiết lập logic mô phỏng tích hợp cổng thanh toán (giao dịch thành công và thất bại). | 23/05/2025 | 23/05/2025 |  |
| 6   | - Thực hiện kiểm thử tải giả lập nhiều người checkout đồng thời để xác minh tính nhất quán kho hàng. | 24/05/2025 | 24/05/2025 |  |


### Kết quả đạt được tuần 6:

* Xây dựng thành công hệ thống Stock Reservation tạm giữ hàng hóa để tránh bán quá số lượng (overselling).
* Triển khai thành công Spring Boot Scheduler tự động hoàn kho khi hết hạn giao dịch.
* Tích hợp các luồng mô phỏng thanh toán tác động trực tiếp đến trạng thái giữ kho.
* Xác minh thành công tính nhất quán của kho hàng dưới tải đồng thời cao nhờ các kỹ thuật khóa.
