# Zeex AI Technical Projects

This repository contains my submissions for the **Zeex AI Technical Projects** task.

---

## 🧠 Project 1: Traffic Prediction (Model Implementation)

**File:** `Traffic_Prediction.ipynb`  
**Libraries:** pandas, numpy, scikit-learn, matplotlib  

### Overview
This notebook builds a machine-learning model to predict traffic volume.  
- **Model:** LSTM (time-series forecasting)  
- **Reason:** captures temporal dependencies in traffic data  
- **Preprocessing:** handled missing values, scaled data, created window sequences  
- **Performance:** achieved ≈
- Final Results in MPH 
  FINAL MAE (Mean Absolute Error): 2.44 MPH
  FINAL RMSE (Root Mean Square Error): 5.14 MPH
- **Strengths:** good trend prediction  
- **Weaknesses:** less accurate for sudden events/outliers  

### How to Run
```bash
pip install -r requirements.txt
jupyter notebook Traffic_Prediction.ipynb
