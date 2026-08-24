# Hi, I'm potaterrr 👋

**Python automation developer** building pipelines that connect data to Make.com — from job scrapers to trading-signal engines.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Make.com-6D00CC?style=for-the-badge&logo=make&logoColor=white" alt="Make.com" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="REST APIs" />
  <img src="https://img.shields.io/badge/Webhooks-F62D00?style=for-the-badge&logo=webhooks&logoColor=white" alt="Webhooks" />
</p>

## 🚀 Projects

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

## 🧠 How I Work

I believe understanding *how* systems communicate beats memorizing platform features. Every workflow I design is:

1. **Resilient** — error handling and fallback alerts built in
2. **Scalable** — clean logic, modular design
3. **Optimized** — minimized API calls and data redundancy

When things break, I reach for Postman, developer consoles, and logs to find the bottleneck fast.

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=potaterrr&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=potaterrr&layout=compact&hide_border=true" alt="Top languages" height="165" />
</p>

## 📬 Contact

The **fastest way to reach me is Telegram** — I always respond there first.

*   **✈️ Telegram:** [@portaterrrr](https://t.me/portaterrrr) *(preferred)*
*   **📧 Email:** [kristiandyanbusiness@gmail.com](mailto:kristiandyanbusiness@gmail.com)

<p align="left">
  <a href="https://t.me/portaterrrr">
    <img src="https://img.shields.io/badge/Telegram-Message_Me-26A69A?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
</p>

Open to discussing new technologies, automation strategies, or freelance opportunities.

---
<p align="center"><i>"Automating the boring stuff, one node at a time."</i></p>
