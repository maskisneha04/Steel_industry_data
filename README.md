# 🔋 Energy Consumption Prediction — Steel Industry Dataset

## 📌 Project Overview  
This project focuses on predicting **Energy Consumption (Usage_kWh)** in the steel industry using Machine Learning models.  
The main objective is to help industries **optimize energy usage**, **reduce operational costs**, and **promote sustainability** through data-driven predictions.

---

## 📊 Dataset Details  
- **Dataset Name:** Steel Industry Energy Consumption Dataset  
- **Source:** Uploaded and preprocessed in Google Colab  
- **Target Variable:** `Usage_kWh`

### ✅ Feature Columns Include:
- Lagging Current Power Factor  
- Leading Current Power Factor  
- NSM (Number of Seconds from Midnight)  
- WeekStatus (Weekday/Weekend)  
- Day_of_week  
- Load_Type  
- and other relevant sensor readings  

### ✅ Data Preprocessing Performed:
- Removed unnecessary or irrelevant columns  
- Handled missing and inconsistent values  
- Label-encoded categorical features  
- Rescaled/standardized numerical features  

---

## 🧠 Machine Learning Model Used  

Model : **Random Forest Regressor**

### Evaluation Metrics
- ✅ **Mean Absolute Error (MAE)**
- ✅ **Root Mean Squared Error (RMSE)**

The Random Forest Regressor was chosen for its ability to handle non-linear relationships and provide robust accuracy on tabular energy datasets.

---

## 📈 Model Visualization
The following plot compares **Actual vs Predicted Energy Consumption**:

![Energy Prediction Graph](results/<img width="1200" height="500" alt="energy_prediction_results" src="https://github.com/user-attachments/assets/e44a09bc-4f3b-4bc4-bdba-eed5ee7e39f5" />
)

This visualization demonstrates that the trained model closely follows the actual consumption trends, confirming its reliability.

---

## 📁 Project Structure

