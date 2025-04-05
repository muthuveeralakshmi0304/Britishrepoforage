# ✈️ Predicting Customer Buying Behaviour – Airline Booking Analysis

This project is part of a business case where airlines aim to **predict whether a customer will complete a booking** based on historical booking behavior and preferences.

By proactively identifying customers likely to complete a booking, airlines can enhance marketing strategies, improve customer targeting, and increase revenue.

---

## 📊 Problem Statement

Modern-day customers are more informed and empowered than ever before. As a result, the airline industry must be **proactive**, not reactive, in acquiring and converting potential customers.

This project builds a **machine learning model** to predict whether a customer will complete a booking using their behavior and booking data.

---

## 📁 Dataset Overview

The dataset contains customer booking data with features such as:

- Number of passengers
- Sales channel
- Trip type
- Purchase lead time
- Length of stay
- Route
- Booking origin
- Flight preferences (e.g., wants meal, baggage, seat)
- Target variable: `booking_complete` (1 = booking made, 0 = not made)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy (Data Analysis)
- Scikit-learn (Machine Learning)
- Matplotlib, Seaborn (Data Visualization)
- Google Colab

---

## ⚙️ Model Building Process

1. **Data Preprocessing**:
   - Categorical encoding
   - Handling nulls
   - Feature engineering
2. **Model Training**:
   - Random Forest Classifier
3. **Model Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - Feature Importance Visualization

---

## 📌 Key Insights

- Features like **flight_hour**, **route**, and **wants_preferred_seat** were strong predictors.
- The Random Forest model achieved good accuracy and provided interpretability.
- Feature importance analysis helped understand key customer behavior drivers.

---

## 📈 Results

| Metric        | Score      |
|---------------|------------|
| Accuracy      | ~85%       |
| F1 Score      | Good Balance |
| Model Used    | Random Forest |

---

## 📷 Visualizations

<img src="images/feature_importance.png" alt="Feature Importance" width="500">

---

## 📂 Folder Structure
project-root/ │ ├── customer_booking_prediction.ipynb # Main notebook ├── README.md # This file ├── customer_booking.csv # Dataset ├── images/ │ └── feature_importance.png 

---

## 🚀 How to Run

1. Clone this repo
2. Open `customer_booking_prediction.ipynb` in Google Colab or Jupyter
3. Run all cells to see the analysis and results

---

## 🏆 Outcome

- Gained actionable insights on customer booking behavior
- Built a deployable machine learning model
- Created visual summaries for stakeholder reporting

---

## 🙋‍♀️ About Me

**Muthuveeralakshmi**  
Aspiring Data Analyst | AI & DS Final Year Student  
Passionate about solving business problems with data  
📫 [LinkedIn Profile](www.linkedin.com/in/muthuveera-lakshmi04)

---

## 🌐 License

This project is for educational purposes and open-source contributions. Attribution is appreciated.

