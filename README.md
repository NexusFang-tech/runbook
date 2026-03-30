# RUNBOOK — IT Operations Playbook

Interactive runbook and SOP builder for IT operations. Create, organize, and reference step-by-step procedures with checklists, code blocks, callout annotations, and full Markdown export. Includes 6 pre-built templates covering incident response, provisioning, maintenance, security, and network operations. Single HTML file, zero dependencies.

## Live Demo

**[nexusfang-tech.github.io/runbook](https://nexusfang-tech.github.io/runbook/)**

## Features

- **Full CRUD** — Create, edit, search, delete, and organize runbooks
- **8 categories** — Incident Response, Maintenance, Provisioning, Security, Backup & DR, Network, Monitoring, and custom
- **Step-by-step procedures** — Each step has:
  - Completion checkbox with progress tracking
  - Expandable detail view
  - Step type tags (Action, Verification, Decision, Documentation, Communication)
  - Code blocks with language selector (Bash, PowerShell, Python, SQL, CMD, JSON, YAML)
  - Callout annotations (Warning, Danger, Note, Tip) with distinct styling
  - Reorder, duplicate, and delete controls
- **5 severity levels** — Critical, High, Medium, Low, Info
- **Metadata** — Author, estimated time, last updated, tags
- **Search** — Full-text search across titles, descriptions, and tags
- **Persistence** — All runbooks saved to browser localStorage
- **Import/Export** — JSON import, Markdown/JSON/checklist export, print support

## Pre-Built Templates

| Template | Category | Severity |
|----------|----------|----------|
| Server Unresponsive — Initial Triage | Incident Response | High |
| New Employee M365 Provisioning | Provisioning | Low |
| SSL Certificate Renewal (win-acme) | Maintenance | Medium |
| Phishing Incident Response | Security | Critical |
| Azure VM Backup Verification | Backup & DR | Medium |
| Network Switch VLAN Configuration | Network | Medium |

Templates include real-world commands for PowerShell, Azure CLI, Bash, and Cisco IOS.

## Export Formats

| Format | Description |
|--------|-------------|
| Markdown | Wiki-ready with headers, tables, code blocks, and blockquote callouts |
| JSON | Full data export, re-importable |
| Checklist | Plain text with checkbox notation for printing |

## Tech Stack

Vanilla JavaScript · localStorage · CSS · GitHub Pages

## Author

**Matt Keith** · [nexusfang-tech.github.io](https://nexusfang-tech.github.io)
