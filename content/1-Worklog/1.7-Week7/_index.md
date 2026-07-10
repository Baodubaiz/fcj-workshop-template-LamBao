---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---



### Week 7 Objectives:

* Integrate Redis into the Spring Boot backend.
* Implement Redis Caching for hot data such as product categories.
* Store OTP codes and session configurations in Redis with TTL.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Spin up local Redis instance.<br>- Add Spring Boot Data Redis starter dependencies and configure connection properties. | 09/22/2025 | 09/22/2025 | <https://redis.io/docs/> |
| 3   | - Implement Redis caching for Product Category list API using `@Cacheable` and configure cache eviction (`@CacheEvict`) on category updates. | 09/23/2025 | 09/23/2025 | <https://spring.io/guides/gs/caching/> |
| 4   | - Implement temporary user OTP storage in Redis, applying a 5-minute TTL (Time-To-Live) for OTP verification. | 09/24/2025 | 09/24/2025 |  |
| 5   | - Shift Session token blacklisting or active sessions storage from memory to Redis. | 09/25/2025 | 09/25/2025 |  |
| 6   | - Measure API performance differences and create benchmarks comparing PostgreSQL DB requests versus Redis cache hits. | 09/26/2025 | 09/26/2025 |  |


### Week 7 Achievements:

* Integrated Redis into the application infrastructure.
* Implemented Redis caching for product categories, reducing database load.
* Secured OTP system with automatic expiration by leveraging Redis TTL features.
* Migrated user session checks to Redis cache layer, enhancing scalability.
* Observed significant reduction in API response times using Redis.
