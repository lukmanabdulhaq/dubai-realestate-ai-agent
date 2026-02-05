# 🇦🇪 Dubai Real Estate AI Support Agent
### Autonomous Multilingual Triage & Data Pipeline

[![AWS Certified](https://img.shields.io/badge/AWS-Data_Engineer_Associate-orange?logo=amazon-aws)](https://aws.amazon.com/certification/certified-data-engineer-associate/)
[![n8n](https://img.shields.io/badge/Orchestration-n8n-FF6D5B?logo=n8n)](https://n8n.io/)
[![LLM](https://img.shields.io/badge/AI_Model-Gemini_1.5_Flash-4285F4?logo=google-gemini)](https://deepmind.google/technologies/gemini/)



## 🎯 Overview
This project is an **event-driven AI automation pipeline** designed for the high-stakes Dubai Real Estate market. It functions as a 24/7 Senior Portfolio Manager, providing instant ROI analysis and property advice while executing an automated triage system for high-priority lead escalation.

## 🏗️ System Architecture
The workflow functions as a robust data pipeline mirroring enterprise cloud architectures:

1.  **Data Ingestion**: Multi-channel intake via **Webhook** and **n8n Form Trigger**.
2.  **Processing Layer**: **Google Gemini 1.5 Flash** acts as the reasoning engine for:
    * **Language Detection**: Automatic switching between Arabic and English.
    * **Sentiment Analysis**: Identifying urgent issues (e.g., financial loss, human-escalation requests).
    * **Domain Expertise**: Providing real-time ROI calculations and DLD fee insights.
3.  **Action & Delivery**:
    * **Gmail API**: Automated delivery of professional email summaries.
    * **Telegram API**: Real-time "High-Priority" alerts sent to management for sentiment-triggered escalations.

## 🎥 Demo
![AI Agent in Action](demo.mp4)
*The demo showcases the agent handling an ROI inquiry in Arabic and triggering a Telegram alert for a high-priority support request.*

## 🛠️ Tech Stack & Skills
* **Data Orchestration**: n8n (Advanced Logic & API Integration)
* **Generative AI**: Google Gemini 1.5 Flash (NLP & Reasoning)
* **Security**: OAuth 2.0 implementation for Google Cloud Console.
* **Data Engineering**: Event-driven architecture, JSON schema management, and automated triage.

## 🚀 Key Features
* **Zero-Shot Localization**: Detects and mirrors the user’s language (English/Arabic) automatically.
* **Smart Triage**: Uses LLM-based intent classification to distinguish between general info and "High-Risk" sentiment.
* **Production Ready**: Configured with professional error handling (HTML parse modes) and secure API pathing.

## 📂 Project Files
* `customer_support_AI.json`: The full n8n workflow export (redacted for security).
* `demo.mp4`: A walkthrough of the live system.

---
*Created by an AWS Certified Data Engineer focused on building intelligent, scalable data workflows.*
