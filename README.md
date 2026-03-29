# 🚖 Uber Cab Dynamic Pricing Engine

A machine learning project that simulates how ride-hailing platforms dynamically adjust prices based on real-time conditions like demand, time, and weather.

---

##  Overview

In real-world systems, cab prices are not fixed. They change depending on factors such as:

- Time of day (peak hours vs normal)
- Weather conditions (rain, storms)
- Ride demand
- Location

This project builds a **dynamic pricing engine** that predicts the optimal cab fare using machine learning.

---

##  Key Idea

Instead of static pricing, this system:
- Takes real-time inputs
- Uses a trained ML model
- Returns an adjusted price instantly

---

##  Tech Stack

- **Python**
- **LightGBM / XGBoost**
- **FastAPI**
- **Pandas, NumPy**

---

##  Workflow

1. Data Collection  
   - Use dataset (Uber/Lyft or similar from Kaggle)

2. Data Preprocessing  
   - Handle missing values  
   - Feature engineering  

3. Model Training  
   - Train using LightGBM / XGBoost  
   - Evaluate performance  

4. API Deployment  
   - Build FastAPI endpoint  
   - Load trained model  

5. Prediction  
   - Input: time, weather, demand, etc.  
   - Output: predicted dynamic price  

---

## 📂 Project Structure
