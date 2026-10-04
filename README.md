# 👋 Hi, I'm Pablo

**AI Cloud Engineer working across cloud infrastructure, DevOps and AI agents.**

At [OpenNebula Systems](https://opennebula.io), I combine hands-on engineering with technical project coordination across European cloud and AI initiatives. I deploy OpenNebula in EuroHPC's national AI Factories, such as NLAIF (Netherlands), AI:AT (Austria) and the BSC AI Factory (Spain). I work on Kubernetes integrations, self-hosted AI services and cloud deployments with research and industry partners.

Outside work, I build business automations and maintain a Kubernetes homelab. I also share what I learn through technical articles and conference talks.

[Website](https://pablodelarco.com) · [Writing](https://pablodelarco.com/writing) · [LinkedIn](https://www.linkedin.com/in/pablo-del-arco/) · [Contact](mailto:hello@pablodelarco.com)

## What I work on

- **Cloud & Kubernetes.** Deploying and operating infrastructure with OpenNebula, Kubernetes, Helm and container technologies.
- **DevOps.** GitOps, CI/CD pipelines, infrastructure automation, monitoring and reproducible deployments.
- **AI systems.** Agents, MCP integrations, RAG systems and self-hosted inference connected to real workflows.

I join these three areas by building the infrastructure, automating deployment and connecting AI systems to the tools and data they need.

## Selected projects

| Project | What I built |
| --- | --- |
| [Kubernetes Homelab](https://github.com/pablodelarco/kubernetes-homelab) | A two-node K3s cluster managed through GitOps, with ArgoCD, Cilium, Longhorn, monitoring and backups. |
| [OpenNebula Helm](https://github.com/pablodelarco/opennebula-helm) | A community-maintained Helm chart and container image for deploying the OpenNebula front-end on Kubernetes. |
| [EuroCopilot](https://github.com/pablodelarco/one-apps-eurocopilot) | A self-hosted AI coding service with an OpenAI-compatible API and optional load balancing across inference instances. |
| [Finetwork MCP](https://github.com/pablodelarco/finetwork-mcp) | An independent MCP server with read-only tools that let AI assistants query telecom invoices, services and billing. |
| [Hygraph Agent Guardrails](https://github.com/pablodelarco/hygraph-agent-guardrails) | An automated agent workflow with restricted permissions, change validation and human-controlled publication. |

## AI automation in practice

[**Arco Rooms, automating a nine-property rental business →**](https://pablodelarco.com/case-studies/arco-rooms)

I built a platform that processes invoices, reconciles rent payments, updates the owner's ledger and sends Telegram notifications when something needs attention.

Routine tasks run as deterministic pipelines, and AI handles only the steps that need judgment, such as finding signed contracts in email threads and writing the monthly missing-rent report. Payments that a rule cannot safely match, and any payment of 100 euros or more, go to a human review queue.

## How I work

I start with the workflow and requirements, then choose the infrastructure and tools around them.

My Kubernetes homelab is where I test deployments, integrations and operational changes. I use GitOps and CI/CD to make deployments repeatable, document how systems run and add monitoring to make failures visible.

For AI workflows, I define what an agent can access, what it can change and when it needs human review.

## Writing & talks

I write practical guides on Kubernetes, cloud infrastructure, DevOps and AI automation, based on projects I build and operate.

- [Technical articles](https://pablodelarco.com/writing)
- [Stop Using the Wrong CNI in 2026: Flannel vs Calico vs Cilium](https://pablodelarco.com/writing/cni-flannel-calico-cilium), featured by the Cilium community
- [Hands-on reviews of AI tools and Claude Code skills](https://pablodelarco.com/claude-skills)
- FOSDEM 2026 talk, [How I Turned a Raspberry Pi into an Open-Source Edge Cloud with OpenNebula](https://fosdem.org/2026/schedule/event/ZHE7VJ-raspberry-into-open-source-edge-cloud/)
- foss-north 2026 talk, [Multi-Cloud Without the Myth: What Actually Works in Practice](https://foss-north.se/2026/speakers-and-talks.html#parcortiz)
- NexusForum 2025 talk, listed on the [speakers page](https://nexusforum.eu/speakers-2025/)

<details>
<summary>A little more about me</summary>

- Based in Valencia, Spain.
- Previously worked as a 5G Field Verification Engineer at Nokia in Helsinki.
- Double MSc from EURECOM in France and Aalto University in Finland.
- OpenNebula Certified Expert, with training in Claude Code and Model Context Protocol.
- Away from the keyboard, I play acoustic and Spanish guitar, padel and football.

</details>
