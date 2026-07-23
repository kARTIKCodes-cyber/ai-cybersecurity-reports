# AI Cybersecurity Reports

AI-powered automation for cybersecurity GRC reporting. Built in public.

## 🚀 Products

### 1. Vulnerability Report Generator
- **Input:** Raw vulnerability scan data (CSV, Nessus, Qualys)
- **Output:** Professional HTML executive summary
- **Features:**
  - AI-generated impact summaries (Groq API - llama-3.1-8b-instant)
  - Color-coded risk levels (Critical/High/Medium/Low)
  - Auto-prioritized remediation timeline
  - 5 vulnerabilities processed in 30 seconds

### 2. Compliance Gap Analyzer
- **Input:** ISO 27001 controls + client evidence
- **Output:** Structured gap report with remediation steps
- **Features:**
  - Gap identification (Compliant/Partial/Non-Compliant)
  - Risk impact assessment
  - Priority + timeline recommendations

### 3. SOC 2 Gap Analysis Report
- **Input:** SOC 2 Trust Service Criteria + client evidence
- **Output:** Audit-ready gap report sections
- **Features:**
  - Criteria matching and evidence validation
  - AI-generated gap descriptions
  - Remediation recommendations

## 🎥 Demos
- [Vulnerability Report Demo](https://www.loom.com/share/5dc8a929366e45f0852c58e12b7bc6cc)
- [Compliance Gap Analyzer Demo](https://www.loom.com/share/09d4a83d1b33467bafc1efffc5b314d3)

## 🛠 Tech Stack
- [n8n](https://n8n.io/) — workflow automation
- [Groq API](https://groq.com/) — llama-3.1-8b-instant
- HTML/CSS — report generation

## 📊 Sample Output

[View Sample Report](sample-report.html)

## 📁 Workflows

All n8n workflows are in the `/workflows` folder:
- `Vulnerability Scan Executive Summary.json` — Raw scan → Executive report
- `ISO 27001 Compliance Gap Analysis.json` — Controls + evidence → Gap report
- `SOC 2 Gap Analysis Report.json` — SOC 2 criteria → Audit report

## 🏗 Building in Public

- Day 0: Started building
- Day 2: Vulnerability report generator working
- Day 4: Compliance gap analyzer built
- Day 5: Professional HTML report output

**Status:** Zero clients. Zero revenue. But the product works.

## 🤝 Connect
- [LinkedIn](https://linkedin.com/in/kartik-sharma-b34a41422)
- [Fiverr](your-fiverr-link-here)

---

Built by Kartik Sharma | Final year Cybersecurity, Shoolini University
