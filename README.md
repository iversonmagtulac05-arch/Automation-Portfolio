**My n8n Automation Portfolio**

Welcome! This repository contains a collection of production-ready n8n workflows built to automate business processes, integrate APIs, and orchestrate AI systems.

### 🌦️ Project 1: n8n Proof-of-Concept (Weather Automation)

![Weather Bot Automation Pipeline](./images/weather-bot-flow.png)

#### 📝 Project Background
Developed as an initial proof-of-concept to evaluate the n8n platform, focusing on node-based architecture, multi-step data routing, and API integration.

#### ⚙️ How It Works
1. **Trigger:** Initiates daily at 6:00 AM via a **Schedule Trigger**.
2. **Fetch:** Queries the **OpenWeatherMap API** for forecast data.
3. **Transform:** Parses the JSON payload using JavaScript expressions (`Math.round`) to format metrics.
4. **Deliver:** Dispatches a structured text digest via the **Telegram Bot API**.
