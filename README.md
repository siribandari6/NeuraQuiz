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

## 🔐 Setup
Create a secrets file for the Gemini API:

toml
Copy
Edit
# .streamlit/secrets.toml
[general]
GOOGLE_API_KEY = "your-gemini-api-key"
💡 If running on Kaggle, you can load secrets using Kaggle Secrets.

▶️ Run the App
bash
Copy
Edit
streamlit run streamlit_app.py
📁 Project Structure
Copy
Edit
neuraquiz/
├── streamlit_app.py         # Main Streamlit application
├── requirements.txt         # Python dependencies
├── utils/                   # Helper functions and utilities
├── .streamlit/secrets.toml  # API key configuration
├── README.md                # Project documentation
🧪 Example Use Cases
👩‍🏫 Teachers generating quizzes from lesson PDFs or slides

🎓 Students practicing MCQs and getting instant feedback

🛠️ EdTech developers integrating GenAI-powered assessments into platforms

📎 Resources
Google Gemini API

OpenAI Whisper

Streamlit Documentation

🛠️ Future Enhancements
🗂️ Upload batch files for bulk quiz generation

🔔 Notification and progress tracking system

🌍 Multilingual support for content translation
