# 🥾 AI Trail Run Assistant

An AI-powered assistant that helps determine if I should go for a trail run today — based on my **schedule**, **weather**, **air quality**, and **trail conditions**.

---

## 📌 Project Purpose

As a Business Analyst with experience in analytics, coordination, and product thinking, I built this project to:
- Learn and implement AI-agent orchestration
- Add a technically rich, real-world portfolio piece
- Showcase cross-functional understanding of automation + AI + analysis

---

## ⚙️ How It Works

1. ✅ Checks your calendar for a **"trail run"** event
2. ☁️ Pulls real-time **weather** data (Boston, MA)
3. 🏭 Pulls **Air Quality Index (AQI)** from API
4. 🥾 Reads trail info from a **Google Sheet**: name, time, elevation, shade, etc.
5. 📬 Sends an **email summary** with the best trail (if suitable) using Gmail API

---

## 🛠️ Tools & Tech

- **n8n** (workflow automation platform)
- **OpenAI GPT-4o-mini** (LLM agent)
- **Google Calendar + Gmail** (OAuth integrations)
- **OpenWeatherMap API**
- **AirNow API** (for AQI)
- **Google Sheets API**
- **Simple Memory Node** (for recent trail recommendations)
- **Markdown/HTML email formatting**

---

## 🧠 AI Agent Prompt Logic

- Acts as an intelligent outdoor assistant
- Evaluates time window, weather, air quality, and trail features
- Filters based on shade, time, and past memory
- Sends a friendly, clear email with the best trail recommendation — or a polite reason if not suitable

---

## ✅ Sample Output

```txt
🌲 Today's Recommended Trail: Middlesex Fells Rock Circuit  
📏 Distance: 4 miles  
📈 Elevation: 636 ft  
⏱️ Estimated Time: 1 hour 20 minutes  
📝 Reason: Shady trail, perfect for today’s warm conditions!
