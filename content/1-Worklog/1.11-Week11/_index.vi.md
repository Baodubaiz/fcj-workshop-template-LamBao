---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---


### Mục tiêu tuần 11:

* Tạo pipeline GitHub Actions CI/CD để tự động build Frontend.
* Tạo pipeline GitLab CI/CD để biên dịch Backend và phát hành image.
* Triển khai kiểm tra code (lint), chạy test suite tự động và push Docker image lên registry.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Viết file cấu hình GitHub Actions (`.github/workflows/frontend-ci.yml`) kích hoạt khi commit vào nhánh main. | 20/10/2025 | 20/10/2025 | <https://docs.github.com/en/actions> |
| 3   | - Cấu hình kiểm tra cú pháp (lint), kiểm tra biên dịch Next.js và đóng gói Docker image trên GitHub Actions. | 21/10/2025 | 21/10/2025 | <https://docs.gitlab.com/ee/ci/> |
| 4   | - Thiết lập cấu hình GitLab CI/CD (`.gitlab-ci.yml`) cho dự án backend. | 22/10/2025 | 22/10/2025 |  |
| 5   | - Thêm các bước biên dịch file JAR, chạy unit test và build Spring Boot Docker image thông qua GitLab runner. | 23/10/2025 | 23/10/2025 |  |
| 6   | - Tích hợp tự động đẩy (push) image lên Docker Hub hoặc Registry riêng bằng cách sử dụng secret key bảo mật. | 24/10/2025 | 24/10/2025 |  |


### Kết quả đạt được tuần 11:

* Triển khai thành công pipeline GitHub Actions cho frontend Next.js đảm bảo kiểm tra khi merge.
* Triển khai thành công pipeline GitLab CI/CD cho backend Spring Boot chạy test tự động trước khi build.
* Cấu hình đóng gói và đẩy Docker image tự động lên registry mỗi khi đẩy code lên nhánh chính.
* Bảo mật thành công pipeline CI/CD nhờ cơ chế lưu thông tin qua Secrets.
