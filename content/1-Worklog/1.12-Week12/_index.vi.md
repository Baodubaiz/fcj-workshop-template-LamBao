---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.12. </b> "
---



### Mục tiêu tuần 12:

* Cấu hình cơ sở hạ tầng giám sát Prometheus và Grafana.
* Triển khai quy trình GitOps với một kho lưu trữ cấu hình riêng biệt.
* Xác minh đồng bộ GitOps, tính năng self-healing và chuẩn bị báo cáo tổng kết.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Bật endpoint Spring Boot Actuator Prometheus và cấu hình xuất các chỉ số (metrics). | 27/10/2025 | 27/10/2025 | <https://prometheus.io/docs/introduction/overview/> |
| 3   | - Triển khai Prometheus và Grafana qua Docker Compose. Kết nối dashboard Grafana để trực quan hóa dung lượng bộ nhớ JVM, luồng xử lý và HTTP request. | 28/10/2025 | 28/10/2025 | <https://grafana.com/docs/> |
| 4   | - Tạo một repo Git chứa cấu hình triển khai riêng biệt (`novatech-deploy`) chỉ chứa file cấu hình YAML/Compose. | 29/10/2025 | 29/10/2025 | <https://opengitops.org/> |
| 5   | - Cài đặt Agent GitOps (hoặc script tự động kéo) trên VPS giám sát repo cấu hình để thực hiện pull-based deployment. | 30/10/2025 | 30/10/2025 |  |
| 6   | - Kiểm tra tính năng self-healing của GitOps bằng cách thay đổi container trên server thủ công và xác thực Agent tự động khôi phục cấu hình khớp với Git. | 31/10/2025 | 31/10/2025 |  |


### Kết quả đạt được tuần 12:

* Thiết lập thành công hệ thống giám sát hiệu năng sử dụng Prometheus và biểu đồ Grafana.
* Tách biệt hoàn toàn cấu hình triển khai và mã nguồn ứng dụng sang repository chuyên biệt.
* Cấu hình thành công cơ chế pull-based deployment thông qua Agent GitOps.
* Xác thực tính năng tự sửa lỗi (self-healing) và tính nhất quán cấu hình hệ thống.
* Hoàn thiện toàn bộ tài liệu dự án, mã nguồn các kho lưu trữ và báo cáo nhật ký công việc.
