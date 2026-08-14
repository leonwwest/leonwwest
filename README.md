# Leon Westermeir

Microsoft, Infrastructure & Automation Engineer with a systems integration background and a
B.Sc. in International Information Systems.

I work across Microsoft 365, Entra ID, Windows infrastructure, networking and security, and I
automate repeatable operations with PowerShell and Python. I am open to full-time Microsoft 365,
IT System Engineering, Infrastructure, Cloud and Application Operations roles around Augsburg,
hybrid in Munich or remote across Germany.

[Portfolio and project overview](https://ibmw-automations.de)

## Core portfolio

| Project | Engineering evidence | Stack |
|---|---|---|
| [Leon Work OS](https://ibmw-automations.de/#projekte) *(private repository)* | Personal operator system with task registry, workspace routing, guardrails, recovery checkpoints, backups and runbooks; operated on my own Mac/Linux infrastructure | Python, SQLite, macOS, Linux, automation |
| [Azure & M365 Tenant Guard](https://github.com/leonwwest/azure-m365-automation-lab) | Sanitized tenant inventory, deterministic governance checks, evidence reports and approval-gated remediation | Python, PowerShell, Azure/M365 |
| [Azure Platform IaC Lab](https://github.com/leonwwest/azure-platform-iac-lab) | Terraform, secretless GitHub OIDC, managed identity, Key Vault RBAC, monitoring, cost controls and gated apply | Terraform, Azure Container Apps, Entra ID, GitHub Actions |
| [GitOps Platform Lab](https://github.com/leonwwest/gitops-platform-lab) | Tested service delivery, Git reconciliation, policy controls, SLOs, observability and recovery exercises | Kubernetes, Argo CD, Kustomize, Prometheus |
| [Incident Automation Lab](https://github.com/leonwwest/slow-ai-app-incident-lab) | Metrics, logs, traces, alerting and explainable SEV triage with safe dry-run actions | FastAPI, Grafana, Loki, OpenTelemetry |
| [Data Quality Pipeline](https://github.com/leonwwest/operations-kpi-automation-demo) | Versioned data contract, quality gates, quarantine, lineage and operational KPIs | Python, FastAPI, Power BI, n8n |

## What I bring

- Automate Azure/M365 inventory, evidence and governance workflows.
- Operate a private task and automation control plane with recovery and explicit approval boundaries.
- Provision small Azure platforms with Terraform, workload identity and approval-gated delivery.
- Package and operate Python services through containers, Kubernetes and GitOps.
- Build versioned ETL pipelines with data-quality controls and operational reporting.
- Add metrics, logs, traces, alerts, incident triage and operator-focused runbooks.
- Learn unfamiliar systems quickly and turn the result into repeatable, documented operations.

## Engineering approach

Every core project is designed to be inspectable: public repositories explain what is automated,
how it is verified, which decisions were made and where a production implementation would need
additional controls. The public projects are reproducible portfolio labs, not claims of operating
a real customer tenant or production cluster. Leon Work OS is a separate private system operated
on my own infrastructure.

The fastest review path is: start with the [portfolio](https://ibmw-automations.de), then inspect
the [Azure & M365 Tenant Guard](https://github.com/leonwwest/azure-m365-automation-lab) and the
[Azure Platform IaC Lab](https://github.com/leonwwest/azure-platform-iac-lab). The public repositories
include real execution captures, automated verification and explicit production limitations.

## Additional work

- [WhatsApp School Assistant](https://github.com/leonwwest/whatsapp-school-assistant-demo) — grounded AI automation with source retrieval, safety checks and human handoff. [Live demo](https://whatsapp-school-assistant-demo.vercel.app)
- [CloudScrobble iOS](https://github.com/leonwwest/cloudscrobble-ios) — Swift/iOS client, Go token broker, Cloudflare Worker and Keychain-backed offline queue.
- [Repo Audio Summary](https://github.com/leonwwest/repo-audio-summary) — local macOS automation for Git summaries and Telegram briefings.
