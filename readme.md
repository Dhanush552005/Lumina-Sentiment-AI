# Lumina Sentiment AI: Neural Sentiment Intelligence 🏨

**Lumina Sentiment AI** is a premium full-stack sentiment analysis platform designed for the hospitality industry. It utilizes a **Bidirectional LSTM (Long Short-Term Memory)** neural network to interpret the nuance, sarcasm, and context of guest reviews.

## 🚀 Key Features
- **Bi-LSTM Neural Core:** Processes text sequences in both directions to capture complex context.
- **Real-time Inference:** Powered by **FastAPI** for sub-second classification.
- **Premium UX:** A glassmorphic **React** interface built with **Framer Motion** and **Tailwind CSS**.
- **Confidence Scoring:** Provides a percentage match alongside the sentiment classification.

## 🛠️ Tech Stack
- **AI/ML:** TensorFlow, Keras, NumPy, Pandas
- **Backend:** FastAPI, Python 3.11, Uvicorn
- **Frontend:** React (Vite), Tailwind CSS, Framer Motion, Axios

## 📦 Installation & Setup

### 1. Backend
```bash
cd backend
python -m venv venv
pip install -r requirements.txt
python -m uvicorn main:app --reload