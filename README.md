# 🤖 100% Free AI Agent Driven Development Workflow

### Build, deploy, and run everything — $0/month

A complete, step-by-step guide to set up a **fully automated AI-powered development and deployment environment** from scratch. No credit card. No hidden costs. No "free trial" that expires.

Designed so that **anyone** can follow along and replicate the entire setup — and let the AI agent do most of the work for you.

---

> 📌 **Quick Info**
> - **Author:** Prince (NH Prince Pradhan)
> - **Maintained by:** Saturday (Hermes Agent) — auto-updated weekly
> - **Last Updated:** 2026-06-06
> - **Server:** Azure VM (2 vCPU, 842MB RAM, 29GB SSD) — Ubuntu 24.04 LTS
> - **Domain:** cp.stuckstudio.qzz.io

---

## 💰 The Free Infrastructure Philosophy

> **The only thing you pay for is the server running the AI agent. Everything else is 100% free. Forever.**

This entire stack costs **$0/month** in infrastructure (excluding the VPS for the agent). No credit card required. No hidden limits. No "free trial" that expires.

### 🆓 What's Completely Free

| Service | What You Get | Free Tier |
|---------|-------------|-----------|
| **☁️ Cloudflare Pages** | Frontend hosting, CDN, SSL, custom domains | Unlimited bandwidth, unlimited requests |
| **⚡ Cloudflare Workers** | Serverless backend, edge computing | 100,000 requests/day |
| **🗄️ Cloudflare D1** | SQLite database at the edge | 5GB storage, 5M rows read/day |
| **📦 Cloudflare KV** | Key-value storage | 100,000 reads/day, 1,000 writes/day |
| **💾 Cloudflare R2** | Object storage (S3-compatible) | 10GB storage, free egress |
| **🔄 GitHub Actions** | CI/CD, auto-deploy on push | 2,000 minutes/month |
| **🐙 GitHub** | Unlimited repos, private & public | Unlimited |
| **🤖 OpenRouter** | AI models (free tier) | Multiple free models with rate limits |
| **🔍 DuckDuckGo** | Web search | Unlimited, no API key needed |
| **📧 Telegram Bot** | Messaging platform | Unlimited |
| **💬 WhatsApp Bridge** | Messaging platform | Unlimited |
| **🛠️ Node.js / pnpm / Bun** | Development tools | Open source, forever free |
| **🎨 Next.js / Hono / Tailwind** | Frameworks | Open source, forever free |
| **📊 PM2** | Process manager | Open source, forever free |

### 💵 Total Monthly Cost

| Item | Cost |
|------|------|
| VPS (for AI agent) | **$0** (Azure for Students) |
| Cloudflare (Pages + Workers + D1 + KV + R2) | **$0** |
| GitHub (Repos + Actions) | **$0** |
| OpenRouter (free models) | **$0** |
| Messaging (Telegram + WhatsApp) | **$0** |
| Development tools | **$0** |
| **TOTAL** | **$0/month — absolutely everything free!** |

### 🎯 The Philosophy

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   🤖 AI Agent (VPS) ← The only thing you might pay for │
│       │                                                 │
│       ├──▶ ☁️ Cloudflare Pages (Frontend)     FREE     │
│       ├──▶ ⚡ Cloudflare Workers (Backend)    FREE     │
│       ├──▶ 🗄️ Cloudflare D1 (Database)       FREE     │
│       ├──▶ 📦 Cloudflare KV (Storage)        FREE     │
│       ├──▶ 🔄 GitHub Actions (CI/CD)         FREE     │
│       ├──▶ 🐙 GitHub (Source Control)        FREE     │
│       ├──▶ 🤖 OpenRouter (AI Models)         FREE     │
│       ├──▶ 🔍 DuckDuckGo (Search)            FREE     │
│       └──▶ 📨 Telegram/WhatsApp (Messaging)  FREE     │
│                                                         │
│   💡 Build, deploy, and run everything for $0/month    │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

> **💡 Pro Tip:** If you're a student, the [GitHub Student Developer Pack](https://education.github.com/pack) gives you **$100 Azure credits**, **$200 DigitalOcean credits**, and more — meaning even the VPS can be **completely free**!

### 🆓 How to Get a FREE VPS (No Credit Card Needed)

> **Yes, you can run this entire setup for $0/month — including the VPS!**

#### Option 1: Azure for Students (Recommended)

1. Go to [azure.microsoft.com/en-us/free/students](https://azure.microsoft.com/en-us/free/students)
2. Click **"Start Free"**
3. Sign in with your **school email** (or verify student status with GitHub)
4. **No credit card required!**
5. You get **$100 in Azure credits** + free services for 12 months
6. Create a VM: **B1s tier** (1 vCPU, 1GB RAM) — **free for 750 hours/month**
7. That's enough to run your AI agent 24/7 for free!

#### Option 2: GitHub Student Pack Credits

1. Apply at [education.github.com/pack](https://education.github.com/pack)
2. Once approved, you get:
   - **$200 DigitalOcean credits** for 60 days
   - **$13/month Heroku** for 24 months
   - **Free GitHub Pro** (normally $4/month)
   - **GitHub Copilot** (free Pro tier)
   - Plus many more tools and services
3. Use any of these to host your VPS for free

> **💡 Note:** Azure for Students already gives you **$100 in free credits** with no credit card required. The GitHub Student Pack does **not** stack additional Azure credits — it's the same $100 Azure offer. But the pack gives you plenty of other credits (DigitalOcean, Heroku, etc.) to cover hosting costs!

---

## 🤖 Let the Agent Do the Heavy Lifting

> **This guide shows you what's happening under the hood. But in practice, you can just ask Saturday (your AI agent) to do all of this for you.**

Throughout this guide, you'll see this icon 🤖 — it means you can skip the manual steps and just tell the agent:

| Instead of... | Just say... |
|---------------|-------------|
| Manually configuring Telegram/WhatsApp/Slack | "Set up all my messaging platforms" |
| Manually editing `config.yaml` | "Add all free OpenRouter models as fallbacks" |
| Creating Cloudflare resources | "Set up Cloudflare Pages and Workers for my project" |
| Writing GitHub Actions YAML | "Create a CI/CD pipeline that auto-deploys to Cloudflare" |
| Configuring nginx/PM2 | "Set up nginx reverse proxy for my app" |
| Writing cron scripts | "Set up a daily cron job that does X" |
| Installing dev tools | "Install Node.js, pnpm, Bun, and PM2" |
| Setting up the whole project | "Create a new full-stack project with Next.js and Hono" |

**The agent handles all complex configs, YAML files, CI/CD pipelines, and infrastructure setup automatically.** This guide is here so you understand what's happening — but you don't have to do it manually.

---

## 🏗️ Build Projects with Saturday Framework

> **Saturday is the official framework** for building projects with this setup. Once your agent is running, Saturday handles everything from scaffold to deploy.

### ✨ Why Saturday?

| Feature | Benefit |
|---------|---------|
| **1-Command Setup** | `"Build me a blog called my-blog"` → full project |
| **100% Free Infrastructure** | Uses Cloudflare free tier + GitHub Actions |
| **Dark Theme UI** | Glassmorphism cards, gradient accents, micro-animations |
| **Agent-Driven Workflow** | Saturday does the work, you just approve |
| **VPS Fallback** | Dual-deploy to Cloudflare or your VPS |

### Quick Start with Saturday

```bash
# Tell Saturday what to build:
"Build me a blog called my-blog"
"Create a SaaS called tiny-tools"
"Make a portfolio site"
"Build an API for my app"
```

Saturday handles: scaffold → configure → deploy → verify. All on 100% free infrastructure.

### How Saturday + This Guide Work Together

```
1. Follow this guide → Set up your AI agent (Saturday) on a free VPS
2. Use Saturday → Build projects with 100% free infrastructure
3. Deploy → Cloudflare (default) or VPS (fallback)
```

[→ Saturday Framework on GitHub](https://github.com/nhprince/saturday) | [→ Saturday Dashboard](https://saturday-62d.pages.dev)

---

1. [Initial Server Setup](#1-initial-server-setup)
2. [Install Hermes Agent (Saturday)](#2-install-hermes-agent-saturday)
3. [Setup Messaging Platforms](#3-setup-messaging-platforms)
4. [Configure Free Model Rotation](#4-configure-free-model-rotation)
5. [Server Cleanup & Optimization](#5-server-cleanup--optimization)
6. [Install Development Tools](#6-install-development-tools)
7. [Configure Cloudflare](#7-configure-cloudflare)
8. [Create Project Template](#8-create-project-template)
9. [GitHub Actions CI/CD](#9-github-actions-cicd)
10. [Daily Greeting Cron Job](#10-daily-greeting-cron-job)
11. [Free Web Search](#11-free-web-search)
12. [Troubleshooting](#12-troubleshooting)
13. [A-to-Z Example Workflow — From Idea to Live Project](#🗺️-a-to-z-example-workflow--from-idea-to-live-project)
14. [Free Student Benefits](#13-free-student-benefits)

---

## 1. Initial Server Setup

### 1.1 Connect to Your Server

```bash
ssh user@your-server-ip
```

### 1.2 Update System

```bash
sudo apt update && sudo apt upgrade -y
```

### 1.3 Create Non-Root User (if needed)

```bash
adduser nhprince
usermod -aG sudo nhprince
```

### 1.4 Install Essential Packages

```bash
sudo apt install -y curl wget git build-essential software-properties-common \
  unzip zip htop btop nano vim ufw fail2ban nginx certbot python3-certbot-nginx \
  mariadb-server php-fpm
```

### 1.5 Configure Firewall

```bash
sudo ufw allow OpenSSH
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw enable
```

### 1.6 Set Timezone

```bash
sudo timedatectl set-timezone Asia/Dhaka
```

### 1.7 Install HestiaCP (Optional — for web panel)

```bash
wget https://raw.githubusercontent.com/hestiacp/hestiacp/release/install/hst-install.sh
sudo bash hst-install.sh
```

> **Note:** Default HestiaCP binds to `127.0.0.1:8084` (localhost only).  
> Access via SSH tunnel: `ssh -L 8084:127.0.0.1:8084 user@server`

---

## 2. Install Hermes Agent (Saturday)

Hermes Agent is an AI-powered assistant that runs on your server. We call ours **Saturday**.

### 2.1 Install Hermes CLI

```bash
npm install -g hermes-agent
```

### 2.2 Run the Setup Wizard

```bash
hermes setup
```

The setup wizard will guide you through everything interactively:

1. **Choose your AI provider** — Select OpenRouter (recommended for free models)
2. **Enter your API key** — Your OpenRouter API key
3. **Select model** — Choose a free model like `nvidia/nemotron-3-super-120b-a12b:free`
4. **Connect messaging platforms** — Telegram, WhatsApp, Slack, Email
5. **Configure gateway** — Port and network settings

That's it. The wizard creates `~/.hermes/config.yaml` automatically.

### 2.3 Start the Gateway

```bash
hermes gateway start
```

### 2.4 (Optional) Run as a Systemd Service

For automatic restarts on boot:

```bash
sudo nano /etc/systemd/system/hermes-gateway.service
```

```ini
[Unit]
Description=Hermes Agent Gateway
After=network.target

[Service]
Type=simple
User=YOUR_USERNAME
WorkingDirectory=/home/YOUR_USERNAME
ExecStart=/home/YOUR_USERNAME/.local/bin/hermes gateway
Restart=always
RestartSec=10
Environment=NODE_ENV=production

[Install]
WantedBy=multi-user.target
```

```bash
sudo systemctl daemon-reload
sudo systemctl enable hermes-gateway
sudo systemctl start hermes-gateway
```

> **⚠️ Important:** Never restart the gateway from inside Hermes itself — it refuses to prevent restart loops. Always use:
> ```bash
> sudo systemctl restart hermes-gateway
> ```

### 2.5 Verify It's Working

```bash
hermes status
```

You should see the gateway running and connected platforms listed.

---

## 3. Setup Messaging Platforms

> **🤖 Agent Tip:** You don't need to do this manually. Just say *"Set up all my messaging platforms"* — Saturday will walk you through connecting Telegram, WhatsApp, Slack, and Email automatically.

The `hermes setup` wizard handles most platform connections. Here's what you need:

### 3.1 Telegram (Recommended)

**This is the primary way you'll talk to Saturday.** Telegram is the most reliable and fully-featured platform for the agent.

1. Message [@BotFather](https://t.me/BotFather) on Telegram
2. Create a new bot with `/newbot`
3. Copy the token
4. During `hermes setup`, paste the token when prompted

> **💡 Why Telegram first?** It's the most stable connection, supports rich messages, and works 24/7 without your phone being online (unlike WhatsApp).

### 3.2 WhatsApp

WhatsApp connects automatically during setup. The bridge only supports **pre-synced contacts** from your phone's address book.

> **Limitation:** You cannot send to arbitrary phone numbers. The contact must be saved in your phone first. Also, WhatsApp requires your phone to stay connected.

### 3.3 Slack & Email

Follow the prompts during `hermes setup` to configure these platforms.

---

## 4. Configure Free Model Rotation

### 4.1 Add Free Models as Fallbacks

After the initial setup, you can add more free models as fallbacks. Ask Saturday:

> "Add all free OpenRouter models as fallbacks"

Saturday will query the OpenRouter API and update `~/.hermes/config.yaml` automatically.

### 4.2 Daily Auto-Refresh (Optional)

To automatically refresh the free model list daily, ask Saturday:

> "Set up a daily cron job to refresh free models"

Saturday will create the script and cron job for you.

> **Tip:** Free models change frequently. If you hit rate limits, just tell Saturday to "refresh free models" and it'll update the config.

---

## 5. Server Cleanup & Optimization

> **🤖 Agent Tip:** Just say *"Clean up my server and free up RAM"* — Saturday will remove unused services, tune MariaDB, and optimize everything automatically.

### 5.1 Remove Unused PHP Versions

HestiaCP installs multiple PHP-FPM versions. Keep only what you need:

```bash
# List installed PHP versions
dpkg -l | grep php-fpm

# Remove old versions (keep 8.3+)
sudo apt remove -y php5.6-fpm php7.0-fpm php7.1-fpm php7.2-fpm \
  php7.3-fpm php7.4-fpm php8.0-fpm php8.1-fpm php8.2-fpm

# Restart remaining
sudo systemctl restart php8.3-fpm
```

### 5.2 Remove Unnecessary Services

```bash
# No modem on a VPS
sudo systemctl stop ModemManager
sudo systemctl disable ModemManager
sudo apt remove -y modemmanager

# Single disk, no multipath needed
sudo systemctl stop multipathd
sudo systemctl disable multipathd

# Only if not hosting DNS zones
sudo systemctl stop bind9
sudo systemctl disable bind9
```

### 5.3 Tune MariaDB for Low Memory

```bash
sudo nano /etc/mysql/conf.d/low-memory.cnf
```

```ini
[mysqld]
innodb_buffer_pool_size = 32M
key_buffer_size = 16M
max_connections = 20
query_cache_size = 8M
tmp_table_size = 8M
performance_schema = OFF
```

```bash
sudo systemctl restart mariadb
```

### 5.4 Expected Memory Savings

| Action | RAM Saved |
|--------|-----------|
| Remove old PHP-FPM | ~90MB |
| Remove ModemManager | ~10MB |
| Remove multipathd | ~5MB |
| Tune MariaDB | ~20MB |
| **Total** | **~125MB** |

---

## 6. Install Development Tools

> **🤖 Agent Tip:** Just say *"Install all development tools — Node.js, pnpm, Bun, PM2, TypeScript, Wrangler, and GitHub CLI"* — Saturday will install and configure everything.

### 6.1 Node.js Ecosystem

```bash
# pnpm (fast package manager)
npm install -g pnpm

# Bun (fast JS runtime)
curl -fsSL https://bun.sh/install | bash

# PM2 (process manager)
npm install -g pm2

# TypeScript
pnpm add -g typescript

# Wrangler (Cloudflare CLI)
pnpm add -g wrangler
```

### 6.2 GitHub CLI

```bash
# Install gh CLI
curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | \
  sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | \
  sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null
sudo apt update && sudo apt install -y gh

# Authenticate
gh auth login
```

### 6.3 Python Tools

```bash
pip3 install --user black isort flake8 mypy
```

### 6.4 Add Hermes Node Bin to PATH

```bash
echo 'export PATH="/home/nhprince/.hermes/node/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

---

## 7. Configure Cloudflare

> **🤖 Agent Tip:** Just say *"Set up Cloudflare — create KV namespace, D1 database, and Pages project for my project"* — Saturday will authenticate, create all resources, and save the IDs.

### 7.1 Create Cloudflare Account

1. Go to [dash.cloudflare.com/sign-up](https://dash.cloudflare.com/sign-up)
2. Create a free account

### 7.2 Authenticate Wrangler

```bash
export PATH="/home/nhprince/.hermes/node/bin:$PATH"

# Option A: Browser login (local machine)
wrangler login

# Option B: API token (remote server — recommended)
# 1. Go to dash.cloudflare.com/profile/api-tokens
# 2. Create token with: Workers Edit, KV Storage Edit, D1 Edit, R2 Storage Edit
# 3. Set environment variable:
export CLOUDFLARE_API_TOKEN="your-token-here"

# Verify
wrangler whoami
```

### 7.3 Create Cloudflare Resources

```bash
# KV Namespace
wrangler kv namespace create KV
# → Save the namespace ID

# D1 Database
wrangler d1 create your-db-name
# → Save the database ID

# Pages Project
wrangler pages project create your-project-name --production-branch=main
```

### 7.4 Store Credentials

Save these for later use:
- **Account ID** (from `wrangler whoami`)
- **KV Namespace ID**
- **D1 Database ID**
- **API Token**

---

## 8. Create Project Template

> **🤖 Agent Tip:** Just say *"Create a new full-stack project called [name] with Next.js frontend and Hono backend"* — Saturday will scaffold the entire project, set up the workspace, and push to GitHub. For project types (blog, SaaS, portfolio, etc.), use the [Saturday Framework](https://github.com/nhprince/saturday) scaffolds.

### 8.1 Scaffold Structure

```
myproject/
├── .github/
│   └── workflows/
│       └── deploy.yml          # CI/CD pipeline
├── frontend/                   # Next.js app
│   ├── src/app/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── globals.css
│   ├── next.config.ts          # output: "export"
│   ├── tailwind.config.ts
│   ├── postcss.config.js
│   ├── package.json
│   └── tsconfig.json
├── backend/                    # Hono worker
│   ├── src/
│   │   └── index.ts
│   ├── wrangler.toml
│   └── package.json
├── package.json                # Root workspace
├── pnpm-workspace.yaml
└── .gitignore
```

### 8.2 Create GitHub Repository

```bash
gh repo create myproject --public --clone
cd myproject
```

### 8.3 Initialize Frontend (Next.js)

```bash
cd frontend
pnpm create next-app . --typescript --tailwind --eslint --app --src-dir --import-alias "@/*" --use-pnpm
```

**next.config.ts:**
```typescript
import type { NextConfig } from "next";
const nextConfig: NextConfig = {
  output: "export",
  images: { unoptimized: true },
};
export default nextConfig;
```

### 8.4 Initialize Backend (Hono)

```bash
cd ../backend
pnpm init
pnpm add hono drizzle-orm
pnpm add -D @cloudflare/workers-types drizzle-kit typescript wrangler
```

**backend/src/index.ts:**
```typescript
import { Hono } from "hono";
import { cors } from "hono/cors";

export interface Env {
  DB: D1Database;
  KV: KVNamespace;
}

const app = new Hono<{ Bindings: Env }>();
app.use("/api/*", cors());

app.get("/api/health", (c) => {
  return c.json({ status: "ok", timestamp: new Date().toISOString() });
});

export default app;
```

**backend/wrangler.toml:**
```toml
name = "myproject"
main = "src/index.ts"
compatibility_date = "2024-11-12"
compatibility_flags = ["nodejs_compat"]

[[kv_namespaces]]
binding = "KV"
id = "YOUR_KV_ID"

[[d1_databases]]
binding = "DB"
database_name = "your-db"
database_id = "YOUR_D1_ID"
```

### 8.5 Root Workspace Config

**pnpm-workspace.yaml:**
```yaml
packages:
  - "frontend"
  - "backend"
```

**package.json:**
```json
{
  "name": "myproject",
  "private": true,
  "scripts": {
    "dev:frontend": "cd frontend && pnpm dev",
    "dev:backend": "cd backend && pnpm dev",
    "build:frontend": "cd frontend && pnpm build",
    "deploy:cloudflare": "cd frontend && pnpm build && wrangler pages deploy out --project-name=myproject && cd ../backend && wrangler deploy"
  }
}
```

---

## 9. GitHub Actions CI/CD

> **🤖 Agent Tip:** Just say *"Set up auto-deploy to Cloudflare on every git push"* — Saturday will create the GitHub Actions workflow, add all secrets, and configure the dual-deploy pipeline.

### 9.1 Create Workflow

**.github/workflows/deploy.yml:**

```yaml
name: Deploy

on:
  push:
    branches: [main]
  workflow_dispatch:
    inputs:
      deploy_target:
        description: "Deploy target"
        required: true
        default: "cloudflare"
        type: choice
        options:
          - cloudflare
          - server

jobs:
  deploy-cloudflare:
    if: github.event.inputs.deploy_target == 'cloudflare' || github.event_name == 'push'
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: pnpm/action-setup@v4
        with: { version: 9 }
      - uses: actions/setup-node@v4
        with: { node-version: 22, cache: "pnpm" }

      - name: Install frontend deps
        run: cd frontend && pnpm install --no-frozen-lockfile

      - name: Build frontend
        run: cd frontend && pnpm build

      - name: Deploy Frontend to Cloudflare Pages
        uses: cloudflare/wrangler-action@v3
        with:
          apiToken: ${{ secrets.CF_API_TOKEN }}
          accountId: ${{ secrets.CF_ACCOUNT_ID }}
          workingDirectory: frontend
          command: pages deploy out --project-name=myproject

      - name: Install backend deps
        run: cd backend && pnpm install --no-frozen-lockfile

      - name: Deploy Backend to Cloudflare Workers
        uses: cloudflare/wrangler-action@v3
        with:
          apiToken: ${{ secrets.CF_API_TOKEN }}
          accountId: ${{ secrets.CF_ACCOUNT_ID }}
          workingDirectory: backend
          command: deploy

  deploy-server:
    if: github.event.inputs.deploy_target == 'server'
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Deploy to VPS via SSH
        uses: appleboy/ssh-action@v1
        with:
          host: ${{ secrets.SERVER_HOST }}
          username: ${{ secrets.SERVER_USER }}
          key: ${{ secrets.SERVER_SSH_KEY }}
          script: |
            cd ~/projects/myproject
            git pull origin main
            pnpm install
            cd frontend && pnpm build && cd ..
            cd backend && pnpm install && cd ..
            pm2 restart myproject 2>/dev/null || echo "No PM2 process"
            echo "✅ Deployed to server"
```

### 9.2 Add GitHub Secrets

Go to **Repo → Settings → Secrets and variables → Actions**:

| Secret | Value |
|--------|-------|
| `CF_API_TOKEN` | Cloudflare API token |
| `CF_ACCOUNT_ID` | Cloudflare account ID |
| `SERVER_HOST` | Your server IP or domain |
| `SERVER_USER` | `nhprince` |
| `SERVER_SSH_KEY` | Contents of `~/.ssh/id_ed25519` (private key) |

### 9.3 Generate SSH Key for Server

```bash
ssh-keygen -t ed25519 -C "your-email" -f ~/.ssh/id_ed25519
# Add public key to GitHub → Settings → SSH Keys
# Add private key as SERVER_SSH_KEY secret
```

---

## 10. Daily Greeting Cron Job

> **🤖 Agent Tip:** Just say *"Set up a daily morning greeting that sends different messages to me on Telegram"* — Saturday will create the script and schedule the cron job.

### 10.1 Create Greeting Script

**~/.hermes/scripts/greeting.sh:**

```bash
#!/bin/bash
GREETINGS=(
  "Good morning, Prince! ☀️ Ready to build something amazing today?"
  "Rise and shine, boss! 🚀 Your server is running smooth."
  "Hello Prince! 💻 All systems green. What are we building today?"
  "Morning, Prince! 🌟 New day, new possibilities."
  "Hey boss! ⚡ Server's been waiting for you."
  "Good morning, Prince! 🎯 Let's make today count."
  "Wakey wakey, Prince! ☕ Coffee's on me (virtually)."
  "Hello, boss! 🛠️ All tools are ready for you."
  "Morning, Prince! 📊 Everything's running perfectly."
  "Hey Prince! 🎨 Time to create something beautiful."
)

DAY=$(date +%d)
INDEX=$((DAY % ${#GREETINGS[@]}))
echo "${GREETINGS[$INDEX]}"
```

```bash
chmod +x ~/.hermes/scripts/greeting.sh
```

### 10.2 Set Up Cron via Hermes

```
# Ask Saturday to set up a daily 8 AM greeting cron job
# Target: Telegram → NH Prince Pranhan
```

---

## 11. Free Web Search

> **🤖 Agent Tip:** You don't need to set this up manually. Just ask Saturday *"search for [anything]"* — it already has free web search built in via DuckDuckGo.

### 11.1 How It Works

**~/.hermes/scripts/web_search.py:**

```python
#!/usr/bin/env python3
"""Free web search via DuckDuckGo HTML — no API key needed"""
import sys
import urllib.request
import urllib.parse
import re

def search(query, num_results=5):
    encoded = urllib.parse.quote_plus(query)
    url = f"https://html.duckduckgo.com/html/?q={encoded}"
    
    req = urllib.request.Request(url, headers={
        "User-Agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36"
    })
    
    try:
        resp = urllib.request.urlopen(req, timeout=15)
        html = resp.read().decode("utf-8", errors="ignore")
        
        results = []
        # Extract results
        pattern = r'result__url[^>]*>([^<]+)</a>.*?<a[^>]*result__a[^>]*>(.*?)</a>'
        matches = re.findall(pattern, html, re.DOTALL)
        
        for url, title in matches[:num_results]:
            title = re.sub(r'<[^>]+>', '', title).strip()
            url = url.strip()
            if title and url:
                results.append({"title": title, "url": url})
        
        return results
    except Exception as e:
        return [{"error": str(e)}]

if __name__ == "__main__":
    query = " ".join(sys.argv[1:]) if len(sys.argv) > 1 else "test"
    results = search(query)
    for r in results:
        if "error" in r:
            print(f"Error: {r['error']}")
        else:
            print(f"📌 {r['title']}")
            print(f"   {r['url']}\n")
```

```bash
chmod +x ~/.hermes/scripts/web_search.py
# Usage: python3 ~/.hermes/scripts/web_search.py "your search query"
```

---

## 12. Troubleshooting

> **🤖 Agent Tip:** Instead of debugging manually, just tell Saturday *"The gateway won't start"* or *"My deployment is failing"* — it will diagnose and fix the issue for you.

### 12.1 Gateway Won't Start

```bash
# Check logs
sudo journalctl -u hermes-gateway -n 50

# Check config
hermes config check

# Restart
sudo systemctl restart hermes-gateway
```

### 12.2 Out of Memory During npm/pnpm Install

```bash
# Increase Node.js memory limit
NODE_OPTIONS="--max-old-space-size=768" pnpm install

# Or use swap
sudo fallocate -l 1G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
```

### 12.3 Wrangler Authentication Issues on Remote Server

```bash
# Use API token instead of browser login
export CLOUDFLARE_API_TOKEN="your-token"
wrangler whoami

# If token is set but not working, ensure it has correct permissions:
# - Workers Edit
# - KV Storage Edit
# - D1 Edit
# - R2 Storage Edit
```

### 12.4 GitHub Actions Deployment Fails

```bash
# Check workflow run logs
gh run list --limit 5
gh run view <run-id> --log-failed

# Common issues:
# 1. Missing GitHub secrets → add them in repo settings
# 2. pnpm lockfile missing → run pnpm install locally and commit
# 3. accountId not set in workflow → add accountId: ${{ secrets.CF_ACCOUNT_ID }}
# 4. Pages project not created → run: wrangler pages project create <name>
```

### 12.5 WhatsApp Can't Send to a Number

The WhatsApp bridge only supports **pre-synced contacts**. Save the contact in your phone's address book first, then try again.

---

## 13. Free Student Benefits 🎓

> If you're a student, you can get **even more for free** — including credits that can cover the VPS itself!

### GitHub Student Developer Pack

Apply at [education.github.com/pack](https://education.github.com/pack) — it's free for students.

| Benefit | Value | Link |
|---------|-------|------|
|| **Microsoft Azure** | **$100 credits** (via Azure for Students — same as above) | azure.com |
| **DigitalOcean** | **$200 credits for 60 days** | digitalocean.com |
| **Heroku** | **$13/month for 24 months** ($312 total) | heroku.com |
| **GitHub Copilot** | **Free Pro tier** — AI code completion | github.com/features/copilot |
| **GitHub Codespaces** | **Free Pro** — cloud dev environment (60 hrs/month) | github.com/codespaces |
| **JetBrains IDEs** | **Free for 1 year** (renewable) — IntelliJ, PyCharm, WebStorm | jetbrains.com |
| **MongoDB Atlas** | **$50 credits + free certification** | mongodb.com/atlas |
| **Namecheap** | **1 free domain for 1 year** (.me, .dev, etc.) | namecheap.com |
| **Educative** | **6 months free** — 70+ courses | educative.io |
| **DataCamp** | **3 months free** — data science & Python | datacamp.com |
| **Notion** | **Education plan + AI responses** | notion.so |
| **Microsoft 365** | **Free** — Word, Excel, PowerPoint + 1TB OneDrive | microsoft.com/365 |
| **Datadog** | **Free Pro plan** — monitoring & logging | datadoghq.com |
| **Clerk** | **Free Pro plan** — auth & user management | clerk.com |
| **GitHub Cert** | **Free exam voucher** — official GitHub certification | github.com/certification |

### 🏆 Top Picks for This Setup

1. **Azure $100 credits** → Run your VPS for free (the one thing that costs money!)
2. **DigitalOcean $200** → Staging server or database hosting
3. **JetBrains WebStorm** → Best TypeScript/React IDE, free for students
4. **GitHub Copilot** → AI pair programmer while coding
5. **Namecheap domain** → Professional domain for your portfolio
6. **GitHub Cert** → Get certified for free, boosts your resume

> **💡 With student credits, the entire setup can be $0/month — including the VPS!**

---

## 📊 Server Specifications

| Resource | Value |
|----------|-------|
| **OS** | Ubuntu 24.04 LTS |
| **CPU** | 2 vCPU (AMD EPYC 7763) |
| **RAM** | 842MB |
| **Disk** | 29GB SSD |
| **Provider** | Microsoft Azure |
| **Control Panel** | HestiaCP |
| **Web Server** | nginx |
| **Database** | MariaDB |
| **PHP** | 8.3, 8.4, 8.5 |
| **Node.js** | 22 LTS |
| **AI Assistant** | Hermes Agent (Saturday) |

## 🔗 Useful Links

- **Hermes Agent Docs:** https://hermes-agent.nousresearch.com/docs
- **OpenRouter:** https://openrouter.ai
- **Cloudflare Dashboard:** https://dash.cloudflare.com
- **GitHub Education Pack:** https://education.github.com/pack
- **HestiaCP:** https://hestiacp.com

---

## 🗺️ A-to-Z Example Workflow — From Idea to Live Project

> This is the entire development lifecycle. From the moment you have an idea to the moment it's live on a custom domain. **The agent does everything — you just direct.**

Let's walk through a real example: **You want to build a SaaS landing page with a contact form.**

---

### Phase 1: 🧠 Planning (You + AI Chat Tools)

**Tools:** Claude, Gemini, ChatGPT, or any AI chat — for brainstorming and high-level planning

Before talking to Saturday, you plan the big picture using your favorite AI chat tools:

```
You → ChatGPT/Claude/Gemini:
"I want to build a SaaS landing page for my 
project 'TaskFlow' — a task management app. 
Give me a feature list, tech stack recommendation, 
and page structure."
```

You'll get back:
- Feature list (hero, features, pricing, contact, FAQ)
- Tech stack suggestion (Next.js + Tailwind + Hono + D1)
- Page structure and component breakdown
- Database schema ideas

> **💡 Tip:** Use web-based AI chats (Claude, Gemini, ChatGPT) for brainstorming and planning. Use Saturday (your server agent) for *building and deploying*.

**Output of this phase:** A rough plan, feature list, and tech stack decision.

---

### Phase 2: 🚀 Hand Off to Saturday (Your Server Agent)

**Tool:** Saturday (Hermes Agent) via Telegram

Now you take that plan to Saturday:

```
You → Saturday (on Telegram):
"Create a new project called 'taskflow' — 
SaaS landing page with Next.js frontend and 
Hono backend. Features: hero section, features 
grid, pricing table, contact form, FAQ accordion. 
Use dark theme with glassmorphism styling."
```

Saturday will:
1. ✅ Scaffold the full project structure
2. ✅ Set up Next.js + Tailwind frontend
3. ✅ Set up Hono backend with D1 database
4. ✅ Create all components and pages
5. ✅ Set up KV for contact form submissions
6. ✅ Push everything to GitHub
7. ✅ Configure CI/CD pipeline

**Output of this phase:** A fully scaffolded project on GitHub, ready for development.

---

### Phase 3: 🔨 Continuous Development Sessions

**Tool:** Saturday (Hermes Agent) via Telegram

Now the real work happens in back-and-forth sessions:

```
You: "Add a testimonials section with 3 sample 
      testimonials and star ratings"

Saturday: [Creates the component, adds sample data, 
           commits and pushes]

You: "The pricing table needs a monthly/yearly 
      toggle. Add that."

Saturday: [Adds toggle state, updates pricing logic, 
           commits and pushes]

You: "Change the color scheme to blue instead of 
      purple"

Saturday: [Updates Tailwind config, all components 
           reflect the change, commits and pushes]
```

Every change is:
- ✅ Committed to Git automatically
- ✅ Pushed to GitHub
- ✅ Deployed to Cloudflare via CI/CD
- ✅ Live within 1-2 minutes

> **💡 This is the key workflow:** You describe what you want in plain English. Saturday codes it, commits it, and deploys it. No manual git commands. No manual builds. No manual deploys.

---

### Phase 4: 🌐 Get Your Free Cloudflare URLs

Once the first deployment happens, Saturday gives you:

```
✅ Frontend: https://taskflow.pages.dev
✅ Backend:  https://taskflow.nurulhudaprince18.workers.dev
✅ API Health: https://taskflow.nurulhudaprince18.workers.dev/api/health
```

These are **live, production URLs** — free, fast, global CDN, SSL included.

You can share these URLs immediately. They work right away.

> **💡 Cloudflare Pages** gives you unlimited bandwidth, unlimited requests, and a global CDN — all free. Your site loads fast anywhere in the world.

---

### Phase 5: 🔗 Connect a Custom Domain (Optional)

**Tool:** Saturday (Hermes Agent) via Telegram

When you're ready for a professional domain:

```
You: "Connect taskflow.com to my project"

Saturday will:
1. Add the custom domain to Cloudflare Pages
2. Configure DNS records (CNAME, A, or ALIAS)
3. Set up SSL certificate (automatic, free)
4. Configure redirects (www → root, HTTP → HTTPS)
5. Verify everything is working
```

**Before you start:**
- Buy a domain (Namecheap, Cloudflare Registrar, or free from GitHub Student Pack)
- If using Cloudflare DNS, add the domain to your Cloudflare account first

**After setup:**
```
✅ https://taskflow.com → Your live site
✅ https://www.taskflow.com → Redirects to taskflow.com
✅ SSL certificate → Automatic, free, auto-renewing
```

> **💡 Free domain option:** GitHub Student Pack includes 1 free domain from Namecheap (.me, .dev, etc.) for 1 year.

---

### Phase 6: 🔄 Ongoing Iteration

The project never stops evolving. Your workflow becomes:

```
1. Think of a feature or fix
2. Tell Saturday on Telegram
3. Saturday codes, commits, deploys
4. Check the live site
5. Repeat
```

**Example ongoing tasks:**
```
"Add dark mode toggle"
"Fix the mobile menu — it's not closing after clicking a link"
"Add a blog section with MDX support"
"Set up email notifications for contact form submissions"
"Add Google Analytics"
"Optimize images — they're loading slow"
```

Each task follows the same flow: **You talk → Saturday builds → It goes live.**

---

### 📋 Summary: The Complete Flow

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  1. 🧠 PLAN    → Brainstorm with Claude/Gemini/ChatGPT     │
│                    Get features, structure, tech stack      │
│                          │                                  │
│  2. 🚀 SCAFFOLD → Tell Saturday: "Create project X"        │
│                    Agent builds full project + pushes       │
│                          │                                  │
│  3. 🔨 DEVELOP  → Back-and-forth sessions with Saturday    │
│                    "Add this", "Fix that", "Change this"    │
│                    Auto-committed + auto-deployed           │
│                          │                                  │
│  4. 🌐 LIVE     → Get free Cloudflare URLs immediately     │
│                    pages.dev + workers.dev                  │
│                          │                                  │
│  5. 🔗 DOMAIN   → Connect custom domain (optional)         │
│                    Free SSL, global CDN                     │
│                          │                                  │
│  6. 🔄 ITERATE  → Keep building, keep shipping             │
│                    One conversation at a time               │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

> **🎯 The bottom line:** You're the CEO. Saturday is the developer. You decide *what* to build. Saturday figures out *how* to build it and ships it — all for $0/month.

---

## 👏 Credits & Acknowledgments

This guide and the entire setup were built by:

- **Prince (NH Prince Pradhan)** — Author, architect, and boss 🧑‍💻
  - [GitHub](https://github.com/nhprince) · [LinkedIn](https://linkedin.com/in/nhprince) · [Facebook](https://facebook.com/nhprince1982)
- **Saturday** — The AI assistant (running on Hermes Agent) that does all the heavy lifting 🤖
  - Built on [Hermes Agent](https://hermes-agent.nousresearch.com) by Nous Research
  - Powered by free models from [OpenRouter](https://openrouter.ai)

### Tools That Made This Possible (All Free)

| Tool | Purpose |
|------|---------|
| Hermes Agent | AI assistant running the entire workflow |
| Cloudflare Pages + Workers + D1 + KV | Hosting, backend, database, storage |
| GitHub + Actions | Source control and CI/CD |
| OpenRouter | Free AI models |
| DuckDuckGo | Free web search |
| Next.js + Hono + Tailwind | Development frameworks |
| PM2 | Process manager |
| Telegram + WhatsApp | Messaging platforms |

> 📝 **This guide is auto-updated every Friday by Saturday (Hermes Agent).**
> Last auto-update: 2026-06-06
