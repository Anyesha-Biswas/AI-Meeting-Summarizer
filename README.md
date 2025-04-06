# 🧠 AI-Powered Meeting Summarizer

An intelligent tool that converts meeting audio or video into clean, actionable summaries. It transcribes content, extracts key points, highlights to-do items, and provides sentiment analysis — all powered by state-of-the-art AI models.

---

## 📌 Project Overview

Meetings are essential for collaboration, but keeping track of discussions, decisions, and action items can be overwhelming. This project solves that by automating the entire process:

- Transcribes recorded or uploaded meeting audio/video
- Summarizes discussions into concise key points
- Extracts action items and decisions
- Analyzes the emotional tone of the meeting

---

## 🚀 Features

- Upload or record audio/video meetings
- Speech-to-text transcription using **OpenAI Whisper**
- Summary generation using **GPT / Transformer models**
- To-do item extraction
- Sentiment analysis using **VADER / Transformers**
- Clean, user-friendly interface (via Streamlit or web app)

---

## 🛠️ Tech Stack

| Component          | Technology                         |
|--------------------|-------------------------------------|
| Transcription       | OpenAI Whisper                     |
| NLP & Summarization | GPT / Hugging Face Transformers    |
| Sentiment Analysis  | VADER, TextBlob, Transformers      |
| Frontend UI         | Streamlit / React (optional)       |
| Backend             | Flask / FastAPI                    |
| File Storage        | Local / Firebase / AWS S3          |
| (Optional) APIs     | Zoom API, Google Meet API          |

---

## ⚙️ How It Works

1. User uploads or records a meeting file (audio/video)
2. Audio is transcribed using OpenAI Whisper
3. Transcription is processed with NLP models
4. Extracts:
   - Key discussion points
   - Actionable to-dos
   - Sentiment trends
5. Results displayed and can be downloaded as text or PDF

---

## 📁 Folder Structure

```
📦 ai-meeting-summarizer/
├── app/                   # Streamlit or React frontend
├── backend/               # Flask or FastAPI API
├── models/                # Summarization and NLP models
├── utils/                 # Helper functions (cleaning, parsing, etc.)
├── sample_data/           # Sample meeting recordings
├── requirements.txt
├── README.md
└── main.py                # App entry point
```

---

## ✅ Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/your-username/ai-meeting-summarizer.git
cd ai-meeting-summarizer
```

2. **Create virtual environment & activate it**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the application**
```bash
streamlit run main.py
```

> Make sure to have a working Python 3.8+ environment.

---

## 🧪 Sample Use Cases

- Corporate meetings and internal team stand-ups
- Online class or lecture summaries
- Podcast and interview recaps
- Legal or healthcare meeting documentation

---

## 📈 Future Improvements

- Real-time summarization for live meetings
- Speaker identification (who said what)
- Integration with Google Meet and Zoom
- Multilingual support

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

