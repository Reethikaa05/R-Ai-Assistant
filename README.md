 ██████╗      ██╗ █████╗ ██████╗ ██╗   ██╗██╗███████╗
     ██╔═══██╗     ██║██╔══██╗██╔══██╗██║   ██║██║██╔════╝
     ██║   ██║     ██║███████║██████╔╝██║   ██║██║███████╗
     ██║   ██║██   ██║██╔══██║██╔═══╝ ██║   ██║██║╚════██║
     ╚██████╔╝╚█████╔╝██║  ██║██║     ╚██████╔╝██║███████║
      ╚═════╝  ╚════╝ ╚═╝  ╚═╝╚═╝      ╚═════╝ ╚═╝╚══════╝
                 Python AI Assistant | R‑JARVIS 🤖
A Python-based AI virtual assistant inspired by Iron Man’s J.A.R.V.I.S. It processes voice commands, automates desktop tasks, and integrates with external APIs (Google, YouTube, WhatsApp, Weather).
Table of Contents

## 📑 Table of Contents
- [Project Structure](#project-structure)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration-env)
- [Usage](#usage)
- [Modules Overview](#modules-overview)
- [Troubleshooting](#troubleshooting)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## 📂 Project Structure

R-Ai-Assistant/
│── agent.py                   # Main control file, core Jarvis loop
│── jarvis_animation.py        # Animation/visual feedback
│── Jarvis_file_opner.py       # File opener tool (apps, docs, dirs)
│── jarvis_get_whether.py      # Weather info fetcher
│── Jarvis_google_search.py    # Google search integration
│── Jarvis_prompts.py          # Predefined prompts/responses
│── Jarvis_window_CTRL.py      # Window management
│── keyboard_mouse_CTRL.py     # Keyboard & mouse automation
│── object_detection.py        # Object detection via AI/ML
│── volume_tool.py             # Volume control
│── whatsapp_tool.py           # WhatsApp automation
│── youtube_tool.py            # YouTube automation
│── requirements.txt           # Dependencies
│── .env                       # API keys & environment variables
│── __pycache__/               # Python cache

## 🚀 Features

- 🎙️ **Voice Commands** — Hands-free control using speech recognition  
- 🌐 **Google Search** — Query the web and read results aloud  
- ☁️ **Real-Time Weather** — Get current conditions & forecasts  
- 🖥️ **System Control** — Open apps/files, manage windows, adjust volume  
- 📱 **WhatsApp Automation** — Send messages programmatically  
- 🎬 **YouTube Integration** — Search and play videos seamlessly  
- 🎨 **Visual Feedback** — Jarvis-like UI animations  
- 🎯 **Object Detection** — AI-powered computer vision recognition  
- ⌨️🖱️ **Keyboard & Mouse Automation** — Automate typing, clicks, and navigation

  
## 🛠 Requirements

- **Python 3.9+**
- **Microphone** (for voice input) & **speakers** (for TTS)
- **Chrome/Chromium** or default browser (for certain automations)
- **OS:** Windows / Linux / macOS  

### 🔧 Installation
```bash
Clone the repository and create a virtual environment:
# Create virtual environment
python -m venv venv
```
# Activate virtual environment
```bash
source venv/bin/activate
```

# 🌦️ Weather API (OpenWeather, WeatherAPI, etc.)
```bash
export WEATHER_API_KEY="your_api_key_here"
export WEATHER_LOCATION_DEFAULT="New York"
```

# 🔍 Google Programmable Search
```bash
export GOOGLE_API_KEY="your_api_key_here"
export GOOGLE_CSE_ID="your_cse_id_here"
```

▶️ Usage
Run the main controller:
```bash
python agent.py console
```
Once started, R-JARVIS will:

🎙️ Listen for the wake word (jarvis by default)
🧠 Interpret your voice command
⚡ Execute the requested action or return a spoken/text response

🗣️ Example Commands

🌦️ “Jarvis, what’s the weather like?”
💻 “Open Visual Studio Code.”
🔍 “Search Google for Python decorators.”
🎵 “Play lo-fi hip hop on YouTube.”
💬 “Send a WhatsApp message to Alex: Meeting moved to 5 PM.”
🔊 “Increase the volume to 60%.”


❗ Troubleshooting

🔊 Microphone not detected → Check OS sound input settings & default device
🛑 Permission errors (Windows) → Run terminal as Administrator
🌐 Browser automation issues → Verify browser path & driver versions
🔑 API errors → Double-check .env keys & quota limits
🌍 Unicode/locale issues → Ensure LANGUAGE is set in .env and supported by STT/TTS


Roadmap

🤖 GPT-powered conversational brain
🏠 IoT/Home Automation
🌍 Multi-language STT/TTS
🗓️ Smarter task scheduling

🤝 Contributing

Contributions are highly welcome! 🚀 Whether it’s fixing bugs, improving documentation, or adding new features, your help makes R-JARVIS better.

📌 How to Contribute
Fork this repository
Create a feature branch
Commit your changes
git commit -m "feat: add your feature"
Push to your fork
git push origin feat/your-feature
Open a Pull Request (PR) — and describe your changes clearly


License
This project is open-source under the MIT License. See LICENSE for details.

Author

Reethika Selvam S

If you build something cool with R‑JARVIS, star the repo and share a demo! ✨
