---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---


### Week 11 Objectives:

* Create GitHub Actions CI/CD pipeline for Frontend auto-building.
* Create GitLab CI/CD pipeline for Backend compilation and image publishing.
* Implement automated linting, test suites, and Docker image pushing.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Write GitHub Actions configuration (`.github/workflows/frontend-ci.yml`) to trigger on commits to main branch. | 10/20/2025 | 10/20/2025 | <https://docs.github.com/en/actions> |
| 3   | - Configure Next.js linting, compilation test, and Docker image build in GitHub Actions. | 10/21/2025 | 10/21/2025 | <https://docs.gitlab.com/ee/ci/> |
| 4   | - Setup GitLab CI/CD configuration (`.gitlab-ci.yml`) for the backend project. | 10/22/2025 | 10/22/2025 |  |
| 5   | - Add steps to compile JAR, run unit tests, and build Spring Boot Docker image using GitLab runner. | 10/23/2025 | 10/23/2025 |  |
| 6   | - Integrate secure image publishing to Docker Hub or private Registry using repository secrets. | 10/24/2025 | 10/24/2025 |  |


### Week 11 Achievements:

* Implemented GitHub Actions pipeline for Next.js frontend, ensuring build checks on merge.
* Implemented GitLab CI/CD pipeline for Spring Boot backend, running tests before builds.
* Configured automatic Docker image creation and publishing to registry on branch pushes.
* Secured build pipelines by abstracting credentials via CI/CD secrets.
