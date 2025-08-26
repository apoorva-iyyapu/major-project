# 🌧️ Precipitation Runoff Prediction

This repository contains my **B.Tech Major Project** on **Precipitation Runoff Prediction**.  
The project applies **machine learning techniques** (Linear Regression, Random Forest, XGBoost, CatBoost) to predict rainfall based on historical weather datasets. Accurate rainfall forecasting helps in **agriculture, water resource management, and disaster prevention**.

---

## 📖 Project Overview
Rainfall prediction is vital for minimizing the risks of **floods, droughts, and crop failures**.  
In this project, multiple machine learning models were trained on the **Austin weather dataset** to estimate precipitation levels.  

The models analyze parameters like **humidity, dew point, sea-level pressure, visibility, and wind speed** to predict the amount of rainfall (in inches).

---

## 🎯 Objectives
- Build predictive models for **precipitation forecasting**.  
- Improve accuracy over traditional regression-based approaches.  
- Compare performance of **Linear Regression, Random Forest, XGBoost, and CatBoost**.  
- Provide insights for future adoption of **deep learning models**.  

---

## ⚙️ Methodology
1. **Dataset**  
   - Austin weather dataset (2013-12-21 → 2017-07-31).  
   - Features include: temperature, humidity, dew point, pressure, visibility, wind, and precipitation.  

2. **Data Preprocessing**  
   - Handled missing values and formatted weather attributes.  
   - Converted categorical values like `'T'` (trace rainfall) to numeric.  

3. **Models Used**  
   - 🔹 **Linear Regression** – baseline model.  
   - 🌲 **Random Forest** – tree-based model, effective for light/moderate rainfall prediction.  
   - ⚡ **XGBoost** – efficient gradient boosting, handles structured data well.  
   - 🐱 **CatBoost** – advanced gradient boosting, strong performance with categorical data.  

4. **Evaluation**  
   - Train/Test split applied.  
   - Models compared based on prediction accuracy and error rate.  

---

## 🛠️ Tech Stack
- **Language:** Python 3.6  
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn, Seaborn  
- **Environment:** Google Colab  
- **Frontend (optional extension):** HTML5, CSS3, Bootstrap, JavaScript  

---

## 📊 Design
- **Architecture Diagram** showing dataset flow, preprocessing, ML model training, and prediction.  
- **UML Diagrams:** Use case, sequence, activity, and class diagrams describe workflow and interactions.  

---

## 🚀 Results
- Machine Learning models provided rainfall predictions with promising accuracy.  
- **Random Forest & XGBoost** performed well for structured weather data.  
- **CatBoost** showed potential for further improvement in predictive accuracy.  

---

## 🔮 Future Enhancements
- Integrate **Deep Learning models** such as:
  - Multilayer Perceptron (MLP)  
  - Convolutional Neural Networks (CNNs)  
- Perform **comparative study** of ML vs DL models.  
- Deploy as a **web-based application** for real-time rainfall forecasting.  

---
