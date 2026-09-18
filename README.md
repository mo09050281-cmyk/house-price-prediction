# 🏡 House Price Prediction (End-to-End ML Web App)

A full-stack machine learning web application that predicts house prices based on various features such as area, number of floors, bathrooms, location, and furnishing status.

---

## 🛠️ Tech Stack

* **Machine Learning:** Python, Pandas, Scikit-Learn, Joblib
* **Backend:** FastAPI, Uvicorn, Pydantic
* **Frontend:** React, TypeScript, Axios
* **Testing:** Pytest

---

## 🚀 Getting Started

### 1️⃣ Prerequisites
* Python 3.11+
* Node.js 18+

### 2️⃣ Backend Setup
```bash
cd backend
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
python -m uvicorn app.main:app --reload