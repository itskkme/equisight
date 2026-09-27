# 📊 EquiSight — AI Equity Research Platform

A professional-grade AI-powered equity research platform built with vanilla HTML/CSS/JS and Google Gemini AI. Designed to function as your personal Senior Equity Research Analyst.

---

## ✨ Features

- **Financial Statement Analyzer** — Paste any P&L, Balance Sheet, or Cash Flow statement and get institutional-quality ratio analysis, red flag detection, and investment verdicts
- **Stock Comparator** — Compare 2–5 stocks side-by-side with valuation multiples, return ratios, and ranked BUY/HOLD/SELL recommendations
- **Quick Analyst** — Generate structured investment theses (Bull/Base/Bear), MOAT assessments, valuation commentary, and red flag scans
- **AI Chat Analyst** — Continuous conversation with a Senior Equity Research Analyst persona powered by Gemini

---

## 🚀 Getting Started

### 1. Get a Gemini API Key
- Go to [Google AI Studio](https://aistudio.google.com)
- Sign in and create a new API key (free tier available)

### 2. Use the App
- Open the deployed app (or `index.html` locally)
- Paste your Gemini API key in the top bar and click **Save**
- Start analyzing — paste financial data from Screener.in, Moneycontrol, NSE/BSE filings, or any annual report

---

## 🛠 Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript (zero dependencies, zero build step)
- **AI:** Google Gemini 1.5 Flash via REST API
- **Fonts:** IBM Plex Mono, Syne, Inter (Google Fonts)
- **Deployment:** Vercel (static)

---

## 📁 Project Structure

```
equisight/
├── index.html      # Entire application (single file)
├── vercel.json     # Vercel deployment config
└── README.md       # This file
```

---

## ☁️ Deploy to Vercel

### Option A — Vercel Dashboard (easiest)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import your GitHub repo
4. Click **Deploy** — no build settings needed

### Option B — Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

---

## ⚠️ Disclaimer

EquiSight is for **informational and educational purposes only**. It does not constitute financial advice, a solicitation, or a recommendation to buy, hold, or sell any security. Always consult a SEBI-registered financial advisor before making investment decisions.

---

## 📄 License

MIT License — free to use, modify, and deploy.
