# Kid-safe Mood2Emoji App

A minimal **Streamlit** app that analyzes short text input and returns a **kid-friendly emoji** (😀 😐 😞) with a one-line explanation. Designed for students aged **12–16** to learn about **text classification and sentiment analysis** in a safe and interactive way.

---

## 🎯 How It Works
-Input text is cleaned and normalized
-Safety check: profanity or inappropriate words trigger neutral output
-Sentiment analysis using TextBlob polarity
-Rule-based fallback for short or ambiguous sentences
-Output: emoji + kid-friendly explanation
-Teacher Mode shows processing flow diagram and example sentences

---

## 👩‍🏫 Teaching & Learning
-Demonstrates how text can map to feelings using AI
-Highlights limitations of automated sentiment detection
-Encourages students to experiment with sentences
-Teacher Mode helps explain internal logic visually

---

## 💡 What the Project Does and How Kids Learn

-Students type a short sentence into the app.
-The app detects the mood (happy, neutral, or sad) using TextBlob polarity and a simple rule-based fallback.
-Returns a kid-friendly emoji (😀 😐 😞) with a one-line explanation.
-Teacher Mode displays a flowchart of the app logic and example sentences for discussion.
-Kids learn:
  -How AI can classify text by sentiment
  -Safe ways to handle text input
  -How algorithms make decisions using simple rules and polarity scores
  -Basic debugging and critical thinking about AI outputs

---

## 🧑‍🏫 How to Teach It in 60 Minutes

| Time      | Activity                                                                            |
| --------- | ----------------------------------------------------------------------------------- |
| 0–5 min   | **Introduction**: Discuss emotions and text, why mood detection matters             |
| 5–15 min  | **Demo**: Launch the app, show input → emoji + explanation                          |
| 15–25 min | **Hands-on Practice**: Students type sentences, observe outputs                     |
| 25–35 min | **Teacher Mode**: Explain workflow diagram (Input → Safety → Sentiment → Emoji)     |
| 35–45 min | **Discussion**: Talk about tricky cases, misclassifications, and AI limitations     |
| 45–55 min | **Activity**: Predict emoji before submission; compare with app output              |
| 55–60 min | **Wrap-up**: Summarize key concepts, answer questions, reflect on learning outcomes |

---

## ⚠️ Known Limitations
-Lightweight educational tool — not for clinical or emotional assessment
-Profanity filter is simple — may miss variations
-TextBlob may misinterpret sarcasm, slang, or very short phrases
-Only English is supported

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
