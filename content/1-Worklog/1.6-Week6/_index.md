---
title: "Week 6 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---



### Week 6 Objectives:

* Design the Stock Reservation mechanism to hold inventory temporarily during checkout.
* Build automated release systems to return items to inventory if payment fails.
* Test system behavior under concurrent checkout scenarios.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Implement stock attributes in ProductVariant.<br>- Setup optimistic and pessimistic locking mechanisms to prevent race conditions during high-traffic checkout. | 09/15/2025 | 09/15/2025 | <https://docs.jboss.org/hibernate/orm/5.4/userguide/html_single/Hibernate_User_Guide.html#locking> |
| 3   | - Develop Order Creation flow that reserves inventory items temporarily upon checkout initiation. | 09/16/2025 | 09/16/2025 |  |
| 4   | - Implement a Spring Boot Scheduler task to monitor pending orders and release reserved stock if payment is not completed within 15 minutes. | 09/17/2025 | 09/17/2025 | <https://spring.io/guides/gs/scheduling-tasks/> |
| 5   | - Setup simulation logic for payment gateway integrations (successful and failed transactions). | 09/18/2025 | 09/18/2025 |  |
| 6   | - Perform load tests to simulate simultaneous checkouts and verify inventory consistency. | 09/19/2025 | 09/19/2025 |  |


### Week 6 Achievements:

* Built Stock Reservation system that reserves products temporarily to avoid overselling.
* Successfully implemented Spring Boot Scheduler to automatically release stock on transaction timeouts.
* Integrated payment simulation flows affecting stock reservation status.
* Verified inventory consistency under high concurrency using locking techniques.
