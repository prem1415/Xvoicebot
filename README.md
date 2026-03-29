# Prem — AI Agent Voicebot 🤖

live link-: https://xvoicebot.onrender.com



This is a **voice-enabled chatbot** designed for the Stage-1 assessment of the **AI Agent Team** at **100x**. The bot responds as **Prem**, a 22-year-old AI/software engineer, in **first-person** with a professional, friendly, and confident tone. 🌟

The web app allows users to **ask questions by voice or text** and receive spoken and written responses that reflect prem’s persona. 💬

---
Live link-: https://one00x-voicebot.onrender.com/


## Features ✨   

- **Voice Input:** Users can speak their questions using the browser microphone. 🎤
- **Text Input:** Users can type questions manually. ⌨️
- **AI Responses:** Powered by **OpenRouter API** to generate first-person answers as Rohan. 💡
- **Speech Output:** Utilizes browser speech synthesis to read answers aloud. 🔊
- **User-Friendly:** No coding or API key setup is required for testing. 👍
- **Cross-Platform:** Works on desktop and mobile browsers that support Web Speech API. 📱💻

---

## Example Questions ❓

- What should we know about your life story in a few sentences?
- What’s your #1 superpower? 🦸‍♂️
- What are the top 3 areas you’d like to grow in?
- What misconception do your coworkers have about you?
- How do you push your boundaries and limits? 🚀

---

## Project Structure 📁

100x-voicebot/
├─ main.py # Flask backend serving API & static files
├─ public/
│ └─ index.html # Frontend UI
├─ requirements.txt # Python dependencies
└─ .env # Environment variables (OpenRouter API key, not included in repo)

---

## Installation (for local testing) ⚙️

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/100x-voicebot.git
   cd 100x-voicebot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a .env file in the root folder with your OpenRouter API key:
   ```ini
   OPENROUTER_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
   ```
4. Run the Flask server:
   ```bash
   python main.py
   ```
5. Open your browser at http://localhost:5000 to test the voicebot. 🌐

## Deployment 🚀

The project is deployed on Render:

**URL:** https://xvoicebot.onrender.com

**Environment Variables:** OpenRouter API key is securely stored on the server. 🔒

No manual configuration is required for testers. 

## System Prompt (Voicebot Personality) 🗣️

The bot uses a detailed system prompt to ensure responses match Rohan’s persona:

- First-person, professional, friendly, and confident
- Short, clear, and concise (2–4 sentences)
- Includes examples or measurable results whenever relevant
- Canadian English spelling 🇨🇦
- Reflects skills, background, and experience in AI, software engineering, and automation

## Tech Stack 🛠️

- **Backend:** Python, Flask, Flask-CORS
- **Frontend:** HTML, JavaScript (Web Speech API)
- **AI:** OpenRouter API (deepseek-r1-0528-qwen3-8b)
- **Deployment:** Render.com
- **Environment Management:** python-dotenv

## Author ✍️

**PREM**  
AI & Software Engineer

**GitHub:** https://github.com/prem1415 
**LinkedIn:** [https://www.linkedin.com/in/rohan-vinay-chaudhary/](https://www.linkedin.com/in/rohan-chaudhary-51b260209/)

## License 📜

This project is for assessment purposes only and is not licensed for commercial use.

---

