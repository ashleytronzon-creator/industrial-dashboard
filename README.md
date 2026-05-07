# industrial-dashboard
Machine learning-based industrial production optimization system with Streamlit dashboard and control charts.
# 🏭 Industrial Production Optimization System

## 📌 Project Overview
This project is a machine learning-based industrial production optimization system designed to predict and optimize manufacturing efficiency using real production data.

It integrates:
- Machine learning prediction
- Constrained optimization
- Interactive Streamlit dashboard
- Statistical process monitoring (3-sigma control charts)
- What-if simulation for decision support

The system helps improve production efficiency, reduce errors, and support data-driven industrial decision-making.

GROUP MEMBERS 

HARO, AILEEN G.                                         
HERNANDEZ, MARINEL M.                                                  
SAPIENDANTE, KRISTINNA CARISSA R.                
SUPEDA, EARON JHAN A. 
TRONZON, ASHLEY V. 
UMAYAM, MARA LYNZEE D. 

---

## 🎯 Objectives
- Predict production processing time using machine learning
- Optimize machine parameters for better efficiency
- Monitor production stability using control charts
- Detect anomalies in production processes
- Provide interactive visualization and decision support

---

## 📊 Dataset Description
The dataset includes the following features:

- Processing_Time (Target Variable)
- Energy_Consumption
- Machine_Availability

---

## 🤖 Machine Learning Model
- Algorithm: Random Forest Regressor
- Type: Supervised Learning (Regression)
- Input Features: Energy Consumption, Machine Availability
- Output: Processing Time

---

## 📈 Model Performance Results

- Average Processing Time: **71.38**
- RMSE: **25.00**
- MAE: **21.43**

---

## ⚙️ System Features

✔ Production time prediction  
✔ Machine parameter optimization  
✔ What-if simulation tool  
✔ Residual control chart (3-sigma limits)  
✔ Anomaly detection system  
✔ Interactive Streamlit dashboard  
✔ Feature importance visualization  

---

## 🧠 Optimization Output Example

The system identifies optimal machine settings to improve production efficiency:

- Energy Consumption: **150.00**
- Machine Availability: **0.80**
- Maximum Predicted Processing Time: **64.04**

---

## 🛠 Installation

Install required dependencies:

```bash
pip install -r requirements.txt
