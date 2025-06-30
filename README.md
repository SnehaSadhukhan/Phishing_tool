# 🎣 Phishing Detection Tool (Flask + Gemini AI)

An intelligent web-based phishing detection tool that uses **Google's Gemini AI** to analyze both text-based files (like emails) and URLs. Built with Flask, this tool can predict whether content is **real or a scam**, and classify suspicious URLs into categories such as **phishing**, **malware**, **defacement**, or **benign**.

---

## 🚀 Features

- 📄 Upload `.pdf` or `.txt` files for scam detection
- 🌐 Enter a URL to detect its nature (phishing, malware, etc.)
- 🤖 Powered by **Google Gemini AI** for contextual analysis
- 📊 Real-time classification with user-friendly web interface
- 🧠 AI-based reasoning for scam/fraud content detection
- Flask-based web server with HTML interface (via `index.html`)

---

## 🧱 Tech Stack

- Python 3.x
- Flask
- PyPDF2
- Google Generative AI (`google.generativeai`)
- HTML/CSS (basic UI)
- Gemini 1.5 Flash model (via Gemini API)

---

## 📦 Installation

1. Clone this repository:

```bash
git clone https://github.com/YourUsername/PhishingDetectionTool.git
cd PhishingDetectionTool
```

## Set your Google Gemini API Key:

```bash
export GOOGLE_API_KEY="your_api_key_here"
```


## On Windows PowerShell:
```powershell
$env:GOOGLE_API_KEY="your_api_key_here"
```

## ▶️ Usage
 
1.Run the Flask app:
```
bash
python app.py
```
2.Open your browser and visit:

http://127.0.0.1:5000/

3.Choose from:
   Uploading a .pdf or .txt file to detect scam content
   Typing a URL to classify it (phishing, malware, etc.)

