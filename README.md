# 🏨 Hotel Booking Cancellation Prediction

## 📌 Overview

Hotel booking cancellations significantly impact revenue and operational efficiency in the hospitality industry. This project uses Machine Learning techniques to predict whether a booking will be canceled or not based on customer and booking details.

The model helps hotels make data-driven decisions to minimize losses and improve customer experience.

---

## 🎯 Problem Statement

The objective of this project is to build a predictive model that can classify hotel bookings into:

* ✅ Not Canceled
* ❌ Canceled

By predicting cancellations in advance, hotels can:

* Optimize pricing strategies
* Improve resource allocation
* Reduce revenue loss
* Enhance customer satisfaction

---

## 📂 Dataset Description

The dataset contains **36,000+ hotel booking records** with the following features:

* 👥 Number of adults & children
* 🛏 Room type
* 🍽 Meal type
* 📅 Date of reservation
* ⏳ Lead time (days before booking)
* 💰 Average price
* 🚗 Parking availability
* 🔁 Repeated customer indicator
* 🎯 Booking status (Target Variable)

---

## ⚙️ Tech Stack

* **Programming Language:** Python 🐍
* **Libraries Used:**

  * Pandas & NumPy → Data handling
  * Matplotlib & Seaborn → Visualization
  * Scikit-learn → Machine Learning

---

## 🔍 Project Workflow

### 1. Data Collection

* Loaded dataset using Pandas

### 2. Data Preprocessing

* Handled missing values
* Removed duplicates
* Outlier detection and removal
* Encoding categorical variables
* Feature scaling

### 3. Exploratory Data Analysis (EDA)

* Histograms for distributions
* Countplots for categorical features
* Heatmap for correlations
* Scatter plots & boxplots

### 4. Feature Engineering

* Extracted **Year & Month** from reservation date
* Created new feature: **Price per Adult**

### 5. Model Building

Models used:

* Logistic Regression
* Support Vector Machine (SVM)

*(You can extend with Random Forest / XGBoost)*

### 6. Model Evaluation

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

## 📊 Key Insights

* 📈 Higher **lead time** increases chances of cancellation
* 💰 Pricing plays a significant role in booking decisions
* 🌐 Online bookings show different behavior compared to offline
* 🔁 Repeated customers are less likely to cancel

---

## 🚀 Results

* Successfully built a classification model for predicting cancellations
* Achieved good performance using standard ML algorithms
* Identified key features affecting booking behavior

---

## 🔮 Future Scope

* Implement advanced models like **XGBoost / LightGBM**
* Hyperparameter tuning for better accuracy
* Deploy model using **Flask / Streamlit**
* Real-time booking prediction system

---

## 📁 Project Structure

```
📦 Hotel-Booking-Prediction
 ┣ 📜 booking.csv
 ┣ 📓 hotel_booking_prediction.ipynb
 ┣ 📄 README.md
```

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📧 Contact

If you have any questions or suggestions, feel free to reach out!

---

⭐ If you found this project helpful, don't forget to star the repository!
