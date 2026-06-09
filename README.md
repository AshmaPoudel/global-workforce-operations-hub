# Global Workforce Operations Hub 🌐

An end-to-end operational portfolio demonstrating AI-assisted 
global payroll management, cross-border EOR compliance, and 
enterprise onboarding implementation.

Built by a remote operations professional targeting Onboarding 
Implementation, Compliance Operations, and Product Operations 
roles at global SaaS companies.

---

## 🎭 The Three-Act Portfolio Story

**Act I — The Employee Frontend**
The Global Payroll Simulator lets anyone enter their salary, 
select their employment country, see live statutory deductions 
applied in local currency, track monthly expenses, and submit 
work reimbursements.

**Act II — The Friction Point**
When a reimbursement is not processed within 14 days, the system 
flags it as a compliance breach and generates an exception ticket 
automatically.

**Act III — The Resolution Core**
The exception enters the Payroll Exception Management System, gets 
classified by severity, assigned an SLA target, routed to the 
correct owner, and tracked on a live operations dashboard until 
resolved.

---

## 🔗 Live Portfolio

🎬 **Video Walkthrough:**
[![Watch the 3-Act Systems Demo](https://img.youtube.com/vi/652033004/maxresdefault.jpg)](https://www.loom.com/share/56416663e8d44395b23dcb53df9bd97b)
*Click the image above to watch the full 90-second system operational lifecycle.*

| Asset | Link |
|-------|------|
| 🌐 Full Portfolio Hub | [Open Notion Page](https://app.notion.com/p/Global-Workforce-Operations-Hub-37049d700566802aa893f03a096a4687?source=copy_link) |
| 🎭 Global Payroll Simulator | [Open Simulator](https://ashmapoudel.github.io/global-workforce-operations-hub/) |
| 🖥️ Exception Dashboard | [Open Dashboard](https://ashmapoudel.github.io/global-workforce-operations-hub/dashboard.html) |
| 📊 Live Command Center | [Open Looker Studio](https://datastudio.google.com/reporting/d6774274-3f24-4161-9839-1fa755a2fed4/page/LdXyF) |
| 🎯 React Dashboard | [Open Artifact](https://claude.ai/public/artifacts/97496e38-412e-4d77-bf99-1d80da0c133e) |
| 📋 Google Sheets Sandbox | [Open Sheet](https://docs.google.com/spreadsheets/d/1BaxNAx-YTVfHZz5vlF1ZkBpylvBMcR1t4t2TeX5uiYA/edit) |

---

## 📁 Project 1 — Payroll Exception Management System

A structured operational framework replacing manual email-based 
payroll issue resolution with AI-assisted ticket classification, 
SLA-governed routing, and a live operations dashboard.

**Key results:**
- 51 tickets tracked across 5 categories and 12 regions
- 3 SLA breaches identified and flagged automatically
- $90,652 total financial impact tracked
- AI classification replaces manual triage entirely
- Live dashboard updates automatically from Google Sheets

**Files:**
- `dashboard.html` — Exception management portfolio page
- `payroll_exceptions_data.xlsx` — 51-row dataset
- `payroll_exceptions_raw.csv` — Raw data for import
- `AI_Classified_Ticket_TK1092.pdf` — Sample AI classified ticket
- `Payroll_Exception_Management_FlowChart.png` — Whimsical flowchart

---

## 📁 Project 2 — Global Payroll & Expense Simulator

An interactive multi-country gross-to-net payroll calculator 
combined with an automated expense router and reimbursement 
pipeline. Supports 10 countries with live statutory deductions 
applied in local currency.

**Key features:**
- 10 countries with country-appropriate default salaries
- Live currency symbols and correct statutory rates per country
- Expense categorisation into Needs, Wants, Savings, Investment
- Reimbursement pipeline with 14-day compliance window
- Automatic exception flagging that connects to Project 1
- Live GOOGLEFINANCE currency conversion to USD

**Files:**
- `index.html` — Global Payroll Simulator (main page)
- `global_workforce_sandbox.xlsx` — Google Sheets calculation engine
- `simulator.jsx` — React component version

---

## 🤖 AI Compliance Agent

Demonstrates prompt engineering applied to a real operational 
problem — automated expense auditing across multiple countries 
using AI to flag compliance risks without manual review.

---

## 🗓️ 30-Day EOR Onboarding Blueprint

Simulates the end-to-end operational plan for migrating 50 workers 
across Thailand, Nepal, and the UK. Documents country-specific 
compliance requirements, document collection workflows, and 
escalation procedures.

---

## 🛠️ Tools and Tech Stack

| Tool | Purpose |
|------|---------|
| React + Recharts | Interactive dashboard with filters and charts |
| Google Sheets | Live calculation engine and compliance matrix |
| Looker Studio | Connected dashboard updating from Google Sheets |
| Whimsical | System design flowchart |
| Claude AI | Ticket classification and compliance auditing |
| GitHub + GitHub Pages | Version control and public hosting |
| Notion | Master portfolio hub |

---

## 🔄 How the Two Projects Connect

Employee submits expense in Simulator (Project 2)
↓
Reimbursement enters 14-day compliance window
↓
If unprocessed after 14 days → Exception ticket generated
↓
AI classifies severity and category
↓
Owner assigned with SLA clock (Project 1)
↓
Operations team resolves via Exception Dashboard
↓
Resolution logged → Live dashboard updates

---

*Built as an independent portfolio project. All systems are live 
and interactive. All data is simulated for demonstration purposes. 
Relevant to roles in Operations, Implementation, Customer Success, 
and Product Operations at global workforce platforms.*
