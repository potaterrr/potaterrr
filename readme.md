# Hi, I'm **Christian John** — but everybody calls me **potaterrr** 🥔

**Python automation developer** growing pipelines that connect data to Make.com and n8n — from job scrapers to trading-signal engines to AI agents that write follow-up emails for me. If it's repetitive, I'll automate it. If it involves potatoes, even better. 🥔

🌐 Portfolio site: [potaterrr.github.io](https://potaterrr.github.io)

🔎 Searching *potater* lands here too — same potato, fewer letters.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenRouter_LLMs-6467F2?style=for-the-badge&logo=openai&logoColor=white" alt="LLMs" />
  <img src="https://img.shields.io/badge/Make.com-6D00CC?style=for-the-badge&logo=make&logoColor=white" alt="Make.com" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Webhooks-F62D00?style=for-the-badge&logo=webhooks&logoColor=white" alt="Webhooks" />
</p>

## 🥔 Featured Projects

<table>
  <tr>
    <th width="50%">💤 <a href="https://github.com/potaterrr/dead-lead-followup">Dead Lead Follow-up</a></th>
    <th width="50%">📞 <a href="https://github.com/potaterrr/voice-receptionist">AI Voice Receptionist</a></th>
  </tr>
  <tr>
    <td valign="top">
      An AI-powered, human-in-the-loop automation that resurrects dormant leads: an LLM writes personalized check-in emails, files them as <b>Gmail drafts</b> (never auto-sent!), drops a booking button into every one, and tracks each lead through the review lifecycle on ClickUp.<br><br>
      • <b>Human-in-the-loop by design</b> — AI drafts, human approves, nothing sends itself<br>
      • Anti-hallucination guardrails: the only link in any email is mine<br>
      • Full setup guide, config reference and production-tested lessons in the README
    </td>
    <td valign="top">
      An AI receptionist that answers missed calls and books appointments — built <b>three times</b> (Make / n8n / Zapier) on a shared Vapi + Twilio voice layer, so platforms can be compared apples-to-apples before choosing one.<br><br>
      • Answers instantly, capturing name, number, intent and preferred slot as structured data<br>
      • Conflict-checks Google Calendar, books real slots, alerts the owner with a summary<br>
      • Simulated end-to-end today — live phone calls are a plug-in away
    </td>
  </tr>
</table>

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

### [ai-folklore](https://github.com/potaterrr/ai-folklore) (theory)
The research stage of a folklore-story video pipeline: **research → AI script → (Veo video) → publish**. A zero-dependency Python scraper pulls folklore stories (Philippine mythology front-loaded) from Wikipedia and feeds them to Make.com or n8n — Gemini writes the script, a Gmail draft waits for review.

- **Zero pip dependencies** — stdlib `urllib` + `json`, Python 3.9+ is all it needs
- Built-in dedupe remembers delivered titles, so each run pushes only new stories
- Ships with importable Make.com and n8n blueprints plus a full testing report

### [rss-news](https://github.com/potaterrr/rss-news) (personal automation)
An automated news curation pipeline for the **AI Tech & Automation Hub** Facebook page: a Python script fetches tech & AI RSS feeds (Hacker News, Phoronix, The Verge…), filters by keyword, and POSTs a digest to a Make.com webhook that drafts the post with Gemini, generates a graphic with Imagen, and publishes to Facebook Pages.

- **GitHub Actions** cron runs it every Sunday at 6:00 AM PHT
- Keyword filtering + `seen_articles.json` dedupe so nothing posts twice
- A random banner image from the repo rides along with every digest

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

## 🥔 Dotfiles

System/Hardware:  
💻  20RA004VPH (ThinkPad E14)  
🧠  Intel(R) Core(TM) i7-10510U (8) @ 4.90 GHz  
🎮  AMD Radeon 550X Series [Discrete]  
🐧  Debian GNU/Linux 13 (trixie) x86_64  
⚙️  Linux 6.12.101+deb13-amd64

Install ([dotfiles](https://github.com/potaterrr/dotfiles)):

[![Animated terminal: curl -fsSL https://potaterrr.github.io/install | sh](assets/install-terminal.svg)](https://potaterrr.github.io/install)

</div>

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-stats-extended.vercel.app/api?username=potaterrr&theme=radical" alt="GitHub stats" height="165" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=potaterrr&layout=compact&theme=radical&hide_border=true" alt="Top languages" height="165" />
</p>

## 📬 Contact

You can reach me anywhere below.

*   **✈️ Telegram:** [@portaterrrr](https://t.me/portaterrrr) *(preferred)*
*   **💬 WhatsApp:** [@potaiterrr](https://wa.me/potaiterrr)
*   **📘 Facebook:** [Potaterrr](https://www.facebook.com/profile.php?id=61593886946042)
*   **📧 Email:** [kristiandyanbusiness@gmail.com](mailto:kristiandyanbusiness@gmail.com)

<p align="left">
  <a href="https://t.me/portaterrrr">
    <img src="https://img.shields.io/badge/Telegram-Message_Me-26A69A?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="https://wa.me/potaiterrr">
    <img src="https://img.shields.io/badge/WhatsApp-potaiterrr-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
  <a href="https://www.facebook.com/profile.php?id=61593886946042">
    <img src="https://img.shields.io/badge/Facebook-Potaterrr-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
  </a>
  <a href="mailto:kristiandyanbusiness@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say_Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

Open to discussing new technologies, automation strategies, or freelance opportunities. If your leads are gathering dust, I know a workflow for that. 🥔

---
<p align="center"><i>"Mashing the boring stuff so you don't have to."</i></p>
