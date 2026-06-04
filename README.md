<div align="center">

# Hi, I'm Daniele 👋

[![Website](https://img.shields.io/badge/daniele--dev.com-0a0e1a?style=for-the-badge&logo=About.me&logoColor=white)](https://daniele-dev.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniele-d-annibale-a00792264/)
[![GitHub followers](https://img.shields.io/github/followers/DanieleDAnnibale?style=for-the-badge&logo=github)](https://github.com/DanieleDAnnibale)

</div>

---

## About Me

Java Backend Developer with a focus on architecture and cloud infrastructure.  
I build and maintain a self-hosted **k3s cluster** managed entirely via GitOps — from containerised applications
and full observability stacks to game servers and AI tooling.

- Full-stack applications in production: **[Time-Ledger](https://time-ledger.daniele-dev.com)** and **[Trek](https://trek.daniele-dev.com)**
- Deep hands-on with **observability**: OpenTelemetry traces, Loki logs, Prometheus metrics — all wired into Grafana
- Self-hosted **k3s cluster** (Fleet + Kustomize) with GitOps-only changes — no manual `kubectl` in prod
- Personal knowledge base in Obsidian with 100+ notes, Dataview queries and a live knowledge graph
- Always learning — from distributed systems to LLMs and AI agents

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frameworks & Libraries**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

**Infrastructure & Data**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Observability**

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

---

## GitHub Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=DanieleDAnnibale&theme=dark&hide_border=true)](https://github.com/DanieleDAnnibale)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=DanieleDAnnibale&theme=github-compact&hide_border=true)](https://github.com/DanieleDAnnibale)

</div>

---

## Projects

### [Time-Ledger](https://time-ledger.daniele-dev.com) · `production`

Full-stack time-tracking app designed, built and deployed on my own cluster.

**Stack:** Python 3.13 · FastAPI · Angular 21 · PostgreSQL · Zitadel OIDC

- Automated overtime calculation, PTO/ROL accrual, configurable widget dashboard, multi-user admin panel
- RBAC via Zitadel JWT claims; OIDC authentication with PKCE flow
- Exposes Prometheus metrics; pushes traces and logs via **OTLP** → OTel Collector → Tempo + Loki → Grafana
- CI/CD through self-hosted GitHub ARC runners — every push to `main` builds, pushes and deploys

---

### [Trek](https://trek.daniele-dev.com) · `production`

Self-hosted travel tracking app with interactive maps and place enrichment.

**Stack:** Node.js · Mapbox GL · Google Places API · Open-Meteo · Zitadel OIDC

- Interactive trip logging, weather data, place enrichment from Google Places
- Restricted access: only authorised Zitadel users can log in

---

### Self-hosted k3s Cluster

Home-lab **k3s** cluster where everything is declared in Git.  
GitOps via **Rancher Fleet** + **Kustomize** (base + environment overlays). Zero manual `kubectl apply` in production.

| Category | What's running |
|---|---|
| **Applications** | Time-Ledger, Trek, Docling (GPU/AI), JSON Résumé, FossFlow, Stirling-PDF |
| **Identity & Access** | Zitadel (OIDC/IdP) · Cloudflare Tunnel · WARP Zero Trust · cert-manager · Sealed Secrets |
| **Observability** | Prometheus · Grafana · Loki · Tempo · Alloy · OTel Operator + Collector · kube-state-metrics · node-exporter · DCGM Exporter |
| **Infrastructure** | Traefik · GitHub ARC runners · NVIDIA device plugin · private registry · Rancher Backup → Cloudflare R2 |
| **Game Servers** | Minecraft (Paper 1.21) · Palworld · Satisfactory |

---

## Interests

- **Infrastructure & DevOps** — self-hosted services, GitOps, homelab
- **Artificial Intelligence** — LLMs, agents, knowledge graphs
- **Gaming** — server management, modding
- **Music** — always in the background while coding

---

## Let's Connect

📎 Portfolio & homelab: **[daniele-dev.com](https://daniele-dev.com)**  
💼 Professional: **[LinkedIn](https://www.linkedin.com/in/daniele-d-annibale-a00792264/)**

Open to collaborating on infrastructure, backend, or tooling projects — feel free to reach out or open an issue on any of my repos!
