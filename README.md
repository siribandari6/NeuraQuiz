# 🧠 NeuraQuiz – A GenAI-Powered Quiz Engine

NeuraQuiz is a multimodal AI assistant designed to simplify assessment and personalized learning. Leveraging the power of Google Gemini 1.5 Pro and OpenAI's Whisper, NeuraQuiz can **automatically generate, evaluate, and explain quizzes** from PDFs, images, and lecture videos — all through a user-friendly Streamlit interface.

---

## 🚀 Features

- 📄 **PDF to Quiz** – Extracts text from documents and generates MCQs with AI-powered explanations.
- 🖼️ **Image to Quiz** – Analyzes educational diagrams or screenshots to create insightful questions.
- 🎥 **Video to Summary** – Transcribes and summarizes lecture content for fast review.
- 🧪 **Answer Evaluation** – Grades student answers, provides feedback, and scores them automatically.
- 🎯 **Learning Path Generator** – Recommends a personalized 2-week study plan based on learning goals.

---

## 💡 GenAI Capabilities Used

| Capability             | Model/Tool        |
|------------------------|-------------------|
| Text + Image Reasoning | Gemini 1.5 Pro    |
| Video Transcription    | OpenAI Whisper    |
| Web UI                 | Streamlit         |
| PDF Parsing            | PyPDF2            |
| Image Handling         | Pillow (PIL)      |
| Secure Secrets         | Kaggle Secrets    |
| Hosting (Notebook)     | Pyngrok           |

---

## 📦 Installation

```bash
git clone https://github.com/smit-6690/NeuraQuiz.git
cd neuraquiz
pip install -r requirements.txt


