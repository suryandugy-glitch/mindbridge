# 🌉 MindBridge

### *Always‑on mental health support for students. No wait. No stigma. No cost.*

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-brightgreen)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-18-61dafb)](https://reactjs.org/)

## 🚨 The problem we solve

> **1 in 3** students suffer from severe anxiety or depression.  
> **6–8 weeks** average wait time for campus counseling.  
> **75%** of cases go untreated due to stigma & cost.

**MindBridge** is an AI companion that's there **24/7, judgment‑free, and completely private.**

## ✨ Features

| Feature | Description |
|---------|-------------|
| 💬 **AI Chat** | Empathetic, evidence‑based conversations (Claude AI) |
| 📊 **Mood Tracking** | Log daily moods, stressors, and notes |
| 📈 **AI Insights** | Personalized analysis + CBT coping strategies |
| 🆘 **Crisis Mode** | Instant 988 & Crisis Text Line when you need help |
| 🔒 **Privacy First** | Your data never leaves your browser (localStorage) |
| 📱 **Mobile Ready** | Works perfectly on phones, tablets, laptops |

## 🚀 Deploy your own copy

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/YOUR_USERNAME/mindbridge)

1. Click the button above (replace `YOUR_USERNAME` with your GitHub username)
2. Add your `ANTHROPIC_API_KEY` (get one free from [console.anthropic.com](https://console.anthropic.com))
3. Click **Create Web Service**
4. Your live site will be ready in 3–5 minutes

## 🛠️ Run locally

```bash
git clone https://github.com/YOUR_USERNAME/mindbridge.git
cd mindbridge
npm run install-all
cp .env.example .env   # add your Anthropic API key
npm run dev
