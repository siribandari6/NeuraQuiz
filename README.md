# 🧠 NeuraQuiz – A GenAI-Powered Quiz Engine

NeuraQuiz is a multimodal AI assistant that automatically generates, explains, and evaluates quizzes from PDFs, images, and lecture videos. Built with Google’s Gemini 1.5 Pro and OpenAI’s Whisper, it is designed to streamline classroom assessment and personalized learning.

---
## 🚀 Features

- 📄 **PDF to Quiz** – Extracts text and generates MCQs with explanations
- 🖼️ **Image to Quiz** – Analyzes educational images and generates questions
- 🎥 **Video to Summary** – Transcribes lectures and summarizes them
- 🧪 **Answer Evaluation** – Grades student responses with feedback and scoring
- 🎯 **Learning Path** – Recommends a 2-week study plan based on goals
---

## 💡 GenAI Capabilities Used

| Capability              | Model/Tool         |
|-------------------------|--------------------|
| Text + Image Reasoning  | Gemini 1.5 Pro     |
| Video Transcription     | Whisper            |
| Web UI                  | Streamlit          |
| PDF Parsing             | PyPDF2             |
| Image Handling          | Pillow (PIL)       |
| Secure Secrets          | Kaggle Secrets     |
| Deployment (Kaggle)     | Pyngrok            |

---

## 📦 Installation

```bash
git clone https://github.com/smit-6690/neuraquiz.git
cd neuraquiz
pip install -r requirements.txt
```
---

## 🔐 Setup
Create a `.streamlit/secrets.toml` file:

```toml
[general]
GOOGLE_API_KEY = "your-gemini-api-key"
```
Or load it from Kaggle Secrets if running in a notebook.
---

## ▶️ Run the App

```bash
streamlit run streamlit_app.py
```
---

## 📁 Project Structure

```
├── streamlit_app.py       # Main application
├── requirements.txt
├── utils/                 # Helper functions
├── .streamlit/secrets.toml
├── README.md
```

---

## 🧪 Example Use Cases

- Teachers auto-generating quizzes from lessons
- Students self-testing and receiving AI feedback
- EdTech builders embedding GenAI into learning platforms

---

## 📎 Resources

- [Google Gemini API](https://ai.google.dev)
- [OpenAI Whisper](https://github.com/openai/whisper)
- [Streamlit Docs](https://docs.streamlit.io)

---
