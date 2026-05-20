QA AI Agents Showcase

AI-powered QA automation agents built around visual testing, intelligent code generation, and automated bug management workflows.

This repository is a portfolio showcase demonstrating the architecture, workflow design, and capabilities of three production-style QA automation agents built using:

n8n
OpenAI GPT models
Playwright
Electron
Jira
TestRail
HTML/CSS/JavaScript

⚠️ This repository intentionally excludes internal implementations, credentials, private endpoints, and company-sensitive data.

Agents Included
1. CoderQA Agent

AI-assisted code generation agent for QA automation engineers.

CoderQA converts:

Playwright recorded scripts
DOM hints
UI metadata

into:

Playwright Java Page Objects
Structured Testcases
Reusable automation code

The agent follows strict enterprise QA coding rules including:

XPath generation standards
Page Object design
Dropdown/date-picker handling
Assertion rules
Anti-hallucination validation
Upload handling
Method deduplication
Features
Converts Playwright recordings into Java sync API code
Generates structured Page Objects
Generates testcase methods in execution order
Intelligent XPath generation
DOM-aware locator strategy
Dropdown/date-picker automation support
Upload automation handling
Electron desktop application for QA users
Tech Stack
OpenAI GPT
n8n
Playwright
Java
Electron
Node.js
Showcase Assets

Add screenshots such as:

Electron UI
Generated code samples
Workflow diagrams
Prompt flow architecture


2. UI Regression Agent

AI-powered visual regression testing and reporting system.

This agent compares:

Baseline screenshots
Newly captured screenshots

and detects:

Missing UI elements
Layout shifts
Visual regressions
Missing buttons/icons
Alignment issues
Floating control issues
Clipping/overflow problems

The system generates a modern interactive HTML report for reviewers.

Features
AI-based screenshot comparison
Regression severity classification
Confidence scoring
Interactive HTML report generation
Jira bug creation integration
Baseline promotion workflow
Full-image modal viewer
Screenshot evidence management
Report Capabilities

The generated report includes:

Side-by-side screenshot comparison
Findings breakdown
Confidence distribution
Regression statistics
Jira bug submission actions
Baseline approval workflow
Tech Stack
OpenAI Vision Models
n8n
HTML/CSS/JavaScript
Jira APIs
Playwright
Showcase Assets

Add:

Sample report screenshots
Comparison examples
Architecture diagrams
Demo GIF/video


3. Automation Bug Agent

Automated TestRail-to-Jira bug management workflow.

This agent:

Reads failed TestRail executions
Extracts structured failure details
Formats bug descriptions
Creates Jira issues automatically
Uploads failure screenshots
Assigns issues into active sprint workflows
Features
TestRail integration
Automated Jira bug creation
Failure parsing
Screenshot attachment uploads
Sprint-aware issue management
Structured bug descriptions
Duplicate failure context handling
Workflow Highlights

The automation extracts:

Failed steps
Expected vs actual results
Failure reasons
URLs
Historical comments
Attachments/screenshots

and converts them into actionable Jira bugs.

Tech Stack
n8n
Jira REST APIs
TestRail APIs
OpenAI
JavaScript
Showcase Assets

Add:

Workflow diagrams
Jira ticket examples
Failure parsing examples
Automation flow screenshots

