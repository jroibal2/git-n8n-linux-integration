# Git + n8n Integration on Linux

## Latest Update:
- Timestamp: 2025-07-20T20:17:48.899Z
- Summary: 

# Git + GitHub Integration with n8n on Docker (Linux Mint)

This project demonstrates how to automate GitHub commits from a **Dockerized** n8n workflow running on a **Linux Mint** machine. By integrating Git with n8n, you can auto-generate and push updates (like a README.md file) based on dynamic data or triggers.

This repo includes:
- A fully working `n8n` workflow export
- A dynamic README template (`README_BASIC_TEMPLATE.md`)
- A guide for SSH + Git configuration inside Docker
- Companion YouTube video walkthrough

---

## 🚀 Use Case

This setup is ideal for:
- Automatically updating documentation from n8n workflows
- Automating Git commits from inside Docker
- Learning how to manage Git/SSH inside containers

---

## 🧱 Requirements

- Linux (tested on Linux Mint 21.3)
- Docker + Docker Compose
- GitHub account with SSH key added
- [n8n](https://n8n.io) running in Docker

---

## 🛠️ Quick Start

### 1. Clone This Repo

```bash
git clone git@github.com:your-username/git-n8n-linux-integration.git
cd git-n8n-linux-integration
 Updated with n8n workflow

## Purpose:
This file is automatically updated by a local n8n workflow to track updates made on this project.

## System Info:
- Host: Linux Mint
- n8n Version: {{n8n_version}}

## Automation Status:
- Last Run: {{last_run}}
- Workflow Status: Success

✅ Success / ❌ Failed
