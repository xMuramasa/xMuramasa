<div align="center">

# Hi, I'm Martín Salinas Scussolin 👋

### Software & Cloud Engineer

Kubernetes, Terraform and GitOps on AWS, plus the mobile and web apps that run on them.

[![Portfolio](https://img.shields.io/badge/Portfolio-x--muramasa.dev-C9A227?style=for-the-badge)](https://x-muramasa.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-xmuramasa-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/xmuramasa)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:martin.salinas.scussolin@gmail.com)

📄 **CV:** [English](https://github.com/xMuramasa/xMuramasa/releases/download/cv/en-resume-short.pdf) ([full](https://github.com/xMuramasa/xMuramasa/releases/download/cv/en-resume-long.pdf)) · [Español](https://github.com/xMuramasa/xMuramasa/releases/download/cv/es-cv-short.pdf) ([completo](https://github.com/xMuramasa/xMuramasa/releases/download/cv/es-cv-long.pdf))

</div>

---

## About me

I'm a Software & Cloud Engineer in Santiago, Chile. At **Mynu** I'm the only infrastructure engineer: I planned,
executed and led the move of every service from ECS/Fargate to **Kubernetes (k3s)** on AWS, with all infrastructure
in **Terraform** and deploys through **ArgoCD**, and cut monthly cloud costs by about **70%**. Before that I built
Mynu's mobile and web apps from zero to production.

I use AI coding agents (Claude Code) for most of the implementation; the architecture, the review and the hand edits
are mine. At home I run a homelab and build my own tools the same way.

---

## 🚀 Work highlights

| Project                       | Technologies                                  | Impact                                                                                        |
| ----------------------------- | --------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **Kubernetes migration**      | k3s, Terraform, ArgoCD, AWS                   | Every service off ECS/Fargate, ~70% lower monthly cloud cost. Planned and led alone.          |
| **Database consolidation**    | AWS Aurora, RDS                               | Three Aurora instances merged into one RDS instance.                                          |
| **GitOps CI/CD**              | GitHub Actions, ArgoCD, Secrets Manager       | ARM64 images, tag write-back to the manifests repo, automated deploys, no hardcoded secrets.  |
| **Monitoring**                | Prometheus, Grafana, Alertmanager, CloudWatch | Resource-utilization tracking that guided the cost work.                                      |
| **Report generation service** | Node, SQS, S3, React-PDF                      | Queue-driven PDFs for bulk B2B distribution, tested with real users at ~150 queued reports.   |
| **AI development workflow**   | Claude Code plugins                           | Team skills from spec to issue, stacked PRs and automated review, synced org-wide.            |
| **Mynu App & web platforms**  | React Native (Expo), React, TanStack Query    | Mobile and web built from zero to production.                                                 |
| **IAM migration**             | AWS Cognito, Clerk, OAuth                     | Zero-downtime, zero-data-loss user migration with Google and Apple OAuth.                     |
| **Azure → AWS migration**     | AWS ECS/Fargate, Terraform, SQS, Lambda       | First cloud move, plus an event-driven notifications microservice.                            |

---

## 🧰 Open source

| Repo                                                                          | What it is                                                                                                 |
| ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [hermes-relay](https://github.com/xMuramasa/hermes-relay)                     | Go WebSocket relay for a self-hosted AI agent: resumable runs, device pairing, a contract-tested protocol. |
| [trismegistus-android](https://github.com/xMuramasa/trismegistus-android)     | Native Android client for the relay: Kotlin, Jetpack Compose, live tool progress and approvals.            |
| [trismegistus-mac](https://github.com/xMuramasa/trismegistus-mac)             | Native macOS client for the relay: a SwiftUI menu bar app and window, Swift 6 strict concurrency.          |
| [caduceus](https://github.com/xMuramasa/caduceus)                             | Go engine of my AI development workflow: issue → headless Claude Code run → gated PR merge queue.          |
| [news-reader](https://github.com/xMuramasa/news-reader)                       | Daily AI news briefings as schema-validated JSON editions; Bun, MongoDB, React 19, shadcn/ui.              |
| [img-transformer](https://github.com/xMuramasa/img-transformer)               | FastAPI + Pillow: convert and resize images, batches and zips, optimize for PDFs, strip backgrounds.       |
| [on-site-meeting-logger](https://github.com/xMuramasa/on-site-meeting-logger) | Local-first pipeline from meeting recordings to transcripts, minutes and validated PDFs.                   |
| [resume-generator](https://github.com/xMuramasa/resume-generator)             | JSON → Markdown, HTML and PDF. It builds the CV above from [`resume/`](resume/).                           |
| [vireo](https://github.com/xMuramasa/vireo)                                   | HLS video service with Bun, Hono, Drizzle and Vite.                                                        |

The first three are **Trismegistus**, companion apps for a self-hosted AI agent: a relay and two native clients
sharing one contract-tested protocol. **Caduceus** is the engine that builds them: it turns a ready issue into a
Claude Code run in its own worktree and lines the result up for review and merge. Private, but happy to talk about
it: the **homelab** it all runs on (25 Docker Compose containers behind Caddy, Tailscale, monitoring and restic
backups).

---

## 🛠 Tech stack

### ☁️ Cloud & platform

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### 💻 Backend & apps

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

### 🔐 Identity, data & AI

![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
