# Awesome-Cloud-IDE-Developer-Workspace

## Top Cloud IDE & Developer Workspace Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Browser-Based Development Environments, Remote Workspaces & Cloud-Native Coding*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud IDE & Developer Workspaces**. These tools provide full development environments accessible from any browser or thin client—covering code editing, terminal access, debugging, extensions, and persistent storage—eliminating the need for local environment setup while enabling consistent, reproducible workflows across teams.

**Examples** include GitHub Codespaces, Gitpod, Replit, Codeanywhere, AWS Cloud9, Eclipse Theia, CodeSandbox, StackBlitz, Projector, and Zoho Code (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted cloud IDEs, open-source editor frameworks, and remote development infrastructure—ideal for platform engineers, developers, and organizations seeking transparent, vendor-neutral workspaces without per-core-hour cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Cloud IDE & Developer Workspace market is estimated at **$6.8 billion in 2025** and is projected to expand to **$28.4 billion by 2034**, advancing at a compound annual growth rate (CAGR) of **17.2%** driven by remote engineering teams and native cloud AI coding agents. The sector exhibits **moderate-to-high concentration** at the infrastructure layer (dominated by hyperscalers like Microsoft/GitHub and AWS), yet remains **fragmented across specialized niches**—where specialized browser runtime providers (StackBlitz WebContainers), collaborative AI-native environments (Replit), and self-hosted developer workspace orchestrators (Coder) capture distinct developer workflows.

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|------------------------------------|-------------|-------------------|--------------------------|
| **[AWS Cloud9](https://aws.amazon.com/cloud9/)** | **~$2.1T+ Market Cap** (Amazon / AWS: ~$105B+ ARR) | Browser-based IDE with terminal, debugger, and AWS CLI pre-installed. No additional charge for Cloud9 itself—billed strictly for underlying compute/storage. | $0.0116/hour (e.g. t2.micro EC2 compute; ~$2.05/month for 90 hrs) | **AWS Free Tier (12 months)**: 750 hours/month of t2.micro/t3.micro instances + 30 GB EBS storage for new AWS customers. |
| **[GitHub Codespaces](https://github.com/features/codespaces)** | **~$3.0T+ Market Cap** (Parent: Microsoft / GitHub: ~$2B+ ARR) | Cloud development environment integrated with GitHub repositories. Supports devcontainer configuration, prebuilt environments, and VS Code in browser or desktop. | $0.18/hour (2-core Linux pay-as-you-go beyond free allowance; $0.36/hour for 4-core) | **Free forever**: 120 core-hours/month (~60 hours on 2-core, ~30 hours on 4-core) + 15 GB-month storage; idle timeout 30 minutes. |
| **[Zoho Code](https://www.zoho.com/)** | **~$12B–$15B Est. Valuation** (~$1.5B ARR) | Cloud development and scripting environment embedded within the Zoho enterprise application ecosystem. | $8.00/user/month (billed annually, Zoho Creator Standard tier) | **15-day free trial**: Unrestricted access to full features without credit card; permanent free tier limited to 1 user, 1 app, and 250 MB storage. |
| **[Replit](https://replit.com/)** | **~$3.0B Valuation** (~$100M+ ARR) | Browser-based collaborative IDE featuring autonomous AI Agents, instant hosting, and managed databases. | $20.00/month (Core tier; $204/year billed annually) | **Starter (free forever)**: Basic Agent access, daily AI allowance, limited monthly cloud compute credits, and 1 published application. |
| **[StackBlitz](https://stackblitz.com/)** | **~$700M Valuation** (~$20M ARR) | In-browser WebContainer-powered IDE running Node.js and client runtimes with near-instant boot times. | $25.00/month (Pro tier; $18/month billed annually) | **Personal (free forever)**: Unlimited public projects, core WebContainer browser IDE features, GitHub repo access, and 1 MB file upload limit. |
| **[Projector](https://www.jetbrains.com/projector/)** | **~$700M–$800M Annual Revenue** (JetBrains, bootstrapped) | JetBrains' server-side rendering technology for running Swing and IntelliJ-based IDEs on remote servers via web browser. | $79.00/year (WebStorm individual license; or $299/year for All Products Pack) | **30-day free trial**: Full unrestricted access to JetBrains IDEs without feature throttling; Projector server/client components are free open-source software. |
| **[Gitpod](https://www.gitpod.io/)** | **~$100M–$200M Est. Valuation** ($41M funding raised; ~$8.6M ARR) | Automated ephemeral cloud development environments supporting devcontainers, prebuilds, and multi-IDE interfaces. | $20.00/month (Core tier supporting hosted compute and multi-IDE) | **Free forever**: 500 workspace credits/month (~up to 50 hours of compute), standard workspace classes, and GitHub/GitLab integration. |
| **[CodeSandbox](https://codesandbox.io/)** | **~$51M Valuation** (Acquired by Together AI; $15.2M funding raised) | Cloud development platform pairing client sandboxes with remote microVM-based developer workspaces. | $12.00/month (Pro tier; $9/month billed annually) | **Free forever**: 400 monthly VM credits (~40 hours on Nano VM), up to 20 sandbox repositories per workspace; static sandboxes do not consume credits. |
| **[Eclipse Theia](https://theia-ide.org/)** | **Non-profit Foundation** (~€13M annual budget; Eclipse Foundation) | Open-source, vendor-neutral IDE platform running both in browser and desktop, with managed cloud distributions from ecosystem partners. | $20.00/user/month (commercial managed hosting/support offerings from partners like TypeFox) | **Free forever**: 100% free open-source Eclipse Public License (EPL-2.0) software for self-hosting with no user caps. |
| **[Codeanywhere](https://codeanywhere.com/)** | **~$1M–$3M Est. Valuation** ($813K funding raised; ~$1.5M ARR) | Cloud development environment providing containerized Linux workspaces with built-in AI completion and terminal access. | $9.60/month (Basic tier, billed annually; or $12/month billed monthly) | **Free forever**: 4 vCPU, 8 GB RAM, 100 GB storage, 500K AI tokens, 20 hours SGRAM, and 1 parallel workspace (15-min inactivity timeout). |

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
