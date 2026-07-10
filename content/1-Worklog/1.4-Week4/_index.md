---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---



### Week 4 Objectives:

* Design and construct the Product Variant System database schema.
* Develop backend APIs for managing products and configuring multiple laptop variants.
* Implement Soft Delete pattern for products and product variants.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Design database tables for Product, ProductVariant, Attribute, and AttributeValue.<br>- Establish JPA mappings (One-to-Many, Many-to-Many). | 06/05/2025 | 06/05/2025 | <https://hibernate.org/orm/documentation/> |
| 3   | - Implement Soft Delete by introducing an `is_deleted` column and overriding Hibernate delete operations using `@SQLDelete`. | 07/05/2025 | 07/05/2025 |  |
| 4   | - Create ProductVariant controller, service, and repository layers.<br>- Implement CRUD operations for product variants. | 08/05/2025 | 08/05/2025 |  |
| 5   | - Build API endpoints for complex product creation including multiple attributes and variants (e.g. laptop RAM, storage configurations). | 09/05/2025 | 09/05/2025 |  |
| 6   | - Create the product administration UI page on Next.js frontend to allow admins to manage products and variants. | 10/05/2025 | 10/05/2025 |  |


### Week 4 Achievements:

* Designed a relational database schema supporting complex product attributes and variants.
* Successfully implemented Soft Delete logic for products and product variants.
* Created RESTful APIs for product and variant management with request validation.
* Integrated variant creation forms on the Next.js admin frontend.
