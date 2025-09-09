📝 AI-Powered Meeting Minutes Generator
Automatically generate structured meeting minutes from raw transcripts or audio recordings using NLP + Speech-to-Text.
🚀 Features
🔊 Audio/Video to Text using Whisper (speech-to-text).
📝 Transcript Summarization with HuggingFace transformers.
✅ Action Item Extraction (who will do what, deadlines).
🏷 Decision Detection (agreed/approved points).
📄 Export results as PDF/Word/Email.
🌐 Simple Streamlit Web UI.
🛠 Tech Stack
Backend: Python, FastAPI/Flask
Frontend: Streamlit
AI Models:
OpenAI Whisper → Transcription
HuggingFace (BART/T5/Pegasus) → Summarization
SpaCy → Named Entity Recognition (NER)
Storage: MongoDB / PostgreSQL (optional)
Deployment: Docker + Render/Heroku


ai-meeting-minutes-generator/
│── backend/
│   └── main.py
│
│── frontend/
│   └── app.py
│
│── models/
│   ├── summarizer.py
│   ├── extractor.py
│
│── data/
│   └── sample_transcripts/
│
│── outputs/
│   └── generated_minutes/
│
│── requirements.txt
│── README.md

