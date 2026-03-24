# MRx Nexus — SharePoint Communication Site Deployment Guide

**Site Name:** MRx Nexus — Data &amp; AI Center of Excellence  
**Site URL:** `https://mckessoncorp.sharepoint.com/sites/MRXNexusCOE`  
**Template:** SharePoint Communication Site  
**Document Version:** 1.0 — March 2026  
**Prepared by:** MRx CoE Team

---

## Overview

This guide walks you step-by-step through creating the **MRx Nexus SharePoint Communication Site** and populating it with the four-section CoE knowledge portal content. No custom development or elevated admin permissions are required — all steps use standard SharePoint Online features available to Site Owners.

---

## Prerequisites

Before you begin, ensure you have:

- [ ] A **Microsoft 365 account** at `mckessoncorp.sharepoint.com` with SharePoint site creation rights
- [ ] The HTML files from this repository (`index.html`, `data-ai.html`, `infrastructure-devops.html`, `security.html`, `styles.css`) saved locally
- [ ] The Word document `Data_AI_CoE_SharePoint_Content.docx` and slides `Data_AI_CoE_Slides.pptx` saved locally
- [ ] **Site Owner** or **SharePoint Admin** role — request from your IT admin if needed
- [ ] A modern browser (Edge, Chrome, Firefox) with McKesson SSO active

---

## Part 1 — Create the SharePoint Communication Site

### Step 1: Navigate to SharePoint Home

1. Open your browser and go to: `https://mckessoncorp.sharepoint.com`
2. Sign in with your McKesson SSO credentials (MFA if prompted)
3. Click the **waffle menu** (⊞) in the top-left and select **SharePoint**
4. You will land on the SharePoint Home page

### Step 2: Create a New Site

1. Click **+ Create site** (top-left of SharePoint Home)
2. Select **Communication site** (not Team site)
3. Choose the **Blank** template (gives the most layout flexibility)
4. Click **Use template**

### Step 3: Configure Site Details

Fill in the site creation form:

| Field | Value |
|-------|-------|
| **Site name** | `MRx Nexus` |
| **Site description** | `Data & AI Center of Excellence — CoE standards, frameworks, and best practices for data engineering and AI delivery across MomentimRx` |
| **Site address** | `MRXNexusCOE` (gives URL: `mckessoncorp.sharepoint.com/sites/MRXNexusCOE`) |
| **Language** | English (United States) |
| **Privacy settings** | Private — only added members can access |
| **Time zone** | (UTC-05:00) Eastern Time |

5. Click **Next**
6. Add site owners: yourself + any co-owners from the MRx CoE team
7. Add site members: all MRx team members (or use an AD security group)
8. Click **Finish** — SharePoint will provision the site (takes ~2 minutes)

---

## Part 2 — Configure Site Settings and Navigation

### Step 4: Set the Site Logo

1. Go to your new site: `https://mckessoncorp.sharepoint.com/sites/MRXNexusCOE`
2. Click the **gear icon (⚙️)** → **Change the look**
3. Click **Header** and upload an MRx / McKesson branded logo image
4. Set the header layout to **Compact** for a clean navigation bar
5. Click **Save**

### Step 5: Set the Site Theme

1. Gear icon → **Change the look** → **Theme**
2. Select **Navy** or **Dark Blue** to match McKinsey/McKesson brand colours
3. Alternatively, use **Custom** and set:
   - Primary colour: `#051c2c` (McKesson dark navy)
   - Secondary colour: `#00a3e0` (McKesson accent blue)
4. Click **Save**

### Step 6: Configure Top Navigation

1. Click **Edit** in the top navigation bar (or click **…** → **Edit navigation**)
2. Remove default links
3. Add the following navigation links:

| Label | URL / Target |
|-------|-------------|
| 🏠 Home | `/sites/MRXNexusCOE` |
| 📊 Data & AI | `/sites/MRXNexusCOE/SitePages/Data-and-AI.aspx` |
| ⚙️ Infrastructure & DevOps | `/sites/MRXNexusCOE/SitePages/Infrastructure-and-DevOps.aspx` |
| 🔒 Security | `/sites/MRXNexusCOE/SitePages/Security.aspx` |

4. Click **Save**

---

## Part 3 — Create the Four Site Pages

### Step 7: Create the Home Page

1. The site comes with a default home page — click **Edit** (top-right pencil icon)
2. Click **Discard** any existing content and start fresh, OR use the existing blank page
3. Click the **title area** at the top:
   - Title: `MRx Nexus — Data & AI Center of Excellence`
   - Description: `A centralized engineering and AI delivery model established by MomentimRx to standardize, govern, and accelerate Data & AI capabilities`
   - Layout: **Image and title** or **Color block** — choose Dark (navy)
   - Click the image placeholder and upload an MRx banner image

4. **Adding the Nexus Definition section:**
   - Click **+** to add a web part → choose **Text**
   - Paste the definition block:
     > **nex·us** /ˈnekʷsəs/ · noun
     > In healthcare and enterprise data contexts, nexus denotes the central hub, convergence point, or core node where data streams, clinical systems, and operational teams intersect and align.
     > *"MRx Nexus is the core for a successful data and AI operational model within the organization."*
   - Format as a highlighted quote using the **Quote** text style

5. **Mission Box:**
   - Add a **Text** web part with the background colour set to dark blue
   - **OUR MISSION:** To establish and govern enterprise-wide standards, frameworks, and best practices for Data & AI engineering — enabling scalable, secure, and high-quality data platform delivery across the organization.

6. **Strategic Objectives (5 cards):**
   - Add a **Quick links** web part
   - Layout: **Compact** or **Button**
   - Add 5 items:
     - 📏 Define Standard Reference Architecture
     - ⭐ Act as Benchmark for Future Programs
     - 🔄 Establish Repeatable Delivery Processes
     - ⚡ Enable Platform Scalability & AI Readiness
     - 🛡️ Enforce Quality, Security & Governance

7. **13 CoE Pillars section:**
   - Add a **Text** web part
   - Section heading: `13 CoE Core Pillars`
   - Add a **Quick links** web part in **Tiles** or **Grid** layout
   - Add all 13 pillars as link tiles (link each to the relevant sub-section anchor on the Data & AI or other pages)
   - See the table below for pillar names and target pages

8. **"What You'll Find" section:**
   - Add a **Quick links** web part — layout: **Filmstrip** or **Grid**
   - Add 6 items linking to the four pages and key sections

9. **Get Connected (4 steps):**
   - Add a **Text** web part with a numbered list

10. Click **Republish** (top-right) to save and publish the home page

### Pillar-to-Page Mapping

| # | Pillar Name | Target Page |
|---|------------|-------------|
| 1 | 📋 NFR & Standards | Data-and-AI.aspx#nfr |
| 2 | ⚙️ Dev Framework | Data-and-AI.aspx#dev |
| 3 | 🗄️ Data Management | Data-and-AI.aspx#data-mgmt |
| 4 | 🧪 Testing Framework | Data-and-AI.aspx#testing |
| 5 | 🚨 Error Handling | Data-and-AI.aspx#error |
| 6 | 🔄 CI/CD | Data-and-AI.aspx#cicd |
| 7 | 🏛️ Data Governance | Data-and-AI.aspx#governance |
| 8 | 🔧 Ops Readiness | Infrastructure-and-DevOps.aspx#ops-readiness |
| 9 | 🏗️ Infrastructure | Infrastructure-and-DevOps.aspx#infrastructure |
| 10 | 💰 Cost Avoidance | Infrastructure-and-DevOps.aspx#cost |
| 11 | 📊 Observability | Infrastructure-and-DevOps.aspx#observability |
| 12 | 🔒 Security | Security.aspx |
| 13 | 🤖 AI Enablement | Data-and-AI.aspx#ai |

---

### Step 8: Create the Data & AI Page

1. From your site, click **New** → **Page**
2. Choose **Blank** template
3. Name the page: `Data and AI` (URL: `Data-and-AI.aspx`)
4. Set the page header:
   - Title: `Data & AI Engineering Frameworks`
   - Description: `Pillars 1–7 & 13 — NFR, Development, Data Management, Testing, Error Handling, CI/CD, Governance, and AI Enablement`
   - Header style: **Color block** — use a medium blue

5. Add a **Section** with the **Vertical section** layout for a sticky sidebar navigation (optional), OR use a single-column layout with clear section headings

6. **For each of the 8 sub-sections**, add:

   **a) Pillar 1 — NFR & Standards:**
   - **Text** web part: Section heading `📋 Pillar 1 — NFR Template & Checks`
   - **Text** web part: Info box — "The NFR framework ensures every data platform asset meets enterprise-grade non-functional standards prior to production release."
   - **Quick links** web part (tiles): Tagging Standards, Security Checks, RTO/RPO, SLA Definitions, HA, DR
   - **Text** or **Table** web part: LeanIX integration requirements table

   **b) Pillar 2 — Dev Framework:**
   - Section heading, text description
   - **Quick links** tiles: Ingestion Tools, Config-Driven, AI-Assisted Dev, SonarQube, Reusable Libraries, Code Standards
   - **Table** web part: Metadata-Driven Pipeline Architecture table

   **c) Pillar 3 — Data Management:**
   - Section heading
   - **3-column layout** showing Bronze / Silver / Gold medallion layers (use coloured text web parts)
   - **Text** web part: Data Modeling, Catalog Structure, Partitioning & Vacuuming

   **d) Pillar 4 — Testing Framework:**
   - Section heading
   - **Quick links** tiles: DQ Framework, Unit Testing, Integration Testing, Contracts, Schema Validation
   - **Text** web part: 9 DQ Dimensions grid

   **e) Pillar 5 — Error Handling:**
   - Section heading
   - Quick links / text tiles: Audit Logs, Exception Logs, Alerting Framework, Root Cause Tooling, Retry Policies

   **f) Pillar 6 — CI/CD:**
   - Section heading
   - **Text** web part: GitOps info box
   - **Quick links** tiles: Asset Bundles, Git Repository, Workflow Stages, Feature Flags, Approval Gateway
   - **Table** web part: 5-stage deployment pipeline table

   **g) Pillar 7 — Data Governance:**
   - Section heading
   - Quick links tiles: Lineage Extraction, Alation Integration, Table Definitions, Data Glossary, Data Classification
   - **Table** web part: Governance Integration Map

   **h) Pillar 13 — AI Enablement:**
   - Section heading
   - **4-column layout** showing status badges: 🟢 Live, 🟡 Piloting, 🔵 Planned, ⚪ Evaluating
   - **Quick links** tiles for each of 6 AI tools (OpenAI, GitHub Copilot, Claude, MCP Servers, Databricks Assistant, Windsurf)

7. Click **Republish**

---

### Step 9: Create the Infrastructure & DevOps Page

1. Click **New** → **Page** → **Blank**
2. Name: `Infrastructure and DevOps` (URL: `Infrastructure-and-DevOps.aspx`)
3. Header: dark teal background, title: `Infrastructure & DevOps Engineering`

4. Add sections for Pillars 9, 8, 10, 11:

   **Pillar 9 — Infrastructure:**
   - Info box: "All MRx infrastructure defined, versioned, and deployed exclusively via Terraform."
   - Text tiles: Terraform IaC, Resource Tagging Policy (table), Compute Policies, Cluster Resizing, Compute Optimization, Network Security

   **Pillar 8 — Ops Readiness:**
   - Text tiles: Change Management (ServiceNow), Incident Management (P1–P4 SLA table), Assignment Groups (table), Jira Integration, SOX/SOC Auditing

   **Pillar 10 — Cost Avoidance:**
   - Info box: "Target: 20% YoY unit cost reduction per DBU consumed"
   - 4 stat boxes (metric tiles): ≥70% Spot, 30 min auto-terminate, 20% YoY, 40% storage savings
   - Text/table: FinOps Monitoring, Chargeback Model, Waste Elimination, Optimization Review cadence

   **Pillar 11 — Observability:**
   - Info box: Observability Stack description
   - Text tiles: Grafana Dashboards (6 dashboards listed), Azure Monitor
   - **Table** web part: Key SLOs table (Pipeline Success Rate, DQ Score, SLA Attainment, MTTD, Cost Variance)
   - **Table** web part: Alert tiers and Log retention tables

5. Click **Republish**

---

### Step 10: Create the Security Page

1. Click **New** → **Page** → **Blank**
2. Name: `Security` (URL: `Security.aspx`)
3. Header: dark red/maroon background, title: `Security & Compliance Framework`

4. Add sections for Pillar 12 sub-topics:

   **Zero Trust Overview:**
   - 4 stat tiles: Zero Trust, Shift Left, 24/7, SOC2/ISO
   - Dark callout box: Zero Trust Principle text
   - 3 tiles: Identity & Access, Network Security, Secrets & Key Management

   **Panorama — Vulnerability Management:**
   - Info box: "Critical CVEs resolved within 72 hours"
   - Text: Panorama integration description
   - **Table**: Vulnerability SLA Matrix (Critical/High/Medium/Low)

   **Wiz Cloud Security:**
   - Info box: "Wiz deployed across all MRx Azure subscriptions — daily scan"
   - 2 tiles: CSPM details, CWPP details
   - Text: Custom MRx Rules, Wiz Integration Flow

   **GitHub Advanced Security:**
   - Info box: GHAS scope statement
   - 3 tiles: Secret Scanning, CodeQL SAST, Dependabot/SCA
   - 2 tiles: Additional CI tooling, Security KPIs table

   **Monitoring & Alerting for Compromised Data:**
   - 2 tiles: Data Exfiltration Detection, Automated Response Playbooks
   - **Table**: Incident Response Playbooks for data security scenarios

   **Reporting:**
   - **Table**: Security Review Calendar
   - **Table**: Compliance Alignment (SOC 2, ISO 27001)

5. Click **Republish**

---

## Part 4 — Add a Document Library for Reference Materials

### Step 11: Upload Source Documents

1. In the left navigation, click **Documents** (or create via **New** → **Document library**)
2. Create a folder: `CoE Reference Materials`
3. Upload:
   - `Data_AI_CoE_SharePoint_Content.docx`
   - `Data_AI_CoE_Slides.pptx`
4. Right-click each file → **Manage access** → set to **Everyone in MRx team can view**

### Step 12: Embed Documents on Pages (Optional)

To show a document preview inline on any page:
1. Click **Edit** on the target page
2. Click **+** to add web part → search **File viewer**
3. Browse to the uploaded DOCX or PPTX file
4. Click **Republish**

---

## Part 5 — Enable SharePoint-Specific Features

### Step 13: Set Up Site Pages Permissions

1. Gear icon → **Site permissions**
2. Under **Site Owners**: add MRx CoE leads
3. Under **Site Members**: add all MRx engineers (or your AD group `MRx-Engineers`)
4. Under **Site Visitors**: add `MomentimRx All Staff` for read-only access
5. Click **Save**

### Step 14: Configure News Feed for CoE Updates

1. On the Home page in Edit mode, add a **News** web part
2. Set it to show **Site news** from this site
3. This allows CoE leads to post announcements (e.g., "NFR v1.1 released") that appear on the home page

### Step 15: Add Search and Highlighted Content

1. Add a **Highlighted content** web part on the Home page
2. Filter by document type and site — this auto-surfaces recently added content
3. Add a **Search** web part at the top of the Home page for easy content discovery

### Step 16: Configure Analytics

1. Gear icon → **Site usage**
2. Note the page view counts to track adoption
3. Share monthly usage stats with CoE leadership to measure engagement

---

## Part 6 — Verify and Test the Site

### Step 17: Pre-Launch Checklist

Run through this checklist before announcing the site:

**Content:**
- [ ] Home page published with vision, mission, 13 pillars, and get-connected section
- [ ] Data & AI page published with all 8 pillar sub-sections (NFR through AI Enablement)
- [ ] Infrastructure & DevOps page published with all 4 sub-sections
- [ ] Security page published with all 5 sub-sections
- [ ] Source documents uploaded to Document Library

**Navigation:**
- [ ] Top navigation links work and go to correct pages
- [ ] All 13 pillar tiles link to the correct page sections
- [ ] Quick links in "What You'll Find" section work

**Permissions:**
- [ ] MRx engineers can view all pages
- [ ] CoE owners can edit all pages
- [ ] Sensitive content (if any) restricted to appropriate groups

**Branding:**
- [ ] Site logo uploaded (MRx / McKesson brand)
- [ ] Theme matches McKesson brand colours
- [ ] Footer shows: "MomentimRx | © 2025 McKesson Corporation | McKesson Proprietary and Confidential"

**Functionality:**
- [ ] News web part shows latest CoE updates
- [ ] Search works across all pages
- [ ] Document previews work for DOCX and PPTX files
- [ ] Mobile view renders correctly (check on phone)

---

## Part 7 — Announce and Onboard the Team

### Step 18: Send the Launch Announcement

Send this email/Teams message to your MRx team:

---

**Subject: 🚀 MRx Nexus CoE Portal is Live!**

Hi team,

The **MRx Nexus** Data & AI Center of Excellence portal is now live at:

🔗 **https://mckessoncorp.sharepoint.com/sites/MRXNexusCOE**

MRx Nexus is your single source of truth for:
- 📋 **CoE standards and patterns** — NFR templates, architecture blueprints
- 🤖 **AI toolkits** — GitHub Copilot, Azure OpenAI, MCP Server guides
- 🔄 **CI/CD templates** — Asset Bundles, GitHub Actions workflows
- 📊 **Data governance frameworks** — Alation integration, lineage maps
- 🛡️ **Security runbooks** — Panorama, Wiz, GitHub Security guides
- 🏗️ **Infra & ops standards** — Terraform modules, Grafana dashboards

**No access request needed** — sign in with your McKesson SSO.

Questions? Reach us on Slack: **#data-ai-coe** or ServiceNow (category: Data & AI CoE).

MRx CoE Team

---

### Step 19: Post a Welcome News Article

1. On the Home page, click **+ Add** → **News post**
2. Title: `Welcome to MRx Nexus — CoE Portal v1.0`
3. Add a summary of what's available and encourage the team to explore
4. Click **Post**

---

## Appendix A — SharePoint Web Parts Reference

| Content Type | Recommended Web Part |
|-------------|---------------------|
| Section heading + description | **Text** |
| Numbered/bulleted lists | **Text** |
| Data tables | **Text** (HTML table) or **List** web part |
| Pillar/topic cards with icons | **Quick links** (tiles layout) |
| Statistics / KPI callouts | **Highlighted content** or **Text** with column layout |
| Document preview | **File viewer** |
| Latest CoE updates | **News** |
| Hero banner | **Hero** web part |
| Process flow diagram | **Image** or **File viewer** (uploaded PNG) |
| YouTube / video | **Stream** or **YouTube** embed |
| Info/callout boxes | **Text** with accent colour background |

---

## Appendix B — Using the HTML Reference Files

The HTML files in this repository (`index.html`, `data-ai.html`, `infrastructure-devops.html`, `security.html`) serve as the **content blueprint** for what to replicate in SharePoint. They are not directly deployable to SharePoint but contain all the:

- Exact text content for each section
- Table structures and data
- Colour coding and visual hierarchy guidance
- Section ordering and grouping

Use each HTML page as your reference while building the corresponding SharePoint page. The content hierarchy in the HTML maps directly to SharePoint web parts as follows:

| HTML Element | SharePoint Web Part |
|-------------|---------------------|
| `<section>` with heading | New section on SharePoint page |
| `.card` grid | Quick links (tiles) or column layout |
| `.data-table` | Text web part with HTML table |
| `.info-box` | Text web part with accent colour |
| `.stat-card` | Column layout text blocks |
| `<ul class="styled-list">` | Text web part bulleted list |
| Navigation tabs | Page sections / anchor links |

---

## Appendix C — Keeping the Portal Up to Date

### Governance Model for MRx Nexus

| Activity | Cadence | Owner |
|----------|---------|-------|
| CoE content review & updates | Quarterly | CoE Lead |
| New pattern / framework publication | As needed | Contributing engineer + CoE review |
| Broken link / outdated content report | Ongoing | Any team member via feedback form |
| Version bump of Enterprise Standards doc | Per major release | CoE Architect |
| Usage analytics review | Monthly | Platform Lead |

### Content Contribution Process

1. Engineer identifies missing pattern, standard, or runbook
2. Drafts content in Word / Markdown
3. Submits to CoE Slack channel `#data-ai-coe` for peer review
4. CoE lead approves and publishes to the relevant SharePoint page
5. News post created to announce the new content

---

*MRx Nexus CoE Portal — Deployment Guide v1.0 — March 2026*  
*MomentimRx | © 2025 McKesson Corporation | McKesson Proprietary and Confidential*
