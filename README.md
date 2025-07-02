# Job Prep: AI-Powered Career Development Platform

**Job Prep** is a career development platform engineered to streamline and enhance the job preparation process through a data-driven and modular architecture.

---

## 🚀 Features

- **Domain-wise Interview Question Generator** powered by locally hosted AI using [Ollama].
- **Aptitude & Coding Assessments** evaluated using custom algorithmic techniques.
- **Mock Interview Analysis** with:
  - Emotion & sentiment detection
  - Speech transcription (Whisper + HuggingFace)
  - Posture and eye-contact tracking
- **Video Uploads** and real-time feedback interface.
- **Admin Dashboards** for insights and performance tracking.

---

## 🛠 Tech Stack

| Layer         | Technologies |
|---------------|--------------|
| **Backend**   | Node.js, PHP, Python |
| **AI/ML**     | Whisper, Hugging Face Transformers, MediaPipe, Ollama |
| **Frontend**  | HTML, CSS, JavaScript (React.js) |
| **Database**  | MySQL |
| **Transcription** | Vosk and Whisper |

---

## 📁 Folder Structure

/backend
/models # AI models like Vosk
/storage # Intermediate/processed data
analyse.py # Main Python AI script
generate_questions.py

/frontend
*.php # UI and logic
*.json # Data I/O
style.css, script.js
/uploads # Video/audio/image uploads

## 🧠 Purpose

> The project’s ultimate goal is to deliver a robust, tech-enabled ecosystem that aligns individual skill development with current industry hiring standards. Its modular design allows easy scaling, personalization, and feedback-driven learning.

---
