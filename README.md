🎤 VocalMind: Real-Time Multilingual Emotion Detection from Speech
📌 Overview
VocalMind is a real-time emotion detection platform that captures and analyzes emotional states from spoken language. Supporting multiple languages, it transcribes, translates, and classifies speech using powerful NLP models, offering insightful emotional feedback through a sleek interactive dashboard.

Built with Flask and Node.js on the backend and React.js on the frontend, VocalMind is modular, scalable, and optimized for near-instantaneous response.

---

![WhatsApp Image 2025-05-27 at 11 22 41_964c7949](https://github.com/user-attachments/assets/b89c7a16-c565-486f-8fc6-6e5bd711b636)

![WhatsApp Image 2025-05-27 at 11 22 49_9ed344bb](https://github.com/user-attachments/assets/b36ef351-10f7-40b2-a75a-c853a2b74ca1)

![WhatsApp Image 2025-05-27 at 11 23 00_aa8ac564](https://github.com/user-attachments/assets/aa77d34e-643c-4ac2-bdd8-9357365f0041)



 Features
🎙 Speech Recognition
Converts audio input into text using Google Speech Recognition API.

🌍 Language Detection & Translation
Detects non-English languages and translates them to English via Google Translate API.

🤖 Emotion Classification
Analyzes emotional tone using the roberta-base-go_emotions transformer model for fine-grained emotion tagging and confidence scoring.

🖥 Live Dashboard
Real-time UI displays detected emotions clearly, with responsive and interactive visuals.

⚡ Low Latency Feedback
Quickly processes and displays emotional insights upon audio upload.



---

🛠 Tech Stack
Backend:

Flask (Python) for emotion detection API

Node.js + Express for routing and API middleware

Google Speech Recognition API

Google Translate API

Hugging Face Transformers (roberta-base-go_emotions)

Frontend:

React.js for dynamic UI

Tailwind CSS for styling

TypeScript for type-safe development

Architecture:

Modular: Flask (ML logic) + Node.js (API gateway) + React (client)

Reusable & scalable codebase for future expansion (e.g., video, text inputs)

---

## 📁 Project Structure
```bash
Emotion-Detection-Voice/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   └── index.js
│   ├── flask_api/
│   │   └── emotion.py
│   ├── uploads/
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   └── index.js
│   ├── public/
│   └── package.json
├── README.md
└── .gitignore

