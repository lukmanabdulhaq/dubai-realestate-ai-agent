# 🏠 Dubai Real Estate AI Agent
### Autonomous Virtual Portfolio Manager & Lead Triage

![AWS ML Essentials](https://img.shields.io/badge/AWS-ML_Essentials-blue?logo=amazon-aws)
![AWS GenAI](https://img.shields.io/badge/AWS-Generative_AI-white?logo=amazon-aws)

## 🎥 System Demo
## 🎥 System Demo

<div align="center">
  ![System Demo](demo.gif)
</div>

## 🎯 Overview
An event-driven AI automation pipeline designed for the Dubai property market. This system handles multilingual inquiries, performs ROI calculations, and triages leads using sentiment analysis.

## 🏗️ Technical Architecture
```mermaid
graph TD
    A[Customer Query: Webhook/Form] --> B{Gemini 1.5 Flash}
    B -->|Language Detection| C[Arabic / English Response]
    B -->|Sentiment Analysis| D{Triage Logic}
    D -->|General Inquiry| E[Gmail: Portfolio Summary]
    D -->|High-Priority Lead| F[Telegram: Instant Agent Alert]
    F --> G[AWS Cloud Ingestion Placeholder]
```

### 📊 System Evidence
| Architecture Layout | Multilingual AI Response | Real-time Alert |
| :--- | :--- | :--- |
| ![Architecture](architecture.png) | ![Arabic Support](arabic_response.png) | ![Telegram Alert](telegram_alert.png) |

---
*Maintained by Lukman Abdulhaq — AI Operations & Data Engineer*
