---
title: "Week 12 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.12. </b> "
---
{% notice warning %} 
⚠️ **Note:** The following information is for reference purposes only. Please **do not copy verbatim** for your own report, including this warning.
{% /notice %}


### Week 12 Objectives:

* Set up Prometheus and Grafana monitoring infrastructure.
* Implement a GitOps flow with a separate configuration repository.
* Validate GitOps synchronization, self-healing, and prepare the final report.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Enable Spring Boot Actuator Prometheus endpoint and configure metrics export. | 08/07/2025 | 08/07/2025 | <https://prometheus.io/docs/introduction/overview/> |
| 3   | - Deploy Prometheus and Grafana via Docker Compose. Connect Grafana dashboard to visualize JVM memory, threads, and HTTP requests. | 09/07/2025 | 09/07/2025 | <https://grafana.com/docs/> |
| 4   | - Create a dedicated GitOps configuration repository (`novatech-deploy`) to store system YAMLs/Compose files. | 10/07/2025 | 10/07/2025 | <https://opengitops.org/> |
| 5   | - Set up GitOps Agent (or automatic script) on a VPS monitoring the config repo to trigger pull-based deployments. | 11/07/2025 | 11/07/2025 |  |
| 6   | - Test GitOps self-healing by manually modifying server containers and verifying the agent automatically reverts changes to match Git state.<br>- Compile final internship report and prepare presentation slides. | 12/07/2025 | 12/07/2025 |  |


### Week 12 Achievements:

* Established system monitoring using Prometheus and Grafana metrics dashboards.
* Separated deployment configuration from application code into a dedicated repository.
* Configured GitOps agent supporting pull-based deployments on target server.
* Verified GitOps self-healing and configuration consistency checks.
* Successfully finalized all project documentation, code repositories, and worklogs.
