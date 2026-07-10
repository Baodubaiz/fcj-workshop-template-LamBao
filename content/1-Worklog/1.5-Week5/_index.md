---
title: "Week 5 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---


### Week 5 Objectives:

* Build shopping cart backend services and sync logic.
* Combine frontend Local Storage cart data with database cart upon user login.
* Develop a database seeding system to populate the database with realistic laptop product configurations.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Design Cart and CartItem entities and map relationship with User.<br>- Create REST APIs for adding, updating, and removing items from the cart. | 09/08/2025 | 09/08/2025 |  |
| 3   | - Implement Next.js shopping cart logic using Local Storage for anonymous visitors. | 09/09/2025 | 09/09/2025 | <https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage> |
| 4   | - Write synchronization logic in Next.js and Spring Boot to merge local storage items into the user's DB cart upon login. | 09/10/2025 | 09/10/2025 |  |
| 5   | - Write a Python data crawler or backend batch seed script to import real laptop models (Dell, Mac, Asus) into the database. | 09/11/2025 | 09/11/2025 | <https://spring.io/guides/gs/batch-processing/> |
| 6   | - Test the cart sync flow end-to-end and resolve conflict scenarios (e.g. item exists in both local storage and database). | 09/12/2025 | 09/12/2025 |  |


### Week 5 Achievements:

* Designed and implemented Cart database models and backend services.
* Implemented Next.js local storage cart mechanics.
* Created seamless sync logic merging guest cart data into database cart upon authentication.
* Successfully populated the database with rich laptop configurations using batch import seeds.
