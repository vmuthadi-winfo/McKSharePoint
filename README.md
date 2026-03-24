# MRx Nexus — Data & AI Center of Excellence

**MRx Nexus** is the knowledge portal for the **MomentimRx Data & AI Center of Excellence (CoE)** — a centralized engineering and AI delivery model that standardizes, governs, and accelerates how data, analytics, and AI capabilities are built and reused across MomentimRx and the broader CSI organization.

> 🔗 SharePoint URL: **mckessoncorp.sharepoint.com/sites/MRXNexusCOE**  
> 📄 Enterprise Standards v1.0 — March 2026  
> 🏢 MomentimRx | © 2025 McKesson Corporation | McKesson Proprietary and Confidential

---

## Site Structure — Four Pages

| Page | File | CoE Pillars | Description |
|------|------|-------------|-------------|
| 🏠 **Home** | `index.html` | All 13 | Vision, mission, strategic objectives, 13 pillars overview, get-connected guide |
| 📊 **Data & AI** | `data-ai.html` | 1–7 & 13 | NFR, Dev Framework, Data Management, Testing, Error Handling, CI/CD, Governance, AI |
| ⚙️ **Infrastructure & DevOps** | `infrastructure-devops.html` | 8–11 | Infrastructure, Ops Readiness, Cost Avoidance, Observability |
| 🔒 **Security** | `security.html` | 12 | Panorama, Wiz Cloud, GitHub Security, Compromised Data Monitoring |

---

## 13 CoE Pillars

| # | Pillar | Key Topics |
|---|--------|-----------|
| 1 | 📋 NFR & Standards | Tagging · RTO/RPO · SLAs · HA/DR · LeanIX · CMDB · AS Numbers |
| 2 | ⚙️ Dev Framework | Config-Driven Pipelines · Ingestion Tools · AI-Assisted Dev · SonarQube |
| 3 | 🗄️ Data Management | Modeling · Unity Catalog · Medallion Layers · Partitioning · Vacuuming |
| 4 | 🧪 Testing | DQ Framework · Unit Testing · Integration · Contracts · Schema Validation |
| 5 | 🚨 Error Handling | Audit Logs · Exception Logs · Error Reporting · Alerting · Retry Policy |
| 6 | 🔄 CI/CD | Asset Bundles · Git Workflows · Feature Flags · Approval Gateway |
| 7 | 🏛️ Data Governance | Lineage Extraction · Glossary · Alation · Table & View Definitions |
| 8 | 🔧 Ops Readiness | Change Mgmt · Incident Mgmt · Jira · ServiceNow · SOX/SOC Auditing |
| 9 | 🏗️ Infrastructure | Terraform IaC · Compute Policies · Tagging · Cluster Resizing |
| 10 | 💰 Cost Avoidance | FinOps · Chargeback Model · Right-Sizing · Auto-Termination |
| 11 | 📊 Observability | Grafana Dashboards · Azure Monitor · SLA Tracking · Distributed Tracing |
| 12 | 🔒 Security | Panorama · Wiz Cloud · GitHub Security Scanner · Zero Trust · RBAC |
| 13 | 🤖 AI Enablement | Azure OpenAI · GitHub Copilot · Claude · MCP Servers · Databricks Assistant |

---

## Source Documents

The content in this portal is derived from two primary source documents:

| File | Contents |
|------|---------|
| `Data_AI_CoE_SharePoint_Content.docx` | Detailed CoE content for all 13 pillars — tables, standards, frameworks |
| `Data_AI_CoE_Slides.pptx` | Executive overview — vision, objectives, pillar summaries, Nexus portal intro |

---

## Deploying to SharePoint

See **[`SHAREPOINT_DEPLOYMENT_GUIDE.md`](SHAREPOINT_DEPLOYMENT_GUIDE.md)** for complete step-by-step instructions to:

1. Create a new SharePoint Communication Site at `mckessoncorp.sharepoint.com/sites/MRXNexusCOE`
2. Configure site settings, navigation, theme, and permissions
3. Build all four pages using SharePoint web parts (with exact content from the HTML files)
4. Upload source documents to the Document Library
5. Set up the News feed for CoE announcements
6. Run the pre-launch checklist and announce to the team

---

## Local Preview

Open `index.html` in any modern browser to preview the portal locally. All pages are static HTML/CSS — no build step or server required.
