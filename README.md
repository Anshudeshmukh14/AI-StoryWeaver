# 🎨 AI StoryWeaver ( [🌐 Live Demo]() )
 - Multilingual Image-to-Story & Voice Narrator (Powered by Google Gemini 2.5)

![example](https://github.com/SannidhyaDas/AI-StoryWeaver/blob/main/assets/appInterface_1.png)

![example](https://github.com/SannidhyaDas/AI-StoryWeaver/blob/main/assets/appInterface_2.png)

> **Transform your images into emotionally expressive, multilingual narrated stories using Google Gemini 2.5 Voice AI.**

---

## 🌟 Overview

**AI StoryWeaver** is an interactive web app that converts a series of uploaded images into a **cohesive, culturally rich story**, then narrates it in a **selected voice, emotion, and language** — powered by **Google Gemini 2.5 multimodal and TTS APIs**.

This project blends **visual storytelling**, **emotion-driven narration**, and **multilingual capabilities**, showcasing the potential of **Generative AI for creative applications** such as:
- Digital storytelling
- Interactive learning content
- AI narrators for regional languages
- Creative writing assistance

---

## 🚀 Key Features

✅ **Multimodal Story Generation** – Generates complete, connected stories based on multiple uploaded images.  
✅ **Emotion-Aware Narration** – Speaks with emotional tones like *cheerful, excited, sad, serious, or angry*.  
✅ **Multilingual Support** – Supports English, Hindi, Bengali, Tamil, and Telugu.  
✅ **Voice Selection** – Choose from multiple Gemini 2.5 narrator voices (Zephyr, Kore, Puck, etc.).  
✅ **Cultural Context Awareness** – Generates stories with Indian names, places, and moral or twist endings depending on the style.  
✅ **Streamlit UI** – Simple, elegant web interface for uploading images and controlling story parameters.  

---

## 🧠 How It Works

1. **Upload Images** – Provide 1–10 images as visual inspiration.
2. **Select Style** – Choose from genres like *Comedy, Thriller, Fairy Tale, Sci-Fi, Mystery, Adventure,* or *Morale*.
3. **Set Language & Emotion** – Select storytelling language and narration tone.
4. **Gemini 2.5 Magic ✨** –  
   - `gemini-2.5-flash-lite` generates the story from the visual and textual prompt.  
   - `gemini-2.5-flash-preview-tts` narrates it in your chosen voice and emotional tone.
5. **Listen & Enjoy** – The app plays your narrated story instantly.

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Generative AI** | Google Gemini 2.5 (Flash Lite + TTS) |
| **Frontend** | Streamlit |
| **Languages** | Python |
| **Environment** | `.env` (for storing API key) |
| **Libraries** | `google-genai`, `PIL`, `streamlit`, `dotenv`, `wave`, `base64`, `io` |

---

## 🏗️ Project Structure

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/SannidhyaDas/AI-StoryWeaver.git
cd AI-StoryWeaver
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Environment

Create a .env file in the root folder and add your Google API key:
```ini
GOOGLE_API_KEY=your_google_api_key_here
```

### 4️⃣ Run the App
```bash
streamlit run app.py
```

## 🌍 Supported Languages & Voices

| Language             | Gemini Voice Options       |
| -------------------- | -------------------------- |
| English (US)         | Zephyr, Puck, Charon, Kore |
| Hindi (India)        | Kore, Puck                 |
| Bengali (Bangladesh) | Zephyr, Puck               |
| Tamil (India)        | Kore, Puck                 |
| Telugu (India)       | Kore, Puck                 |

## 🎭 Supported Emotions

- neutral
- cheerful
- excited
- sad
- angry
- serious

