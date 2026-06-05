<div align="center">

# Yehonatan Barel

**Software developer who builds things that talk back.**

</div>

---

## About Me

I'm a software developer who enjoys working at the intersection of AI, audio, and real-world usability.  
My work spans local AI pipelines, Python backends, and React frontends.  
I care about software that runs entirely on your machine — no accounts, no cloud, no data sent anywhere.

---

## ⭐ Featured Project — BRYCE AI Assistant

> *A fully local, privacy-first voice AI assistant.  
> No cloud. No data sent anywhere. Just you and an AI that speaks back.*

<!-- Replace this comment with a screenshot or GIF of the app once it's uploaded to your profile repo -->

### How It Works

```
🎙️  You speak
      ↓
[ Whisper STT ]   — speech-to-text, runs on CPU, int8 quantized for speed
      ↓
[ Ollama LLM  ]   — local inference, llama3.2:1b, tokens streamed in real time
      ↓
[ Piper TTS   ]   — text-to-speech, custom voice, raw PCM audio output
      ↓
🔊  Bryce speaks back
```

### Features

- **100% offline** — Whisper + Ollama + Piper, nothing leaves your machine after setup
- **Push-to-talk** — hold spacebar to record, release to process; no button clicking
- **Real-time audio meter** — visual feedback while your mic is live
- **Streamed responses** — LLM tokens are buffered into speech as they arrive, no waiting for the full reply
- **Interruptible at any moment** — STOP button halts both inference and audio playback instantly
- **Conversation memory** — maintains the last 10 turns of context across the session
- **English tutor persona** — gives gentle grammar feedback and keeps the conversation moving

### Stack

| Component | Technology |
|---|---|
| GUI | Python · CustomTkinter |
| Speech-to-Text | faster-whisper · Whisper base.en · int8 quantization |
| Language Model | Ollama · llama3.2:1b |
| Text-to-Speech | Piper TTS · en_US-bryce-medium voice |
| Audio I/O | sounddevice · 16 kHz recording · 22 kHz playback |

🔗 **[github.com/yehonatanbarel/speak-english-ai](https://github.com/yehonatanbarel/speak-english-ai)**

---

## Other Projects

| Project | Description | Tech |
|---|---|---|
| 🎮 Pokemon | Animated game with resizable window and sprite sheets | Java |
| 💪 Murph Counter | Workout rep counter with animated tracking | React |
| 🛒 Customer Classifier | Segments mall shoppers into loyalty groups using KNN & Logistic Regression | Python · Scikit-learn · Pandas |
| ✅ To-Do App | Minimal task manager with add, complete, and delete flow | React |

---

## Tech Stack

| Category | Technologies |
|---|---|
| Languages | 🐍 Python · ☕ Java · ⚡ JavaScript · 🔵 C · 🌐 HTML · 🎨 CSS |
| AI / Data | 🎙️ Whisper · 🦙 Ollama · 🔢 NumPy · 🐼 Pandas · 🤖 Scikit-learn |
| Frameworks | ⚛️ React · 🌶️ Flask · 🅱️ Bootstrap · 🖥️ CustomTkinter |
| Tools | 🔧 Git · 🐧 Linux |
