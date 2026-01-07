# Lumina Sentiment AI: Neural Sentiment Intelligence 🏨


---
## 🚀 Key Features

- 🧠 **Transformer Neural Core (DistilBERT)**  
  Captures long-range context and semantic meaning better than traditional sequence models.

- ⚡ **Real-time Inference**  
  Powered by **FastAPI** for low-latency sentiment classification.

- 🎨 **Premium UX**  
  Glassmorphic **React** interface built with **Framer Motion** and **Tailwind CSS**.

- 📊 **Confidence Scoring**  
  Displays prediction confidence derived from softmax probabilities.

- 🔁 **Seamless Model Upgrade**  
  Backend upgraded from BiLSTM to Transformer without changing frontend or API contracts.

---

## 🛠️ Tech Stack

### 🔹 AI / ML
- TensorFlow 2.19  
- Hugging Face Transformers  
- DistilBERT (Transformer model)

### 🔹 Backend
- FastAPI  
- Python 3.11  
- Uvicorn  

### 🔹 Frontend
- React (Vite)  
- Tailwind CSS  
- Framer Motion  
- Axios  

---


## 📦 Installation & Setup

### 1. Backend
```bash
cd backend
python -m venv venv
pip install -r requirements.txt
python -m uvicorn main:app --reload
