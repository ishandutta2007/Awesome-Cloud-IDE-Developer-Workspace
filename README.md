# Awesome-Cloud-IDE-Developer-Workspace

# Top Cloud IDE & Developer Workspace Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Browser-Based Development Environments, Remote Workspaces & Cloud-Native Coding*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud IDE & Developer Workspaces**. These tools provide full development environments accessible from any browser or thin client—covering code editing, terminal access, debugging, extensions, and persistent storage—eliminating the need for local environment setup while enabling consistent, reproducible workflows across teams.

**Examples** include GitHub Codespaces, Gitpod, Replit, Codeanywhere, AWS Cloud9, Eclipse Theia, CodeSandbox, StackBlitz, Projector, and Zoho Code (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted cloud IDEs, open-source editor frameworks, and remote development infrastructure—ideal for platform engineers, developers, and organizations seeking transparent, vendor-neutral workspaces without per-core-hour cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[GitHub Codespaces](https://github.com/features/codespaces)** | Cloud development environment integrated with GitHub repositories. Supports devcontainer configuration, prebuilt environments, and VS Code in browser or desktop. Billed in core-hours (CPU cores × runtime) . | Pay-as-you-go beyond included quota; 2-core Linux ~$0.18/hour, 4-core ~$0.36/hour | **GitHub Free**: 120 core-hours/month (~60 real hours on 2-core, ~30 hours on 4-core) + 15 GB-month storage; idle timeout 30 minutes . Pro/Team/Enterprise tiers have higher quotas  |
| **[Gitpod](https://www.gitpod.io/)** | Ephemeral cloud development environments with prebuilds, multi-IDE support (VS Code, JetBrains), and Git integration. Free plan includes 500 credits/month or up to 50 hours . | Paid plans available; free tier 500 credits/month or 50 hours | **Free plan**: 500 credits/month or up to 50 hours, workspace classes, multi-IDE, prebuilds  |
| **[Replit](https://replit.com/)** | Browser-based IDE with AI Agent, hosting, and database. Starter plan is free with daily Agent allowance and limited monthly cloud credits. Core ($20/month) adds $20 monthly credits, full Agent, and unlimited published apps . | Core: $20/month ($204/year annual); Pro: $100/month | **Starter (free)**: daily Agent allowance, limited monthly cloud credits, basic Agent access, one published app; no time-limited trial for paid plans  |
| **[Codeanywhere](https://codeanywhere.com/)** | Cloud IDE with container-based workspaces, AI tokens, and on-premise deployment option for Premium. Free tier includes 4 vCPU, 8 GB RAM, 100 GB storage, 500K AI tokens, and 20 hours SGRAM . | Basic: $9.60/month (annual); Premium: $23/month (annual) | **Free plan**: 4 vCPU, 8 GB RAM, 100 GB storage, 500K AI tokens, 20 hours SGRAM, 1 parallel workspace, 15-min inactivity timeout  |
| **[AWS Cloud9](https://aws.amazon.com/cloud9/)** | Browser-based IDE with terminal, debugger, and AWS CLI pre-installed. No additional charge for Cloud9 itself—pay only for underlying EC2/EBS resources. Can connect to existing Linux servers via SSH at no extra cost . | Free IDE; pay only for AWS resources (e.g., t2.micro ~$0.0116/hour, EBS ~$0.10/GB-month) | **AWS Free Tier eligible**: new AWS customers can use Cloud9 free within Free Tier limits; example 90-hour month on t2.micro costs ~$2.05 total (compute + storage)  |
| **[CodeSandbox](https://codesandbox.io/)** | Cloud development platform with browser sandboxes and VM-based workspaces. Free tier provides 400 monthly credits (enough for ~40 hours on Nano VM for a small React app) and 20 sandboxes per workspace . | Pro plans available; free tier 400 credits/month | **Free tier**: 400 monthly credits (~40 hours on Nano VM), 20 sandboxes per workspace; sandboxes (non-VM) don't consume credits  |
| **[StackBlitz](https://stackblitz.com/)** | Browser-based IDE using WebContainers (Node.js in browser). Personal plan is free with unlimited public projects and core browser IDE features . | Personal: Free; Pro/Teams tiers available | **Personal (free)**: unlimited public projects, core browser IDE features, 1 MB file upload limit, GitHub repo access, local backend connections, CORS API access  |
| **[Eclipse Theia](https://theia-ide.org/)** | Open-source, AI-native IDE that runs on desktop and in the cloud. Core framework is free forever; commercial offerings (managed hosting, enterprise support) typically start around $20/user/month . | Core framework: free (open-source); managed/enterprise: ~$20/user/month | **Free forever**: Theia IDE core is open-source and free; commercial cloud/support offerings are paid  |
| **[Projector](https://www.jetbrains.com/projector/)** | JetBrains' remote development solution for running IntelliJ-based IDEs on a server and accessing them via browser or thin client. | Included with JetBrains IDE licenses | No separate free tier; requires JetBrains IDE subscription |
| **[Zoho Code](https://www.zoho.com/)** | Cloud IDE within Zoho's developer ecosystem (limited public pricing information available; part of broader Zoho platform). | Included with Zoho platform access | Contact Zoho for current availability and limits |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Eclipse Theia](https://github.com/eclipse-theia/theia)** | [![Stars](https://img.shields.io/github/stars/eclipse-theia/theia?style=social&color=white)](https://github.com/eclipse-theia/theia/stargazers) | Open-source, vendor-neutral IDE framework for desktop and cloud. Built on TypeScript, supports VS Code extensions, and serves as the foundation for many commercial cloud IDEs. |
| **[code-server](https://github.com/coder/code-server)** | [![Stars](https://img.shields.io/github/stars/coder/code-server?style=social&color=white)](https://github.com/coder/code-server/stargazers) | Run VS Code on a remote server, accessible via browser. Self-hosted alternative to GitHub Codespaces; supports extensions, terminal, and persistent storage. |
| **[OpenVSCode Server](https://github.com/gitpod-io/openvscode-server)** | [![Stars](https://img.shields.io/github/stars/gitpod-io/openvscode-server?style=social&color=white)](https://github.com/gitpod-io/openvscode-server/stargazers) | Gitpod's fork of VS Code optimized for server use. Minimal modifications to upstream VS Code; serves as the editor layer for Gitpod and can be self-hosted. |
| **[JupyterLab](https://github.com/jupyterlab/jupyterlab)** | [![Stars](https://img.shields.io/github/stars/jupyterlab/jupyterlab?style=social&color=white)](https://github.com/jupyterlab/jupyterlab/stargazers) | Web-based interactive development environment for notebooks, code, and data. Widely used for data science and scientific computing in cloud environments. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Eclipse Che](https://github.com/eclipse-che/che)** | [![Stars](https://img.shields.io/github/stars/eclipse-che/che?style=social&color=white)](https://github.com/eclipse-che/che/stargazers) | Kubernetes-native IDE and developer workspace server. Provides browser-based VS Code-like experience with containerized workspaces. |
| **[Coder](https://github.com/coder/coder)** | [![Stars](https://img.shields.io/github/stars/coder/coder?style=social&color=white)](https://github.com/coder/coder/stargazers) | Self-hosted cloud development environment platform. Provisions remote workspaces on your infrastructure with Terraform-based templates. |
| **[DevPod](https://github.com/loft-sh/devpod)** | [![Stars](https://img.shields.io/github/stars/loft-sh/devpod?style=social&color=white)](https://github.com/loft-sh/devpod/stargazers) | Client-only codespaces implementation. Works with any IDE and any cloud—self-hosted alternative to GitHub Codespaces without vendor lock-in. |

**Frameworks for building custom systems**: Combine **code-server** or **OpenVSCode Server** for browser-based VS Code, **Eclipse Theia** for a customizable IDE framework, and **Coder** or **DevPod** for workspace orchestration—creating a fully self-hosted cloud IDE environment on Kubernetes or bare-metal infrastructure.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud IDEs execute arbitrary code and expose terminal access; enforce proper authentication, network isolation, and workspace cleanup to prevent resource abuse.
- Core-hour billing (GitHub Codespaces) can consume quotas faster than expected on multi-core machines; idle timeout settings and manual stop discipline are essential to stay within free tier limits.

---

**Made for developers, platform engineers, DevOps teams, and organizations building remote development infrastructure.**  
Let's make cloud IDE and developer workspaces more open, accessible, and cost-transparent.
