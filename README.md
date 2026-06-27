# 🤖 Jarvis - AI Voice Assistant

A Python-based Voice Assistant inspired by J.A.R.V.I.S from Iron Man. This project uses Speech Recognition, Text-to-Speech, Web Automation, Wikipedia Search, Email Services, and System Automation to perform voice-controlled tasks.

---

## 📌 Project Overview

Jarvis is an intelligent desktop assistant capable of understanding voice commands and executing various tasks such as:

- Opening websites
- Searching Wikipedia
- Sending Emails
- Playing Music
- Opening Applications
- Telling Time
- Google Maps Search
- Internet Connectivity Check
- Voice-Based Interaction

The assistant continuously listens for user commands and responds using speech synthesis.

---

## ✨ Features

### 🎤 Voice Recognition
- Speech-to-Text using Google Speech Recognition
- Real-time microphone input
- Continuous voice listening mode

### 🔊 Text-to-Speech
- Voice responses using:
  - pyttsx3
  - gTTS (Google Text-to-Speech)

### 🌐 Web Automation
- Open Google
- Open YouTube
- Open Gmail
- Open Websites using voice commands
- Google Maps location search

### 📚 Information Retrieval
- Wikipedia Search
- WolframAlpha Query Support

### 📧 Email Automation
- Send emails using SMTP
- Voice-controlled email content

### 🎵 Multimedia Controls
- Play Music
- Pause Music
- Next Music
- Voice-controlled media playback

### 💻 System Automation
- Start Applications
- Stop Applications
- Install Python Packages
- Sleep Mode
- Check Internet Connectivity

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core Programming Language |
| SpeechRecognition | Voice Input |
| PyAudio | Microphone Access |
| pyttsx3 | Offline Text-to-Speech |
| gTTS | Online Text-to-Speech |
| Wikipedia API | Knowledge Search |
| WolframAlpha API | Computational Answers |
| SMTP | Email Sending |
| Webbrowser Module | Browser Automation |
| Pygame Mixer | Audio Playback |

---

## 📂 Project Structure

```
Jarvis Voice Assistant
│
├── Jarvis.py
│   ├── Main Voice Assistant
│   ├── Speech Recognition
│   ├── System Commands
│   └── Music Controls
│
├── Jarvis+newengine.py
│   ├── Enhanced Voice Engine
│   ├── Wikipedia Search
│   ├── WolframAlpha Integration
│   ├── Email Sending
│   └── Web Automation
│
├── jarvis2.py
│   ├── Alternative Jarvis Version
│   ├── Voice Commands
│   ├── Email Functionality
│   └── Music Playback
│
├── speekmodule.py
│   ├── Speech Output Module
│   ├── gTTS Integration
│   └── Internet Connectivity Check
│
├── jarvis7.mp3
│   └── Voice Audio Resource
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/jarvis-voice-assistant.git
cd jarvis-voice-assistant
```

---

### 2. Install Required Packages

```bash
pip install pyttsx3
pip install SpeechRecognition
pip install pyaudio
pip install wikipedia
pip install wolframalpha
pip install pygame
pip install gtts
```

Or install all together:

```bash
pip install pyttsx3 SpeechRecognition pyaudio wikipedia wolframalpha pygame gtts
```

---

## ▶️ Running the Project

### Basic Jarvis

```bash
python Jarvis.py
```

### Enhanced Jarvis

```bash
python "Jarvis+newengine.py"
```

### Alternative Version

```bash
python jarvis2.py
```

---

## 🎙 Supported Commands

### General Commands

```
Hello
Hi
Jarvis
How are you
Thank You
Goodbye
```

### Web Commands

```
Open Google
Open YouTube
Open Gmail
Google Maps New York
```

### Information Commands

```
Wikipedia Elon Musk
What is Artificial Intelligence
```

### Utility Commands

```
What time is it
Play Music
Start Chrome
Stop Chrome
```

### System Commands

```
Sleep Mode
Install numpy
Install pandas
```

---

## 📧 Email Configuration

Before using email features:

1. Enable App Passwords in Gmail.
2. Update your email credentials in:

```python
server.login("your_email@gmail.com", "your_password")
```

3. Replace recipient email address accordingly.

---

## 🔑 API Configuration

### WolframAlpha

Get your App ID from:

https://developer.wolframalpha.com/

Replace:

```python
client = wolframalpha.Client('YOUR_APP_ID')
```

---

## 🚀 Future Enhancements

- OpenAI ChatGPT Integration
- Weather Forecast
- Face Recognition Login
- WhatsApp Messaging
- Voice Authentication
- GUI Dashboard
- Smart Home Control
- News Updates
- AI Chat Mode
- Task Scheduling

---

## 🎓 Academic Information

**Project Title:** Jarvis - AI Voice Assistant

**Domain:** Artificial Intelligence

**Technology Stack:** Python

**Type:** Desktop Voice Assistant

**Category:** AI & Automation

---

## 👨‍💻 Developed By

**Aditya Prakash Purohit**

B.Tech Student

Python Developer | AI Enthusiast

---

## 📜 License

This project is intended for educational and learning purposes.

Feel free to modify, improve, and extend the project.
