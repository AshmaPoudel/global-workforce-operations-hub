# Global Workforce Operations Hub: End-to-End Payroll & Exception Architecture

An interconnected operational ecosystem designed to model cross-border employment, automate compliance auditing, and streamline multi-country payroll issue resolution. 

This repository demonstrates advanced system design, automated AI compliance pipelines, and live data visualization tailored for scale at global EOR and workforce management platforms.

---

## Live System Infrastructure

| Asset | Platform/Stack | Live Access |
|-------|----------------|-------------|
| 🎯 Functional Payroll Engine | React + Recharts | [Open Interactive Sandbox](https://claude.ai/public/artifacts/97496e38-412e-4d77-bf99-1d80da0c133e) |
| 📊 Operations Command Center | Looker Studio | [Open Live Dashboard](https://datastudio.google.com/reporting/d6774274-3f24-4161-9839-1fa755a2fed4/page/LdXyF) |
| 🌐 Master Architecture Hub | Notion | [Open Global Operations Hub](https://app.notion.com/p/Global-Workforce-Operations-Hub-37049d700566802aa893f03a096a4687) |
| 💻 Deployed Codebase | Netlify + GitHub | [Open Live Project Site](https://payroll-exception-management.netlify.app/) |

---

## The Operational Architecture (How It Connects)

Unlike isolated portfolio pieces, this repository connects an **Employee-Facing Layer** directly to an **Operations-Facing Layer** to close the feedback loop on payroll administration:

1. **The Sandbox (Project 2):** Employees input their country, gross salary, and recurring expenses. The calculations layer processes local tax structures, enforces statutory ceilings (e.g., Thailand’s 750 THB social security cap), and routes corporate expense claims into a 14-day reimbursement pipeline.
2. **The Automation Layer (AI Detective):** Expense submissions undergo automated parsing to flag cross-border compliance violations (e.g., missing receipts under UK HMRC or missing business contexts under Thai Revenue Department guidelines).
3. **The Exception Desk (Project 1):** If a reimbursement remains processing past the 14-day SLA window, the backend dynamically instantiates an emergency exception ticket, categorizes its priority, assigns a dedicated internal owner, and updates the management command center in real time.
[Employee Submission] ──> [Expense Tracking] ──> [AI Compliance Check]
│
[Live Looker Dashboard] <── [SLA Triage Desk] <── [Overdue Exception Flag]
---

## System Component Breakdown

### 1. Global Payroll & Expense Simulator (Project 2)
*   **Multi-Jurisdiction Logic:** Built-in calculation matrices for 10 distinct countries, managing dynamically adjusted localized income tax bands and statutory pension boundaries.
*   **Financial Health Engine:** Real-time personal cash-flow optimizer routing net disposable income automatically into structured portfolios (30% savings floor, 70% automated wealth allocations) with dynamic safety warnings.

### 2. AI Compliance Agent (The Payroll Detective)
*   **Automated Auditing:** Leverages tailored prompt architecture to cross-examine text-based reimbursement logs against local EOR labor laws.
*   **Risk Categorization:** Outputs structured risk tables marking violations as Low, Medium, or High, while dictating the precise manual override required by an operations manager.

### 3. Payroll Exception Management Desk (Project 1)
*   **Automated Triage:** Replaces high-friction manual email sorting with algorithmic classification of issue severity, core categories, and region-based routing.
*   **SLA Governance:** Governs internal back-office infrastructure with tight resolution deadlines ranging from a strict 4-hour critical turnaround to routine weekly audits.

---

## Service Level Agreement (SLA) Priority Matrix

| Severity | Target System Event | SLA Clock | Assigned Target Owner | Breach Escalation Protocol |
| :--- | :--- | :--- | :--- | :--- |
| 🔴 **Critical** | Missing/Delayed Core Salary | 4 Hours | Sr. Payroll Analyst | Immediate SLA breach; Ops Lead automated ping |
| 🟠 **High** | Inaccurate Statutory Tax Deduction | 1 Business Day | Payroll Analyst | Trigger alert if unassigned within 2 hours |
| 🟡 **Medium** | Overdue Reimbursement Cycle (>14 days) | 2 Business Days | Payroll Analyst | Automated warning at 80% of SLA window |
| 🟢 **Low** | Historical Payslip Clarification | 3 Business Days | Support Specialist | Batch processing during weekly operational reviews |

---

## Live Core Metrics Tracked

| Operational Metric | Live Architecture Baseline |
| :--- | :--- |
| **Monitored Ticket Volume** | 51 Live Cases across 12 EOR Target Regions |
| **System Financial Impact** | $90,652 in tracked capital allocation |
| **SLA Exceptions Caught** | 3 Breaches flagged with active escalation triggers |
| **Resolution Velocity** | Modelled to drive a 68% drop in resolution times |
| **Target SLA Maintenance** | Balanced at an enterprise benchmark of 92% |
| **Manual Operational Triage** | Reduced to 0% via frontend automated categorization |

---

## Engineering & Operations Stack

| Core Tool | System Function |
| :--- | :--- |
| **React + Recharts** | Frontend analytical client, handling multi-variable UI rendering and filtering |
| **Google Sheets** | Relational calculation engine, storing core statutory rates and tax data matrices |
| **Looker Studio** | Live business intelligence dashboard, continuously piping data from the core ledger |
| **Whimsical** | Structural blueprint engine mapping automated vs. human-in-the-loop logic gates |
| **Claude AI** | LLM core parsing free-text support tickets and executing rule-based validation scripts |

---

## Directory Schema

```text
payroll-exception-management/
├── index.html                           # Main web entry application
├── dashboard.jsx                        # React analytics engine and visual logic
├── payroll_exceptions_data.xlsx         # Consolidated EOR database and historical records
├── payroll_exceptions_raw.csv           # Unstructured incoming employee ticket simulation
├── AI_Classified_Ticket_TK1092.pdf      # Proof-of-concept automated ticket triage artifact
├── Payroll_Exception_Management_Flow.png # Full Whimsical operational infrastructure layout
└── Payroll_Exception_Management_Looker.pdf # Visual reference of active business intelligence system
