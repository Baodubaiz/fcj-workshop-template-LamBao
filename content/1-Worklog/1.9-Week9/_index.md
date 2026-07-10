---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---


### Week 9 Objectives:

* Integrate Message Queue (RabbitMQ or Kafka) for asynchronous operations.
* Develop asynchronous email notification flows for OTPs and orders.
* Implement Voucher System calculation engine.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Setup local RabbitMQ/Kafka server.<br>- Add AMQP configuration and setup exchange/queue bindings in Spring Boot. | 10/06/2025 | 10/06/2025 | <https://www.rabbitmq.com/documentation.html> |
| 3   | - Implement message publisher that sends email tasks to queue on events (user registration, order confirmation). | 10/07/2025 | 10/07/2025 | <https://spring.io/guides/gs/messaging-rabbitmq/> |
| 4   | - Write asynchronous email consumer that picks up messages and sends actual emails using JavaMailSender. | 10/08/2025 | 10/08/2025 |  |
| 5   | - Design Voucher entities (percentage and fixed-amount discounts) and database schema. | 10/09/2025 | 10/09/2025 |  |
| 6   | - Implement validation and discount calculation services (expiry checks, min spend, voucher code usage counts). | 10/10/2025 | 10/10/2025 |  |


### Week 9 Achievements:

* Integrated Message Queue framework to enable decoupled, asynchronous task execution.
* Offloaded slow email sending tasks to background consumers, improving HTTP response times.
* Designed and implemented Voucher management and logic verification engine.
* Successfully tested end-to-end async notifications and discount calculations.
