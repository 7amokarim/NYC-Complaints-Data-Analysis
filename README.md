# NYC Complaints Data Analysis & Prediction

## Overview
This project focuses on analyzing a large-scale NYC complaints dataset to extract meaningful insights and build a machine learning model for prediction. The goal is to understand complaint patterns across different locations and time periods, and predict whether a complaint is related to illegal parking.

---

## Objectives
- Identify the most common complaint types
- Analyze complaint distribution across boroughs, ZIP codes, and streets
- Explore temporal patterns (hour, day, month)
- Build a predictive model for illegal parking complaints
- Evaluate model performance and limitations

---

## Dataset
The dataset contains NYC complaint records including:
- Complaint type
- Borough and ZIP code
- Street name and location
- Date and time
- Agency and description

The data was loaded and processed using **Pandas**.

---

## Exploratory Data Analysis (EDA)

### Key Analysis Performed:
- Top complaint types
- Complaints distribution by borough
- ZIP code and street-level analysis
- Visualization using bar charts

### Insights:
- "Illegal Parking" was the most frequent complaint
- Certain boroughs had significantly higher complaint rates
- Complaints were concentrated in specific locations

---

## Temporal Analysis

We analyzed complaints over time to detect patterns:

- Hourly distribution
- Day of the week trends
- Monthly distribution

### Key Findings:
- Complaints peak during specific hours of the day
- Weekdays show different patterns compared to weekends
- Seasonal variation exists across months

---

## Machine Learning Model

### Model Used:
- Random Forest Classifier

### Steps:
- Feature selection (borough, ZIP code)
- Encoding categorical variables
- Train-test split
- Model training and prediction

---

## Model Evaluation

- Accuracy: ~82%
- Recall (Illegal Parking): Low (~6%)

### Interpretation:
- The dataset is imbalanced
- Features used are limited
- Model struggles to detect minority class

---

## Challenges
- Class imbalance in dataset
- Limited feature set for prediction
- Missing building-related information

---

## Future Improvements
- Apply techniques to handle class imbalance (SMOTE, class weights)
- Add more features (location clustering, time-based features)
- Use advanced models (XGBoost, Deep Learning)
- Build an interactive dashboard (Streamlit / Power BI)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

