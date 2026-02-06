# 🧠 MedCHAT — AI Health Therapist

MedCHAT is an AI-powered health support chatbot designed to provide empathetic conversational assistance, general health guidance, and emergency-aware responses. The system integrates a modern AI model with safety-focused logic to identify sensitive situations and respond responsibly.

This project demonstrates the use of AI in healthcare-oriented conversational systems while maintaining safety, empathy, and structured evaluation metrics.

---

## 🚀 Features

- ✅ AI-powered conversational health assistant  
- ✅ Gemini AI integration for natural responses  
- ✅ Emergency intent detection  
- ✅ Safe emergency handling (mock notification system)  
- ✅ Empathetic and supportive responses  
- ✅ FastAPI backend with Streamlit frontend  
- ✅ Evaluation metrics for model performance  
- ✅ Research-style evaluation pipeline

---

## 🏗️ Project Architecture

MedChat/
│
├── backend/
│ ├── main.py # FastAPI server
│ ├── ai_agent.py # AI agent logic
│ ├── tools.py # Emergency & helper tools
│ ├── config.py # API configuration
│
├── frontend.py # Streamlit UI
├── evaluate.py # Evaluation metrics script
├── evaluation_logs.csv # Generated interaction logs
├── README.md


---

## ⚙️ Tech Stack

- **Python 3.11+**
- **FastAPI** — Backend API
- **Streamlit** — Frontend Interface
- **LangChain / LangGraph**
- **Google Gemini API**
- **Scikit-learn** — Evaluation metrics
- **Pandas** — Data processing

---

## 🧩 How It Works

1. User enters a health-related query in the Streamlit interface.
2. Query is sent to the FastAPI backend.
3. AI agent processes the request using Gemini.
4. System checks for emergency intent.
5. Response is returned with empathetic and safe guidance.
6. Interaction is optionally logged for evaluation.

---

## 🚨 Emergency Handling

If the system detects self-harm or emergency intent:

- The chatbot provides supportive guidance.
- A safe mock message is triggered:

