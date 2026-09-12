# Leomar Moncada

### Senior DevOps / Site Reliability Engineer

I've spent about ten years building and running cloud infrastructure, mostly on AWS, with a good amount of GCP and Azure along the way. Day to day that usually means making deploys faster and less nerve-racking, keeping Kubernetes and ECS workloads healthy in production, replacing click-ops with Terraform, and carrying the pager when something breaks anyway.

The last couple of years added a new layer: running GenAI workloads in production. RAG pipelines, model CI/CD, and GPU inference that holds up under real traffic.

Based in Málaga, Spain. Open to remote and contract work.

[Portfolio](https://leomoncada.github.io/terminal-web/) · [LinkedIn](https://www.linkedin.com/in/leomar-moncada/) · [leomarmoncadah@gmail.com](mailto:leomarmoncadah@gmail.com)

---

## Some things I've done

* Took a CI/CD pipeline from 15 minutes down to 5, which changed how often the team was actually willing to ship.
* Kept ECS, EKS and Kubernetes workloads at 99.9% uptime, and cut time to detect and resolve incidents by 90% by rebuilding monitoring and alerting nobody trusted.
* Ran fintech platforms at real scale: 1.2M+ users on a 90% serverless AWS architecture, and 9.5M+ users with 13M+ issued cards.
* Brought resource usage and cost down by up to 80% on specific workloads through capacity and performance tuning.
* Wrote Terraform and Pulumi modules that took environment provisioning from days to minutes, so product teams stopped filing tickets for it.
* Handled HIPAA, SOC 2 and Central Bank of Panama compliance, holding zero high or critical vulnerabilities with same-day remediation.
* Built the platform side of GenAI: RAG pipelines, Amazon Bedrock and Anthropic/OpenAI integrations, vector databases, model CI/CD and GPU inference serving.
* Set CI/CD and quality standards across roughly 8 engineering teams, together with the dev and QA leads.

---

## Featured work

**[aws-ecs-fargate-platform](https://github.com/leomoncada/aws-ecs-fargate-platform)**
A full AWS deployment set up the way I'd actually run it. Terraform with separate state per environment, ECS Fargate behind an ALB, shared ECR, and GitHub Actions that builds on staging and promotes the same image to prod. It also ships the parts people skip: observability docs, architecture decision records, and runbooks for deploy, rollback and incidents.

**[terminal-web](https://github.com/leomoncada/terminal-web)**
My portfolio, as a terminal you can type into. React, TypeScript and Vite, deployed to GitHub Pages by Actions. [Try it](https://leomoncada.github.io/terminal-web/) and run `help`.

---

## Stack

**Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)

**Containers & Orchestration**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**Infrastructure as Code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=flat-square)

**CI/CD & GitOps**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Flux](https://img.shields.io/badge/FluxCD-5468FF?style=flat-square&logo=flux&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**AI / MLOps**

![Amazon Bedrock](https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=flat-square)
![Anthropic](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Kubeflow](https://img.shields.io/badge/Kubeflow-326CE5?style=flat-square)

**Languages & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Certifications

* [Claude Certified Architect, Foundations](https://www.credly.com/badges/f0494f0d-d723-4752-b6fd-5d869a1de2f9) (Anthropic, 2026)
* AWS Certified Solutions Architect, Associate

---

## Get in touch

I'm looking at Senior DevOps, SRE and Platform Engineering roles, remote or contract. Easiest way to reach me is email.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/leomar-moncada/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:leomarmoncadah@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://leomoncada.github.io/terminal-web/)

<sub>English (professional working proficiency) and Spanish (native)</sub>
