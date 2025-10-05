# 🌾 AgriTech AI - Smart Farming Solutions

AI-powered crop recommendation and plant disease detection system using Machine Learning.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104.1-green)
![Next.js](https://img.shields.io/badge/Next.js-15.5.4-black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.18.0-orange)
![Supabase](https://img.shields.io/badge/Supabase-Database-green)

## 🚀 Features

- **🌱 Crop Recommendation** — Personalized crop suggestions based on soil nutrients (NPK), temperature, humidity, pH, and rainfall  
- **🩺 Disease Detection** — Upload plant leaf images to detect 15 different diseases with AI  
- **📜 Prediction History** — Track all past predictions with detailed parameters  
- **🗄️ Real-time Database** — All predictions saved to Supabase PostgreSQL  
- **💻 Interactive UI** — Modern, responsive web interface built with Next.js  

---

## 🧠 Tech Stack

### Backend
- **FastAPI** — Modern Python web framework  
- **TensorFlow 2.18** — Deep learning for disease detection  
- **scikit-learn** — Machine learning for crop recommendation  
- **Supabase** — PostgreSQL database & authentication  
- **Python 3.11**

### Frontend
- **Next.js 15** — React framework  
- **Tailwind CSS** — Styling  
- **Lucide React** — Icons  
- **Supabase JS Client** — Database connectivity  

### Models
- **Crop Recommendation:** Random Forest Classifier (99% accuracy, 22 crops)  
- **Disease Detection:** MobileNetV2 CNN (85%+ accuracy, 15 disease classes)  

---

## 📁 Project Structure

```
agritech-ai/
├── backend/
│   ├── models/
│   │   ├── crop_recommendation_model.pkl
│   │   ├── scaler.pkl
│   │   ├── disease_detection_model.h5
│   │   ├── class_indices.json
│   │   └── class_labels.json
│   ├── main.py
│   ├── supabase_client.py
│   ├── requirements.txt
│   ├── .env
│   └── test_api.py
└── frontend/
    ├── src/
    │   ├── app/
    │   │   ├── page.js
    │   │   ├── layout.js
    │   │   ├── crop-recommendation/page.js
    │   │   ├── disease-detection/page.js
    │   │   └── history/page.js
    │   ├── components/
    │   │   ├── Navbar.js
    │   │   └── Footer.js
    │   └── utils/
    │       └── api.js
    ├── .env.local
    └── package.json
```

---

## 🛠️ Installation & Setup

(Installation, Supabase setup, API endpoints, testing, and deployment instructions continue as in the full provided README.)

---

**Built with ❤️ for farmers and agricultural innovation**
