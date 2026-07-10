---
title: "Week 3 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---


### Week 3 Objectives:

* Integrate Frontend and Backend with proper error handling and logging tracking.
* Implement RequestID Tracking middleware for trace logging.
* Prepare Docker configurations for containerizing individual services.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Create RequestID tracking filter in Spring Boot to attach a unique UUID to every incoming HTTP request header. | 08/25/2025 | 08/25/2025 |  |
| 3   | - Configure Axios Interceptors in Next.js to forward RequestID in every request.<br>- Store and automatically inject JWT Token into the Authorization header. | 08/26/2025 | 08/26/2025 | <https://axios-http.com/docs/interceptors> |
| 4   | - Develop a centralized global Exception Handler in Spring Boot to return standardized error responses. | 08/27/2025 | 08/27/2025 |  |
| 5   | - Implement Next.js routing middleware to guard private dashboard/admin pages and check token validity. | 08/28/2025 | 08/28/2025 | <https://nextjs.org/docs/app/building-your-application/routing/middleware> |
| 6   | - Draft initial Dockerfiles for both Backend (multi-stage build for JAR) and Frontend (Next.js runner).<br>- Parameterize environment settings via env files. | 08/29/2025 | 08/29/2025 | <https://docs.docker.com/engine/reference/builder/> |


### Week 3 Achievements:

* Implemented Logging Middleware that records RequestID, facilitating easier debugging.
* Configured Axios Interceptors to handle JWT tokens and RequestID tracking automatically.
* Created global exception handling for uniform error messages.
* Prepared production-ready Dockerfiles for FE and BE with environment variable bindings.
