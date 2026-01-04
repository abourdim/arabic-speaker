
# 🗣️ Arabic Speech App (Browser-Only)

A fully client-side Arabic **Text-to-Speech (TTS)** and **Speech-to-Text (STT)** web application.
Runs entirely in the browser with **no backend**, using the Web Speech API.

---

## ✨ Features
- Arabic Text-to-Speech
- Arabic Speech-to-Text
- Multiple Arabic dialects (ar-SA, ar-EG, ar-AE, ar-MA, etc.)
- Voice selection (system voices)
- Adjustable rate, pitch, and volume
- Works offline (except STT which needs browser permission)
- No frameworks, no dependencies

---

## 🚀 How to Run

### Option 1: Open directly
Just double-click `index.html` in a modern browser (Chrome / Edge recommended).

### Option 2: Local server (recommended for microphone)
```bash
python -m http.server
```
Then open:
```
http://localhost:8000
```

---

## 🧠 Technologies Used
- HTML5
- CSS3
- Vanilla JavaScript
- Web Speech API
  - `speechSynthesis`
  - `SpeechRecognition`

---

## 🌍 Supported Dialects
- Saudi Arabia (ar-SA)
- Egypt (ar-EG)
- UAE (ar-AE)
- Jordan (ar-JO)
- Lebanon (ar-LB)
- Morocco (ar-MA)
- Algeria (ar-DZ)
- Tunisia (ar-TN)
- Iraq (ar-IQ)
- Kuwait (ar-KW)

---

## 🔐 Privacy
- No data leaves your device
- No servers
- No tracking
- Microphone access only when you click "Listen"

---

## 📁 Project Structure
```
arabic-speech-app/
├── index.html
└── README.md
```

---

## ⚠️ Notes
- Speech recognition works best on Chrome or Edge
- HTTPS or localhost is required for microphone access
- Available Arabic voices depend on OS and browser

---

## 📜 License
Free for educational and personal use.
