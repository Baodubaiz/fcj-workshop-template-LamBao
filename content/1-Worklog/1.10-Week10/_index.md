---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---


### Week 10 Objectives:

* Dockerize all individual services (Frontend, Backend, DB, Redis, Message Queue).
* Create a multi-container Docker Compose file linking services.
* Ensure proper storage persistence and security configurations.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Refactor existing Dockerfiles, optimizing build size using multi-stage builds and alpine/distroless base images. | 10/13/2025 | 10/13/2025 | <https://docs.docker.com/compose/> |
| 3   | - Write a unified `docker-compose.yml` defining services: `novatech-fe`, `novatech-be`, `postgresql-db`, `redis-cache`, and `rabbitmq-queue`. | 10/14/2025 | 10/14/2025 | <https://docs.docker.com/develop/develop-images/multistage-build/> |
| 4   | - Configure private docker networks and environment variables linking services internally. | 10/15/2025 | 10/15/2025 |  |
| 5   | - Configure persistent Docker Volumes for PostgreSQL data, Redis, and RabbitMQ state directories. | 10/16/2025 | 10/16/2025 |  |
| 6   | - Run `docker compose up --build` locally and perform complete end-to-end validation of all application layers. | 10/17/2025 | 10/17/2025 |  |


### Week 10 Achievements:

* Successfully containerized Frontend and Backend applications.
* Constructed a multi-container Docker Compose network connecting all services.
* Secured database and queue credentials using external env parameter bindings.
* Ensured persistent data storage through configured Docker volumes.
* Ran the entire ecosystem locally with a single terminal command.
