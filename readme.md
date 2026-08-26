# Hi, I'm **Christian John** — but everybody calls me **potaterrr** 🥔

**Python automation developer** growing pipelines that connect data to Make.com and n8n — from job scrapers to trading-signal engines to AI agents that write follow-up emails for me. If it's repetitive, I'll automate it. If it involves potatoes, even better.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenRouter_LLMs-6467F2?style=for-the-badge&logo=openai&logoColor=white" alt="LLMs" />
  <img src="https://img.shields.io/badge/Make.com-6D00CC?style=for-the-badge&logo=make&logoColor=white" alt="Make.com" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Webhooks-F62D00?style=for-the-badge&logo=webhooks&logoColor=white" alt="Webhooks" />
</p>

## 🥔 Featured Project

### [Dead Lead Follow-up](https://github.com/potaterrr/dead-lead-followup)
An AI-powered, human-in-the-loop automation that resurrects dormant leads: an LLM writes personalized check-in emails, files them as **Gmail drafts** (never auto-sent!), drops a booking button into every one, and tracks each lead through the review lifecycle on ClickUp.

- **Human-in-the-loop by design** — AI drafts, human approves, nothing sends itself
- Personalization from custom fields: lead name, company, original interest notes
- Anti-hallucination guardrails: the only link in any email is mine
- Full setup guide, config reference and production-tested lessons learned in the README

## 🚀 Other Projects

### [job-scrapper](https://github.com/potaterrr/job-scrapper)
A Python scraper that searches [OnlineJobs.ph](https://www.onlinejobs.ph) for remote jobs matching automation keywords (`n8n`, `make.com`, `zapier`) and pushes each listing as JSON to a Make.com webhook for downstream automation.

- Extracts title, salary, employment type, and **full job description** per listing
- Keyword dedupe + polite, human-like request delays
- Fallback notifications so downstream automations never stall

### [signal-checker](https://github.com/potaterrr/signal-checker)
An automated trading-signal pipeline that evaluates an **SMA crossover strategy** on daily stock prices and dispatches `BUY` / `SELL` / `HOLD` signals as JSON to a Make.com webhook.

- ~400 days of historical closes via **yfinance** (50/200-day defaults)
- Fully configurable through environment variables (symbol, SMA windows, webhook URL)
- Runs automatically on GitHub Actions every weekday at 21:00 UTC

### [make-commits](https://github.com/potaterrr/make-commits)
A Make.com automation that posts every GitHub push to a Facebook Page as a digest — instantly, via webhooks. Built and running entirely on the Make.com free tier.

- Instant pipeline: `git push` → Facebook post lands seconds later (webhooks, no polling)
- One post per push listing every commit message as a bullet (~2 ops per push)
- Ships with a sanitized scenario blueprint + step-by-step setup guide

## 🧠 How I Work

I believe understanding *how* systems communicate beats memorizing platform features. Every workflow I design is:

1. **Resilient** — error handling and fallback alerts built in
2. **Scalable** — clean logic, modular design
3. **Optimized** — minimized API calls and data redundancy

When things break, I reach for Postman, developer consoles, and logs to find the bottleneck fast. (The logs are always lying. Check them anyway.)

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=potaterrr&show_icons=true&hide_border=true&count_private=true&theme=transparent" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=potaterrr&layout=compact&hide_border=true&theme=transparent" alt="Top languages" height="165" />
</p>

## 📬 Contact

The **fastest way to reach me is Telegram** — I always respond there first.

*   **✈️ Telegram:** [@portaterrrr](https://t.me/portaterrrr) *(preferred)*
*   **📘 Facebook:** [Potaterrr](https://www.facebook.com/profile.php?id=61593886946042)
*   **📧 Email:** [kristiandyanbusiness@gmail.com](mailto:kristiandyanbusiness@gmail.com)
*   **💬 Discord:** **potaterrr** *(find me in our shared servers)*

<p align="left">
  <a href="https://t.me/portaterrrr">
    <img src="https://img.shields.io/badge/Telegram-Message_Me-26A69A?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="https://www.facebook.com/profile.php?id=61593886946042">
    <img src="https://img.shields.io/badge/Facebook-Potaterrr-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
  </a>
  <a href="mailto:kristiandyanbusiness@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say_Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://discord.com/users/684383261744431104">
    <img src="https://img.shields.io/badge/Discord-potaterrr-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord: potaterrr" />
  </a>
</p>

Open to discussing new technologies, automation strategies, or freelance opportunities. If your leads are gathering dust, I know a workflow for that. 🥔

---
<p align="center"><i>"Mashing the boring stuff so you don't have to."</i></p>
