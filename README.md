# Awesome-Cloud-Development-Environment

# Awesome-Cloud-Development-Environment



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cloud IDEs, Remote Workstations, Reproducible Environments & Agent-Ready Workspaces*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Development Environments (CDEs)**. These tools help developers code, build, test, and debug in fully configured environments hosted in the cloud—accessible from any device, with zero local setup.



**Examples** include Visual Studio Codespaces, GitHub Codespaces, Gitpod, AWS Cloud9, Google Cloud Workstations, Replit, CodeSandbox, StackBlitz, Coder, and Eclipse Che (the category leaders).



**Open-source emphasis**: The CDE ecosystem has **matured dramatically in 2026**, with open-source alternatives closing the gap on hosted platforms. **Coder** (AGPL-3.0) leads self-hosted enterprise deployments with unlimited free workspaces and AI agent governance . **Gitpod** supports any Git host (GitHub, GitLab, Bitbucket, Gitea) and can be self-hosted . **DevPod** (client-only, DevContainer standard) costs **5-10x less** than hosted services by using bare cloud VMs . **Eclipse Che** (EPL-2.0, Kubernetes-native) and **Daytona** (AGPL-3.0, 14,000+ stars) provide additional production-grade options . This section documents these solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global Cloud Development Environment market is estimated at **~$6.65B in 2026**, growing toward **~$25B by 2035** at a **~14.2% CAGR** . The IDE-as-a-Service segment alone is projected at **$4.2B in 2026**, reaching **$7.2B by 2030** at **14.4% CAGR** . The sector is **moderately fragmented** — GitHub Codespaces benefits from GitHub's distribution, Gitpod competes on open-source flexibility, and Coder leads self-hosted enterprise deployments. A key 2025-2026 trend: **VDI renewal sticker shock** (Citrix +50%, VMware "thousands of percent") is driving enterprises to CDEs as a modern alternative . No single vendor holds a winner-take-all position; enterprises typically run multi-CDE strategies.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[GitHub Codespaces](https://github.co.jp/features/codespaces?source=post_page-----8c46ebe4994e--------------------------------)** | Deeply integrated with GitHub repositories, PRs, and Actions. Uses DevContainer standard. | **2-core**: **$0.18/hour** . **4-core**: **$0.36/hour**. **8-core**: **$0.72/hour**. Storage: **$0.07/GB/month** . | **Free (personal)**: **120 core-hours/month** (~60 real hours on 2-core) . **Pro**: higher quota. Idle timeout: 30 min default . | **~$331.8B revenue (Microsoft FY2026)** |

| **[Gitpod](https://www.gitpod.io/)** | Open-source, any Git host (GitHub, GitLab, Bitbucket, Gitea). Flat monthly pricing. | **Individual**: **$9/month** (100 hrs) or **$25/month** (unlimited) . **Team**: **$15/user/month** . | **Free tier**: **50 hours/month** . **Self-hosted**: Yes (open source). | **Private (~$100M+ raised)** |

| **[Google Cloud Workstations](https://cloud.google.com/workstations)** | Managed, container-based development environments on Google Cloud. Persistent storage per workstation. | **$0.05/hour per vCPU** management fee + underlying Compute costs (us-central1) . Billed per second . | **Google Cloud Free Tier**: **$300 credit for 90 days**. No perpetual free tier. | **~$350B revenue (Alphabet FY2025)** |

| **[AWS Cloud9](https://aws.amazon.com/cloud9/)** | Browser-based IDE with deep AWS integration. Uses EC2 instances for compute. | **Cloud9 itself: Free** . You pay only for underlying **EC2/EBS resources** used . | **AWS Free Tier**: New customers can use Cloud9 free if environment uses free-tier resources. **t2.micro**: 750 hours/month for 12 months . | **~$638B revenue (Amazon FY2025)** |

| **[Replit](https://replit.com/)** | Browser-based IDE with AI Agent. Popular for education and rapid prototyping. | **Core**: **$20/month** (includes $20 credits) . **Pro**: **$100/month** (more credits, parallel agents) . Annual: Core **$204/year** . | **Starter**: Free with daily Agent allowance and limited monthly cloud credits . **No paid trial** but Starter is free indefinitely . | **Private (~$1.16B valuation est.)** |

| **[CodeSandbox](https://codesandbox.io/)** | Instant cloud VMs with memory snapshotting. Acquired by Together AI. | **VM Sandboxes**: **Pico** (2 cores, 1GB): **$0.0743/hour** . **Nano** (2 cores, 4GB): **$0.1486/hour**. **Micro** (4 cores, 8GB): **$0.2972/hour** . | **Free**: **400 credits/month** per workspace (1 credit = $0.01486/hour) . **Pro**: 1,000 credits/month . Sandboxes don't count toward credits . | **Acquired by Together AI (2024)** |

| **[StackBlitz](https://stackblitz.com/)** | Browser-based IDE powered by WebContainers. Boots Node.js in milliseconds. | **Pro**: **$18/month** (billed annually) or **$25/month** . **Teams**: **$55/member/month** (annual) or **$60/month** . | **Personal**: Free with unlimited public projects, 1MB file upload per project . | **Private (~$7.9M raised)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[Coder](https://github.com/coder/coder)** — **Leading self-hosted CDE platform.** Terraform-based workspace provisioning, unlimited free workspaces, AI agent governance. AGPL-3.0. **Community tier is free forever** for hobbyists and small teams . | [![Stars](https://img.shields.io/github/stars/coder/coder?style=social&color=white)](https://github.com/coder/coder/stargazers) | ~12,000 |

| **[Daytona](https://github.com/daytonaio/daytona)** — **Open-source dev environment manager.** Single-command setup, runs on any machine/cloud, DevContainer support, built-in VPN security. AGPL-3.0. **14,043 stars** . | [![Stars](https://img.shields.io/github/stars/daytonaio/daytona?style=social&color=white)](https://github.com/daytonaio/daytona/stargazers) | ~14,000 |

| **[DevPod](https://github.com/loft-sh/devpod)** — **Client-only CDE using DevContainer standard.** Any backend (local, K8s, SSH, cloud VM). **5-10x cheaper** than hosted services. No vendor lock-in. 100% open source . | [![Stars](https://img.shields.io/github/stars/loft-sh/devpod?style=social&color=white)](https://github.com/loft-sh/devpod/stargazers) | ~14,000 |

| **[Eclipse Che](https://github.com/eclipse-che/che)** — **Kubernetes-native IDE and developer collaboration platform.** Multi-container workspaces, browser-based VS Code, enterprise OIDC integration. EPL-2.0 . | [![Stars](https://img.shields.io/github/stars/eclipse-che/che?style=social&color=white)](https://github.com/eclipse-che/che/stargazers) | ~7,000 |

| **[code-server](https://github.com/coder/code-server)** — **Run VS Code on a remote server, access via browser.** The foundation for many self-hosted CDE setups. MIT . | [![Stars](https://img.shields.io/github/stars/coder/code-server?style=social&color=white)](https://github.com/coder/code-server/stargazers) | ~69,000 |

| **[OpenVSCode Server](https://github.com/gitpod-io/openvscode-server)** — **Lightweight VS Code in the browser.** Single binary, ~1GB RAM, no Docker needed. MIT . | [![Stars](https://img.shields.io/github/stars/gitpod-io/openvscode-server?style=social&color=white)](https://github.com/gitpod-io/openvscode-server/stargazers) | ~25,000 |



**Additional open-source options worth exploring:**



| Repo | Description |

|---|---|

| **[DevPod Desktop](https://devpod.sh/)** — Desktop app for DevPod with GUI. Abstracts CLI complexity . | [![DevPod](https://img.shields.io/badge/DevPod-Desktop-blue)](https://devpod.sh/) |

| **[Eclipse Che hosted by Red Hat](https://eclipse.dev/che/docs/stable/hosted-che/hosted-che/)** — Free hosted Che with 80GB storage, 30GB RAM, 1 concurrent workspace, 30-day active period . | [![Red Hat](https://img.shields.io/badge/Red%20Hat-Hosted%20Che-red)](https://eclipse.dev/che/docs/stable/hosted-che/hosted-che/) |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud development environments handle source code and development credentials; ensure proper access controls, secret management, and compliance with organizational security policies.

- **Open-source reality**: The CDE ecosystem has **matured dramatically in 2026**. **Coder** leads self-hosted enterprise deployments with **unlimited free workspaces** and AI agent governance, with a free Community tier for small teams . **Gitpod** supports any Git host and can be self-hosted . **DevPod** is **client-only** and costs **5-10x less** than hosted services by using bare cloud VMs . **Eclipse Che** is Kubernetes-native with enterprise OIDC integration . **Daytona** has **14,000+ stars** and single-command setup . **code-server** and **OpenVSCode Server** provide the browser-based VS Code foundation. The open-source path is **genuinely viable** for organizations seeking full data sovereignty, cost control, and freedom from vendor lock-in.

- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. Cloud provider costs (compute, storage, egress) are often billed separately. Always request a formal quote for accurate budgeting.



---



**Made for platform engineers, DevOps leads, developer experience teams, and infrastructure architects.**

Let's make cloud development environments more open, reproducible, and cost-effective.
