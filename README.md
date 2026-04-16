# sahayak-ai-disaster-response-systemm
AI-powered disaster response system for real-time relief allocation, risk prediction, and adaptive decision-making.
#  Sahayak AI – Intelligent Disaster Response Systems

##  Overview

Sahayak AI is an AI-powered disaster response system designed to optimize the distribution of relief supplies such as food, water, and medicine in real-time during natural disasters.

It simulates a disaster command center that:
- Allocates resources efficiently
- Predicts shortages
- Adapts to changing conditions
- Explains decisions using AI reasoning

---

##  Problem Statement

In disaster scenarios, relief distribution is often:
- Delayed
- Poorly optimized
- Lacking real-time adaptability

Sahayak AI solves this by providing a **dynamic, intelligent decision-support system**.

---

##  Features

-  Smart resource allocation
-  Risk prediction (HIGH / MEDIUM / LOW)
-  AI-based decision explanations
-  Real-time simulation (road blocks, demand changes)
-  Scalable architecture for real-world data integration

---

##  Architecture
Frontend (React + Tailwind)
↓
Backend (FastAPI)
↓
AI & Optimization Engine
↓
Data Layer (Simulated / APIs)
---

##  Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios

### Backend
- FastAPI (Python)
- REST APIs

### AI Logic
- Rule-based + explainable AI reasoning

---

## How It Works

1. Input data (population, damage, accessibility)
2. Calculate demand per zone
3. Allocate supplies using optimization logic
4. Predict risk levels
5. Generate AI explanations
6. Adapt dynamically to new conditions

---

##  Getting Started

### Backend

```bash
cd backend
pip install fastapi uvicorn
python -m uvicorn main:app --reload
