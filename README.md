# 🏠 Dubai Real Estate AI Agent

> **An event-driven AI automation pipeline for the Dubai property market — multilingual lead triage, sentiment analysis, and instant sales alerts via Telegram.**

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)](https://python.org)
[![Gemini](https://img.shields.io/badge/Google-Gemini_1.5_Flash-blue?logo=google)](#)
[![Telegram](https://img.shields.io/badge/Telegram-Bot_API-blue?logo=telegram)](https://core.telegram.org/bots)

## Demo

![System Demo](demo.gif)

> AI agent handling a live customer inquiry — language detection, sentiment triage, ROI calculation, and Telegram alert fired automatically.

## What This Agent Does

1. Detects the language — Arabic or English, responds accordingly
2. Analyses sentiment — classifies intent and urgency
3. Triages the lead — general inquiry vs high-priority buyer
4. Sends portfolio summary — via Gmail for general inquiries
5. Fires instant Telegram alert — for high-priority leads
6. Calculates ROI — property investment projections on demand

## Architecture
```
Customer Query (Webhook / Form)
        ↓
  Gemini 1.5 Flash
  ├── Language Detection → Arabic / English Response
  └── Sentiment Analysis
            ↓
       Triage Logic
       ├── General Inquiry → Gmail: Portfolio Summary
       └── High Priority  → Telegram: Instant Agent Alert
```

## Screenshots

| Arabic Response | Telegram Alert |
|---|---|
| ![Arabic](arabic_response.png) | ![Telegram](telegram_alert.png) |

## Tech Stack

| Component | Technology |
|---|---|
| AI Model | Google Gemini 1.5 Flash |
| Language | Python |
| Notifications | Telegram Bot API |
| Email | Gmail API |

## Related Projects

This agent was the predecessor to the full **[AI Lead Intelligence System](https://github.com/lukmanabdulhaq/ai-lead-intelligence-system)** — a production-grade multi-channel lead automation platform.

## Author

**Lukman Abdul Haq** — AI Automation & Full-Stack Engineer
Accra, Ghana · lukmanabdulhaq1@gmail.com
