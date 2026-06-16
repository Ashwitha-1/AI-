# 🤖 J.A.R.V.I.S — AI Desktop Assistant

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Gemini-AI-orange?style=for-the-badge&logo=google">
  <img src="https://img.shields.io/badge/Platform-Windows-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge">
</p>

---

## 🚀 Overview

J.A.R.V.I.S (Just A Rather Very Intelligent System) is a futuristic AI-powered desktop assistant inspired by Iron Man's JARVIS.

The system combines voice interaction, Gemini AI, automation tools, file processing, memory management, and a custom HUD interface to create an intelligent desktop companion capable of assisting users with everyday tasks.

---

## ✨ Features

### 🎙️ Voice Assistant
- Real-time voice interaction
- Speech recognition
- Voice command execution
- AI-generated voice responses

### 🧠 Gemini AI Integration
- Natural language conversations
- Intelligent responses
- Context-aware interactions
- AI-powered task execution

### 📂 File Processing
- Upload and analyze files
- PDF processing
- Document handling
- File management tools

### 💻 System Monitoring
- CPU usage tracking
- Memory monitoring
- Network statistics
- System uptime display

### 🔧 Automation Tools
- Open applications
- Execute desktop commands
- System controls
- Productivity automation

### 🗂 Memory Management
- Conversation history
- Context retention
- Session management
- Smart memory storage

---

## 🏗️ System Architecture

```text
User Voice
    ↓
Speech Recognition
    ↓
Gemini AI Engine
    ↓
Command Processing
    ↓
Tool Execution Layer
    ↓
System Automation
    ↓
Response Generation
    ↓
Voice Output + HUD Display
```

---

## 🛠️ Technologies Used

### Core Technologies

- Python 3.13
- Google Gemini AI
- AsyncIO
- Playwright
- Speech Recognition
- Text-to-Speech

### Libraries

- tkinter
- asyncio
- pygame
- psutil
- requests
- google-generativeai
- sounddevice
- numpy

---

## 📁 Project Structure

```text
jarvis-ai/
│
├── actions/
│   ├── web_search.py
│   ├── desktop.py
│   ├── file_processor.py
│   └── automation.py
│
├── agent/
│   ├── executor.py
│   └── error_handler.py
│
├── config/
│   └── api_keys.json
│
├── core/
│   ├── ai_core.py
│   ├── speech.py
│   └── memory.py
│
├── memory/
│
├── main.py
├── ui.py
├── setup.py
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Ashwitha-1/AI-.git
```

### Navigate to Project

```bash
cd AI-
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Gemini API

Create:

```json
{
  "gemini_api_key": "YOUR_API_KEY",
  "os_system": "windows"
}
```

inside:

```text
config/api_keys.json
```

### Run Application

```bash
python main.py
```

---

## 🎯 Capabilities

- AI Chat Assistant
- Voice Commands
- System Monitoring
- File Analysis
- Automation Tasks
- Desktop Control
- AI Conversations
- Productivity Assistance

---

## 🔒 Security

- Local configuration storage
- Secure API handling
- Controlled command execution
- User-managed credentials

---

## 📸 Screenshots

### JARVIS Dashboard

Add your screenshot here:

```md
![JARVIS Dashboard](screenshot/dashboard.png)
```

---

## 📈 Future Enhancements

- Wake-word detection
- Multi-language support
- Smart home integration
- Mobile companion app
- Cloud synchronization
- Advanced AI memory

---

## 👩‍💻 Author

**Ashwitha**

GitHub: https://github.com/Ashwitha-1

---

## 📄 License

This project is intended for educational and learning purposes.

---

<p align="center">
⭐ If you like this project, consider starring the repository.
</p>
