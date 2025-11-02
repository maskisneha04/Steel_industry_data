# 🔋 Energy Consumption Prediction — Steel Industry Dataset

## 📌 Project Overview  
This project focuses on predicting **Energy Consumption (Usage_kWh)** in the steel industry using Machine Learning models.  
The aim is to help industries optimize their energy usage, reduce operational cost, and support sustainability.

---

## 📊 Dataset Details  
- **Dataset Name:** Steel Industry Energy Consumption Dataset  
- **Source:** Uploaded to Google Colab  
- **Target Variable:** `Usage_kWh`

### ✅ Feature columns include:
- Lagging Current Power Factor
- Leading Current Power Factor
- NSM (Number of Seconds from Midnight)
- WeekStatus (Weekday/Weekend)
- Day_of_week
- Load_Type
- And other sensor readings…

### ✅ Data Preprocessing Performed:
- Removed unnecessary columns
- Handled missing values
- Label encoded categorical columns
- Rescaled data where necessary

---

## 🧠 Machine Learning Model Used

Model: **Random Forest Regressor**

Evaluation Metrics:
- ✅ Mean Absolute Error (MAE)
- ✅ Root Mean Squared Error (RMSE)

---

## 📁 Project Structure
