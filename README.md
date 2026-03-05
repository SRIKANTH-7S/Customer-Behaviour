🏥📊 Customer Behavior Prediction for Insurance Companies
GANESH INSURANCE(GI)

A real-time, AI-powered system that **predicts insurance customer behavior**, classifies them as *"prominent"* or *"not prominent"*, and recommends personalized policies — all using deep learning.

> 📖 *Inspired by the book “AI 2041” — showing how AI can transform industries like insurance.*
> GANESH Insurance stands for *Generative AI Neural network Ensuring Smart Human-like contract*.
> It leverages a cutting-edge deep learning model to analyze health and lifestyle factors, offering personalized insurance plans tailored to individual needs.

## ✨ Why this project matters

In the traditional insurance industry, risk assessment is often manual, slow, and based on outdated data.  
This project **bridges that gap** by:
- Predicting risk in real-time
- Tailoring insurance products to customers
- Helping insurers identify high-risk profiles early
- Bringing transparency & personalization to end users

---


## 🎯 Project Highlights

✨ **Deep Learning Classification** – "Prominent" vs. "Not prominent"  
🧮 **Risk Scoring** – Predicts low / medium / high risk  
💡 **Policy Recommendation** – Suggests best-fit policies  
📊 **Interactive Dashboard** – Real-time analytics for insurers  
🤖 **AI Chatbot (GI)** – Answers queries and guides users  
⚡ **Underwriting Automation** – Faster, fairer decisions  
💰 **Smart Premiums** – Data-driven pricing suggestions

## 🛠 Tech Stack

| Layer        | Technology                                     |
|--------------|-----------------------------------------------:|
| Backend      | Python 3.8+, Flask REST API                    |
| ML / AI      | TensorFlow / Keras, scikit-learn, pandas, NumPy|
| Frontend     | React.js, Tailwind CSS, Chart.js / Recharts    |
| Database     | MongoDB & MongoDB Atlas                        |

---

Technologies Used:
- React frontend: customer & admin dashboards
- Flask backend: prediction API
- Deep Learning (TensorFlow): Built ANN model
- MongoDB: stores user data, predictions, policies

---

## 📁 Folder Structure

```plaintext
Customer-Behaviour/
├── backend/
│   ├── app.py                # Flask backend
│   ├── model.py              # Training & preprocessing
│   ├── health_risk_model.h5  # Trained model
│   ├── preprocessor.pkl      # Data scaler / encoder
│   ├── requirements.txt
│   └── .env
├── frontend/
│   ├── src/                  # React code
│   ├── public/               # Static assets
│   └── dist/                 # Build output
├── .gitignore
└── README.md
```

## ⚙️ Quick Start

### Prerequisites
- Python 3.8+
- Node.js 14+
- MongoDB running locally or via Atlas

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```
### Frontend
```bash
cd frontend
npm install
npm run dev
```

🌱 Future Enhancements
1. Explainable AI (XAI) to justify predictions using research paper
https://cdn.iiit.ac.in/cdn/rndshowcase.iiit.ac.in/tto2025/TTO_website_data/PDF/105.pdf
2. Integration with real-time government data (Aadhaar, PAN)
3. Cross-platform mobile app
4. Multilingual support

