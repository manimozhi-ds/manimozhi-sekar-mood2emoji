# manimozhi-sekar-mood2emoji
This repository contains a Kid-safe Mood2Emoji app, a simple Streamlit web application that analyzes short text input and returns a kid-friendly emoji (😀 😐 😞) along with a one-line explanation.  The project is designed for students aged 12–16 to learn about text classification and sentiment analysis in a safe and interactive way.
# Kid-safe Mood2Emoji App

A minimal **Streamlit** app that analyzes short text input and returns a **kid-friendly emoji** (😀 😐 😞) with a one-line explanation. Designed for students aged **12–16** to learn about **text classification and sentiment analysis** in a safe and interactive way.

---

## 📝 Features
- Input box for typing a short sentence (max 280 characters)  
- Outputs:
  - Emoji representing mood (happy, neutral, sad)  
  - One-line, age-appropriate explanation  
- **Neutral fallback** for unknown, unsafe, or inappropriate text  
- **Teacher Mode**: flow diagram + example sentences for classroom discussion  
- Lightweight and safe — no heavy AI models  

---

## 🛠 Technology
- Python 3.9+  
- [Streamlit](https://streamlit.io/) — Web interface  
- [TextBlob](https://textblob.readthedocs.io/) — Lightweight sentiment analysis  
- Optional: Graphviz for diagrams in Teacher Mode  

---

## ⚡ Installation & Setup

1. **Clone the repository**  
```bash
git clone https://github.com/<your-username>/kid-safe-mood-detector.git
cd kid-safe-mood-detector
