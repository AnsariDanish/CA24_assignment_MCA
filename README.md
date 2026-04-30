# 📊 Multi-Output Time-Series Forecasting using LSTM & GRU

## 📌 Assignment Details
- **Course Assignment**: CA 24 – Theory Assignment 1  
- **Weightage**: 10 Marks  
- **Date Given**: April 10, 2026  
- **Due Date**: April 30, 2026  

---

## 📖 Project Overview
This project focuses on **multi-output time-series forecasting** using deep learning techniques, specifically **LSTM (Long Short-Term Memory)** and **GRU (Gated Recurrent Unit)** models.

The goal is to predict multiple future values of stock prices based on historical data from the NIFTY-50 stock market.

---

## 📂 Dataset
- Source: Kaggle  
- Dataset Name: *NIFTY-50 Stock Market Data (2000–2021)*  
- Link: https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data/data  

### 📊 Dataset Description
The dataset contains historical stock data including:
- Open price  
- Close price  
- High price  
- Low price  
- Volume  
- Date-wise records for multiple companies in NIFTY-50  

---

## 🎯 Objectives
- Perform time-series forecasting using deep learning  
- Implement and compare:
  - LSTM model  
  - GRU model  
- Predict **multiple future time steps (multi-output forecasting)**  
- Evaluate model performance using standard metrics  

---

## ⚙️ Technologies Used
- Python 🐍  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- TensorFlow / Keras  

---

## 🧠 Model Architecture

### 🔹 LSTM Model
- Handles long-term dependencies in time-series data  
- Suitable for sequential prediction tasks  

### 🔹 GRU Model
- Simplified version of LSTM  
- Faster training with comparable performance  

---

## 🔄 Workflow
1. Data Collection & Preprocessing  
2. Feature Scaling (Normalization)  
3. Sequence Creation (Sliding Window)  
4. Model Building (LSTM & GRU)  
5. Training & Validation  
6. Multi-step Prediction  
7. Performance Evaluation  

---

## 📈 Evaluation Metrics
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- Mean Absolute Error (MAE)  

---

## 📊 Results
- Both models successfully learned time-series patterns  
- GRU provided faster training time  
- LSTM performed slightly better in capturing long-term trends *(modify based on your actual results)*  

---
