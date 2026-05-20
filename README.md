# QA AI Agents Showcase
![GitHub stars](https://img.shields.io/github/stars/FazilaAli/QA-AI-Agents?style=social)

![OpenAI](https://img.shields.io/badge/OpenAI-GPT-green)
![Playwright](https://img.shields.io/badge/Playwright-Automation-brightgreen)
![n8n](https://img.shields.io/badge/n8n-Workflow-orange)
![Electron](https://img.shields.io/badge/Electron-DesktopApp-blue)

AI-powered QA automation agents for intelligent code generation, visual regression analysis, and automated bug reporting.

> Portfolio showcase repository only.  
> Internal implementation details, credentials, URLs, and production workflows are intentionally excluded.

---

# 🚀 Agents

## 1. CoderQA Agent

AI-assisted automation code generation agent that converts Playwright recordings and DOM hints into structured Playwright Java automation code.

### ✨ Features

- Generates Playwright Java sync API code
- Creates Page Object methods
- Creates testcase method calls
- Uses DOM-aware XPath generation
- Handles dropdowns, uploads, assertions, and date pickers
- Preserves recorded execution order
- Includes Electron desktop application for QA users

### 🧠 Workflow

```text
Playwright Recording + DOM Hints / Metadata
        ↓
OpenAI Processing
        ↓
Generated Java Page Object + Generated Testcase
        ↓
Generated Code in IDE
```

### 🛠 Tech Stack

- OpenAI GPT
- Playwright
- Java
- Electron
- n8n

### 📷 Showcase Assets

```text
assets/coderqa-electron-app.png
assets/coderqa-generated-code.png
assets/coderqa-workflow.png
```

---

## 2. UI Regression Agent

AI-powered visual regression testing workflow that compares baseline screenshots against new screenshots and generates an interactive review report.

### ✨ Features

- Baseline vs new screenshot comparison
- Missing element detection
- Layout shift detection
- Clipping and overflow detection
- Severity classification
- Confidence scoring
- Interactive HTML regression report
- Jira bug creation workflow
- Baseline promotion workflow

### 📊 Report Features

- Side-by-side screenshot comparison
- Regression findings
- Confidence distribution
- Bug summary dashboard
- Jira bug action buttons
- Fullscreen image viewer
- Baseline approval action

### 🧠 Workflow

```text
Baseline Screenshot + New Screenshot
        ↓
AI Visual Analysis
        ↓
Regression Findings
        ↓
Interactive HTML Report
        ↓
Jira Bug / Baseline Approval
```

### 🛠 Tech Stack

- OpenAI Vision Models
- Playwright
- HTML/CSS/JavaScript
- Jira APIs
- n8n

### 📷 Showcase Assets

```text
assets/ui-regression-report-1.png
assets/ui-regression-report-2.png
assets/ui-regression-report-3.png
assets/ui-workflow.png
```

---

## 3. Automation Bug Agent

Automated workflow that converts failed TestRail executions into Jira bug tickets.

### ✨ Features

- Reads failed TestRail results
- Extracts failure details
- Formats Jira bug descriptions
- Uploads screenshots automatically
- Links bugs to active sprint
- Adds severity metadata
- Reduces manual QA reporting effort

### 📌 Extracted Information

- Failed step
- Expected result
- Actual result
- Failure reason
- URL
- Attachments
- Historical comments

### 🧠 Workflow

```text
Failed TestRail Execution
        ↓
Failure Parsing
        ↓
AI Formatting
        ↓
Jira Bug Creation
        ↓
Screenshot Upload
```

### 🛠 Tech Stack

- TestRail APIs
- Jira APIs
- OpenAI
- JavaScript
- n8n

### 📷 Showcase Assets

```text
assets/automation-bug-flow.png
```

---

# 📂 Repository Structure

```text
qa-ai-agents-showcase/
│
├── README.md
│
├── agents/
│   ├── coderqa/
│   ├── ui-regression-agent/
│   └── automation-bug-agent/
│
├── assets/
│   ├── coderqa-electron-app.png
│   ├── ui-regression-report.png
│   ├── automation-bug-flow.png
│   └── architecture.png
│
└── docs/
    ├── sample-outputs.md
    └── security-note.md
```

---

# 🏗 System Architecture

```text
Playwright / TestRail / Screenshots
                ↓
         n8n Workflow Layer
                ↓
          OpenAI Processing
                ↓
 ┌─────────────┬─────────────┬
 ↓             ↓             ↓
CoderQA     UI Agent     Bug Agent
 ↓             ↓             ↓
Code         Report       Jira Bug
```

---

# ⚙️ Tech Stack

| Area | Tools |
|---|---|
| Workflow Automation      | n8n      |
| AI Models      | OpenAI GPT Models      |
| Browser Automation      | Playwright      |
| Desktop Application      | Electron      |
| Automation Language      | Java      |
| Bug Tracking      | Jira      |
| Test Management      | TestRail      |
| Reporting      | HTML, CSS, JavaScript      |

---

# 🔒 Security Notice

This repository intentionally excludes:

- API keys
- Credentials
- Tokens
- Internal URLs
- Webhook endpoints
- Production workflow exports
- Company-sensitive screenshots
- Real Jira/TestRail data

All showcased assets should be sanitized before publishing.

---

# 🎯 Purpose

This project demonstrates practical AI applications in QA automation including:

- AI-assisted automation development
- Intelligent visual regression review
- Automated bug reporting
- QA workflow orchestration
- Enterprise automation tooling

---

# 📄 License

This repository is shared for portfolio and demonstration purposes only.
