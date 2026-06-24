<div align="center">

<img src="https://img.shields.io/badge/J.A.R.V.I.S-Autonomous%20AI%20Desktop%20Assistant-00D4FF?style=for-the-badge&logo=robot&logoColor=white" />

# 🤖 J.A.R.V.I.S
### *Just A Rather Very Intelligent System*

**Autonomous AI Desktop Assistant with Real-Time Voice Control**

<br/>

[![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Claude AI](https://img.shields.io/badge/Claude-AI%20Engine-D4A017?style=flat-square&logo=anthropic&logoColor=white)](https://anthropic.com)
[![PyAutoGUI](https://img.shields.io/badge/PyAutoGUI-OS%20Automation-FF6B35?style=flat-square)](https://pyautogui.readthedocs.io)
[![SpeechRecognition](https://img.shields.io/badge/SpeechRecognition-Voice%20Input-4CAF50?style=flat-square)](https://pypi.org/project/SpeechRecognition/)
[![pyttsx3](https://img.shields.io/badge/pyttsx3-TTS%20Engine-9C27B0?style=flat-square)](https://pypi.org/project/pyttsx3/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square&logo=windows&logoColor=white)](https://microsoft.com/windows)

<br/>

> **A fully autonomous, voice-driven AI desktop assistant** that understands natural language, reasons through multi-step tasks using Claude LLM, and executes deep OS-level automation — from opening apps and searching the web to controlling media, managing files, and monitoring system performance — all hands-free.

<br/>

[🚀 Quick Start](#️-installation--setup) · [🧠 Architecture](#-system-architecture) · [📸 Screenshots](#-live-system-demonstration) · [⚙️ Capabilities](#-core-capabilities) · [🤖 AI Engine](#-ai-decision-engine--model-analysis)

</div>

---

## 🏆 Hackathon Recognition

<div align="center">

[![Hackathon](https://img.shields.io/badge/OSC%20AI%20Build%201.0-Shortlisted-00D4FF?style=for-the-badge&logo=trophy&logoColor=white)](https://hackculture.io)
[![Idea Submission](https://img.shields.io/badge/Idea%20Submission-Cleared-4CAF50?style=for-the-badge)](https://hackculture.io)
[![Build Phase](https://img.shields.io/badge/Build%20Phase-Cleared-4CAF50?style=for-the-badge)](https://hackculture.io)

</div>

**J.A.R.V.I.S** wasn't just built in isolation — it was forged and battle-tested at **OSC AI Build 1.0**, a national-level, elimination-format hackathon hosted by **Open Source Connect** on the **HackCulture** platform. While most submissions get filtered out at the very first checkpoint, JARVIS didn't just survive — it dominated **every elimination round**, standing tall among the shortlisted few.

RoundResultSubmitted🧠 Idea Submission (Elimination)✅ ShortlistedMay 20, 2026⚙️ Build Phase (Elimination)✅ ShortlistedJun 12, 2026


Competing in the AI/ML Track under the Problem Statement "AI for Builders", JARVIS was independently evaluated and selected as a standout submission across both elimination checkpoints — a direct validation of its architecture, ambition, and real-world execution under competitive scrutiny.



📁 Complete hackathon documentation, submission proofs, and supporting material: Google Drive Link https://drive.google.com/drive/folders/1fAXfUpbQa25qnr4UUQf6Zw6SoCMLfUiT?usp=drive_link

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Highlights](#-key-highlights)
- [Live System Demonstration](#-live-system-demonstration)
- [System Architecture](#-system-architecture)
- [AI Decision Engine & Model Analysis](#-ai-decision-engine--model-analysis)
- [Core Capabilities](#-core-capabilities)
- [Advanced Features](#-advanced-features)
- [Performance Metrics](#-performance-metrics)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Installation & Setup](#️-installation--setup)
- [Example Commands](#-example-commands)
- [Roadmap](#-roadmap)
- [Author](#-author)
- [License](#-license)

---

## 🌐 Overview

**JARVIS** is a production-grade, modular AI assistant built to bridge the gap between *conversational AI* and *real OS-level system control*. Unlike traditional voice assistants limited to web queries or smart home commands, JARVIS operates at the system level — executing actions across applications, the file system, the browser, mouse and keyboard, media, and system power controls.

At its core, JARVIS uses **Claude LLM** as its reasoning engine — not a rigid rule-based parser. This means it understands *intent*, plans *multi-step execution*, and dynamically maps commands to actions even when phrasing varies.

### The Problem It Solves

```
Traditional Computing:   Manual input → fragmented workflows → context switching
JARVIS:                  Voice → AI reasoning → full system execution → response
```

Modern computing still demands constant manual interaction. JARVIS demonstrates what a true **LLM-powered autonomous desktop agent** looks like in practice.

---

## ⚡ Key Highlights

```
┌─────────────────────────────────────────────────────────────────────┐
│  🧠  Claude LLM Engine     Intent detection + multi-step planning   │
│  🎙️  Wake Word System      "Hey Jarvis" — always listening          │
│  💻  Full OS Automation    Apps · Files · Web · Mouse · Keyboard    │
│  ⚔️  Weapon Mode           Dev environment spun up in one command   │
│  🎬  Favorites Mode        Instant entertainment launch             │
│  🎨  Iron Man GUI          Real-time state visualization            │
│  ⚡  ~1s Response          Event-driven, multi-threaded execution   │
│  🔍  Auto App Discovery    Registry + fuzzy match — no hardcoding   │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 📸 Live System Demonstration

### 🎤 Listening Mode — Wake Word Detected

> System actively listening after detecting *"Hey Jarvis"* — ready for voice command input.

![Listening Mode](https://github.com/user-attachments/assets/51c80245-0ac8-4da9-8a17-906b3cdc8ade)

---

### 🟢 Responding Mode — Command Executed

> Command successfully executed. GUI and voice output synchronized. Example: *"Open Documents"*

![Responding Mode](https://github.com/user-attachments/assets/fb57df8b-6050-4762-a930-03c729c6ad76)

---

### 🟠 Processing Mode — AI Reasoning Active

> Claude LLM analyzing the command, planning multi-step execution, and dispatching to the Device Controller Layer.

![Processing Mode](https://github.com/user-attachments/assets/4c152621-882d-46aa-a79a-cbc89bea0325)

---

### 🌐 Real Browser Automation

> Live demonstration of web automation — JARVIS identifies and interacts with specific on-screen elements. Example: *"Play the second video"*

![Browser Automation](https://github.com/user-attachments/assets/77f416ed-de92-452f-aa94-07f322b2bbce)

---

### ⚡ Execution Pipeline

```
"Hey Jarvis"  →  Wake Word  →  Listening  →  Processing  →  Execution  →  Voice Response
     │               │              │               │              │              │
  Always On      Detected       STT + Clean     Claude LLM    OS Action     TTS + GUI
```

---

## 🏗 System Architecture

```
                    ┌──────────────────────────────┐
                    │         User (Voice)          │
                    └─────────────┬────────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────────┐
                    │     Wake Word Detection       │
                    │       "Hey Jarvis"            │
                    │       detector.py             │
                    └─────────────┬────────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────────┐
                    │      Speech Recognition       │
                    │       Voice → Text            │
                    │       listener.py             │
                    └─────────────┬────────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────────┐
                    │    Command Preprocessing      │
                    │    · Wake word removal        │
                    │    · Noise filtering          │
                    │    · Duplicate removal        │
                    └─────────────┬────────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────────┐
                    │     AI Decision Engine        │
                    │     Claude LLM  (core.py)     │
                    │                               │
                    │    · Intent detection         │
                    │    · Multi-step planning      │
                    │    · Dynamic action mapping   │
                    │    · Context-aware reasoning  │
                    └─────────────┬────────────────┘
                                  │
         ┌───────────────────────┼───────────────────────┐
         ▼                       ▼                       ▼
┌────────────────┐   ┌───────────────────┐   ┌──────────────────┐
│  App Control   │   │   File System     │   │  Web Automation  │
│  system.py     │   │   system.py       │   │  web.py          │
│                │   │                   │   │                  │
│ Open any app   │   │ Create / Delete   │   │ Google / YouTube │
│ Close apps     │   │ List files        │   │ WhatsApp Web     │
│ Close all      │   │ Open / Navigate   │   │ Social media     │
│ Auto-discover  │   │                   │   │ Any URL          │
└────────────────┘   └───────────────────┘   └──────────────────┘

┌────────────────┐   ┌───────────────────┐   ┌──────────────────┐
│ Keyboard Ctrl  │   │   Mouse Control   │   │  Media Control   │
│ keyboard.py    │   │   system.py       │   │  system.py       │
│                │   │                   │   │                  │
│ Type text      │   │ Move cursor       │   │ Play / Pause     │
│ Hotkeys        │   │ Click / Scroll    │   │ Skip / Rewind    │
│ Copy / Paste   │   │ Natural positions │   │ Volume / Mute    │
└────────────────┘   └───────────────────┘   └──────────────────┘

┌────────────────┐   ┌───────────────────┐
│ System Control │   │    Monitoring     │
│                │   │                   │
│ Shutdown       │   │ CPU / RAM         │
│ Restart / Lock │   │ Disk / Battery    │
│ Screenshot     │   │ Process list      │
│ Terminal cmds  │   │ System health     │
└────────────────┘   └───────────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────────┐
                    │    Text-to-Speech Engine      │
                    │        speaker.py             │
                    └─────────────┬────────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────────┐
                    │      GUI Visualization        │
                    │      main_window.py           │
                    │  🔵 Listening  🟠 Processing  │
                    │  🟢 Responding                │
                    └──────────────────────────────┘
```

---

## 🤖 AI Decision Engine — Model Analysis

JARVIS uses **Claude (Anthropic)** as its core reasoning engine. Unlike voice assistants built on keyword matching or decision trees, JARVIS delegates *intent interpretation* and *action planning* entirely to an LLM — enabling natural, flexible, multi-step command understanding.

### Why LLM-Based Reasoning Over Rule-Based Parsing

| Approach | Rule-Based Parser | LLM-Based (JARVIS) |
|---|---|---|
| Command flexibility | Fixed keywords only | ✅ Natural language variations |
| Multi-step tasks | Requires explicit chaining | ✅ Auto-planned by LLM |
| Ambiguity handling | Fails or defaults | ✅ Context-aware resolution |
| New command support | Requires code changes | ✅ Zero-shot generalization |
| Error recovery | Hard failure | ✅ Graceful re-interpretation |
| Maintenance cost | High (brittle) | ✅ Low (self-adapting) |

### Claude vs. Alternative LLM Backends

| Model | Reasoning | Latency | Context Window | Tool Use | Best For |
|---|---|---|---|---|---|
| **Claude (Anthropic)** ✅ | ⭐⭐⭐⭐⭐ | ~1s | 200K tokens | ✅ Native | Complex multi-step OS tasks |
| GPT-4o (OpenAI) | ⭐⭐⭐⭐⭐ | ~1.2s | 128K tokens | ✅ Native | General-purpose assistant |
| GPT-3.5 Turbo | ⭐⭐⭐ | ~0.5s | 16K tokens | ✅ Limited | Simple, fast commands |
| Gemini 1.5 Pro | ⭐⭐⭐⭐ | ~1.1s | 1M tokens | ✅ Native | Long-context workflows |
| LLaMA 3 (Local) | ⭐⭐⭐ | ~2–5s | 8K tokens | ❌ Manual | Privacy-first, offline use |
| Mistral 7B (Local) | ⭐⭐⭐ | ~3–6s | 8K tokens | ❌ Manual | Low-resource deployment |

> **Why Claude was chosen:** Claude excels at instruction-following with structured output, handles ambiguous multi-step commands reliably, and produces clean action-mappable responses — critical for OS-level automation where incorrect actions have immediate real-world consequences.

### Speech Recognition — Engine Comparison

| Engine | Accuracy | Latency | Offline | Cost | Used In JARVIS |
|---|---|---|---|---|---|
| **Google STT (SpeechRecognition)** ✅ | ⭐⭐⭐⭐⭐ | ~300ms | ❌ | Free tier | ✅ Primary |
| Whisper (OpenAI) | ⭐⭐⭐⭐⭐ | ~500ms–1s | ✅ | Free (local) | Alternative |
| Azure Speech | ⭐⭐⭐⭐ | ~350ms | ❌ | Paid | Enterprise alt |
| Vosk | ⭐⭐⭐ | ~200ms | ✅ | Free | Offline alt |
| DeepSpeech | ⭐⭐⭐ | ~600ms | ✅ | Free | Research use |

### TTS Engine Comparison

| Engine | Voice Quality | Latency | Offline | Used In JARVIS |
|---|---|---|---|---|
| **pyttsx3** ✅ | ⭐⭐⭐ | ~50ms | ✅ | ✅ Primary |
| gTTS (Google) | ⭐⭐⭐⭐ | ~300ms | ❌ | Alternative |
| ElevenLabs | ⭐⭐⭐⭐⭐ | ~500ms | ❌ | Premium alt |
| Coqui TTS | ⭐⭐⭐⭐ | ~200ms | ✅ | Open-source alt |

> **pyttsx3 chosen** for zero-latency offline voice output — critical for real-time response feel. The assistant sounds instant even when LLM reasoning takes ~1s.

---

## 🔧 Core Capabilities

### 🎙 Voice Interaction System
- Wake word: **"Hey Jarvis"** — always-on detection
- Continuous listening with real-time speech-to-text
- Noise filtering and duplicate speech deduplication
- Graceful handling of partial or unclear commands

### 🖥 Application & Process Control
- Open **any installed application** — no hardcoding required
- Auto-discovery via Windows Registry + Start Menu + Desktop scan
- Fuzzy name matching (*"open chrome"* → finds `Google Chrome.exe`)
- Close specific apps, tabs, or issue **"close everything"** to clear the full workspace

### 🌐 Web Automation
- Google and YouTube search by voice
- Open any URL by name or spoken address
- WhatsApp Web — messages and calls via smart contact matching
- Social platform navigation

### ⌨️ Keyboard & Mouse Automation
- Type text into any focused application
- Execute keyboard shortcuts: Copy · Paste · New Tab · Refresh · Select All
- Move mouse to natural language positions (*"top right"*, *"center"*)
- Click, double-click, scroll on demand

### 🎥 Intelligent Media Control
- Play / Pause / Skip / Rewind
- Volume up, down, mute
- Fullscreen toggle
- **Target-specific playback:** *"Play the second video"* — AI identifies position and clicks

### 📁 File System Operations
- Create and delete files and folders
- Open files and navigate directories
- List directory contents by voice

### 📊 System Monitoring
- Live CPU, RAM, Disk, and Battery status
- Active process listing
- Report system health on demand

### 🖥 System-Level Control
- Shutdown · Restart · Sleep · Lock
- Run terminal commands by voice
- Screenshot capture with auto-save

### 📞 Contact Integration
- Call via WhatsApp by name (*"Call Mom"*)
- Send messages with smart contact matching

---

## ⚔️ Advanced Features

### ⚔️ Weapon Mode
> *"Hey Jarvis, weapon up"*

Activates the full developer environment in a single command:
- Opens **ChatGPT**, **Claude**, **GitHub**, **VS Code**
- Displays current **time**, **date**, and **weather**

### 🎬 Favorites Mode
> *"Hey Jarvis, open my favourites"*

Instant entertainment launch — **Netflix** · **Amazon Prime** · **YouTube**

### 💣 Global System Cleanup
> *"Hey Jarvis, close everything"*

Terminates all running applications and clears the full desktop workspace in one command.

### 🔍 Auto App Discovery Engine
- Dynamically scans the system on startup
- Builds and caches an app index in `apps_cache.json`
- Supports fuzzy name matching — no manual app registration ever required

---

## 📊 Performance Metrics

| Metric | Value |
|---|---|
| **End-to-End Response Time** | ~1 second |
| **Wake Word Detection Latency** | ~300 ms |
| **STT Processing Time** | ~200–400 ms |
| **LLM Reasoning Time (Claude)** | ~400–700 ms |
| **TTS Output Latency** | ~50 ms |
| **Architecture** | Event-driven, non-blocking |
| **Execution Model** | Multi-threaded |
| **App Discovery** | Dynamic (Registry + fuzzy match) |
| **Supported Commands** | Unlimited (LLM-generalized) |

---

## 📂 Project Structure

```
JARVIS/
│
├── main.py                        # 🚀 Application entry point
├── requirements.txt               # Python dependencies
├── startup.bat                    # Windows auto-launch script
├── apps_cache.json                # Cached app index (auto-generated)
├── jarvis.log                     # Runtime execution log
│
├── brain/
│   ├── core.py                    # 🧠 Claude LLM integration & reasoning
│   └── memory.py                  # Conversation context management
│
├── commands/
│   ├── keyboard.py                # ⌨️ Keyboard automation & shortcuts
│   ├── system.py                  # 💻 OS-level control (apps, files, mouse)
│   └── web.py                     # 🌐 Browser & web automation
│
├── config/
│   └── settings.py                # ⚙️ API keys, config, constants
│
├── gui/
│   ├── animations.py              # 🎨 State animations
│   └── main_window.py             # 🖼 Iron Man-style GUI window
│
├── voice/
│   ├── listener.py                # 🎤 Speech recognition & preprocessing
│   └── speaker.py                 # 🔊 Text-to-speech output engine
│
├── wake_word/
│   └── detector.py                # 👂 Always-on wake word detection
│
└── Contacts manager.py            # 📞 WhatsApp contact integration
```

---

## 🛠 Tech Stack

### Core AI & NLP

| Component | Technology | Role |
|---|---|---|
| **LLM Reasoning** | Claude (Anthropic) | Intent detection, multi-step planning |
| **Speech-to-Text** | Google STT via SpeechRecognition | Voice → text conversion |
| **Text-to-Speech** | pyttsx3 | Offline instant voice output |
| **Wake Word** | Custom detector | Always-on "Hey Jarvis" trigger |

### OS Automation

| Component | Technology | Role |
|---|---|---|
| **GUI Automation** | PyAutoGUI | Mouse, keyboard, screenshots |
| **App Discovery** | winreg + os.walk | Registry + filesystem scanning |
| **Process Control** | psutil | Kill, monitor system processes |
| **System Info** | psutil | CPU, RAM, disk, battery |

### Interface & Visualization

| Component | Technology | Role |
|---|---|---|
| **GUI Framework** | Tkinter | Iron Man-style status window |
| **Animations** | Custom (animations.py) | State-based visual transitions |
| **Logging** | Python logging | jarvis.log runtime trace |

---

## ⚙️ Installation & Setup

### Prerequisites

- Python **3.12+**
- Windows OS (Registry-based app discovery)
- Working microphone
- Internet connection (Claude API + Google STT)
- Anthropic API key

### 1. Clone the Repository

```bash
git clone https://github.com/Mvkarthikeya07/J.A.R.V.I.S-Autonomous-AI-Desktop-Assistant-with-Real-Time-Voice-Control
cd jarvis
```

### 2. Create a Virtual Environment *(recommended)*

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Open `config/settings.py` and add your Anthropic API key:

```python
ANTHROPIC_API_KEY = "your-claude-api-key-here"
```

### 5. Detect Your Microphone

```bash
python "Find mic.py"
```

Update the microphone index in `config/settings.py` if needed.

### 6. Launch JARVIS

```bash
python main.py
```

Or double-click `startup.bat` for one-click Windows launch.

---

## 🎯 Example Commands

```bash
# Activation
"Hey Jarvis"

# App Control
"Hey Jarvis, open Chrome"
"Hey Jarvis, close everything"
"Hey Jarvis, open VS Code"

# Web
"Hey Jarvis, search Python tutorials on YouTube"
"Hey Jarvis, open GitHub"

# Media
"Hey Jarvis, play the first video"
"Hey Jarvis, pause"
"Hey Jarvis, volume up"

# Typing
"Hey Jarvis, type hello world in Notepad"

# Communication
"Hey Jarvis, call mom"
"Hey Jarvis, message John: I am on my way"

# System
"Hey Jarvis, take a screenshot"
"Hey Jarvis, what is my CPU usage"
"Hey Jarvis, lock the computer"

# Special Modes
"Hey Jarvis, weapon up"
"Hey Jarvis, open my favourites"
```

---

## 🔮 Roadmap

| Feature | Priority | Status |
|---|---|---|
| Persistent conversation memory | High | 🔲 Planned |
| Offline LLM support (LLaMA / Mistral) | High | 🔲 Planned |
| Task automation pipelines (chained macros) | High | 🔲 Planned |
| Mobile companion app | Medium | 🔲 Planned |
| Smart home integration (Home Assistant) | Medium | 🔲 Planned |
| Multi-monitor awareness | Medium | 🔲 Planned |
| Plugin / extension system | Low | 🔲 Planned |
| Cross-platform support (macOS / Linux) | Low | 🔲 Planned |

---

## 👨‍💻 Author

<div align="center">

**M V Karthikeya**
B.Tech CSE — Artificial Intelligence & Machine Learning

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/m-v-karthikeya-b26a2131b)

</div>

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**JARVIS is not just a voice assistant.**
**It is a fully autonomous AI agent capable of controlling an entire computer through natural language.**

*If this project helped you, consider giving it a ⭐ on GitHub.*

[![GitHub Stars](https://img.shields.io/github/stars/Mvkarthikeya07/J.A.R.V.I.S-Autonomous-AI-Desktop-Assistant-with-Real-Time-Voice-Control?style=social)](https://github.com/Mvkarthikeya07/J.A.R.V.I.S-Autonomous-AI-Desktop-Assistant-with-Real-Time-Voice-Control)

</div>
