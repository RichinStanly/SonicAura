# 🎧 Sonic Aura: Lyrical Sentiment Engine

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit)
![NLP](https://img.shields.io/badge/NLP-TextBlob-8A2BE2?style=for-the-badge)
![API](https://img.shields.io/badge/Genius-API-FFFF00?style=for-the-badge&logo=genius&logoColor=black)

> **"Translating the art of music into the mathematics of emotion."**

**Sonic Aura** is a real-time Natural Language Processing (NLP) dashboard that analyzes an artist's discography to visualize their emotional footprint. It extracts raw lyric data, processes the lexical sentiment, and renders the results inside a custom, animated **Glassmorphism** interface.

---

## 📸 Interface Preview

<img width="1920" height="1080" alt="Screenshot (161)" src="https://github.com/user-attachments/assets/4c68b7f1-0223-47e3-8daa-c37409a389aa" />
<img width="1920" height="1080" alt="Screenshot (159)" src="https://github.com/user-attachments/assets/ff7d1acc-53f4-45d5-9738-26ec3764a212" />
<img width="1920" height="1080" alt="Screenshot (160)" src="https://github.com/user-attachments/assets/69b62a19-f4a3-43a7-b8d6-d17ad369ca56" />


---

## ⚡ Core Features

* **🧠 NLP Sentiment Analysis:** Utilizes `TextBlob` to calculate the emotional polarity of unstructured lyric data, grading artists on a scale from Melancholy (-1.0) to Euphoric (1.0).
* **🎨 Lexical DNA Mapping:** Generates dynamic, transparent-background WordClouds using `matplotlib` to visualize an artist's most frequently used vocabulary.
* **✨ Glassmorphism UI:** A custom-engineered frontend featuring animated liquid gradient backgrounds, frosted glass cards, and responsive hover states—mimicking high-end modern music applications.
* **📡 Live Data Extraction:** Connects directly to the **Genius API** via `lyricsgenius` to scrape, clean, and process multi-song datasets in seconds.

---

## 🛠️ Installation & Setup Guide

### 1. Clone the Repository
bash
git clone [https://github.com/RichinStanly/SonicAura.git](https://github.com/RichinStanly/SonicAura.git)
cd SonicAura

2. Install Dependencies
This project requires specific Data Science and NLP libraries. Install them via: pip install -r requirements.txt

3. Get Your Free API Key
To fetch live lyrics, you need a free Genius API Token:

Go to the Genius API Client Page.

Create a "New API Client" (Use http://127.0.0.1 as your App Website URL and Redirect URI).

Click Generate Access Token and copy the key.

Open app.py, find GENIUS_TOKEN = "..." (around line 18), and paste your key.

4. Ignite the Engine

streamlit run app.py

🧪 The Science Behind the Vibe
Sonic Aura doesn't just count words; it measures context.
By aggregating the lyrics of an artist's top tracks, the algorithm strips away noise (like [Chorus] tags or embed tracking) and evaluates the semantic weight of the text.

The Word Matrix reveals the topics the artist obsesses over.

The Polarity Gauge reveals the tone with which they discuss those topics.


<p align="center">Designed & Engineered by <a href="https://github.com/RichinStanly">Richin Stanly</a></p>


