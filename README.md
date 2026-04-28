# 🎮 Gaming vs Academic Performance Analysis

This project explores the relationship between gaming habits and academic performance using a dataset of 8000 students. The analysis focuses on behavioral, psychological, and lifestyle factors that may influence student grades.

---

## 📂 Dataset Overview

The dataset contains 14 features:

- `student_id` – Unique identifier
- `age` – Student age
- `gender` – Gender of the student
- `gaming_hours` – Daily gaming time
- `study_hours` – Daily study time
- `sleep_hours` – Daily sleep duration
- `attendance` – Attendance percentage
- `gaming_genre` – Preferred game genre
- `social_activity` – Social interaction level
- `device_usage` – Screen/device usage time
- `reaction_time_ms` – Reaction speed (milliseconds)
- `addiction_score` – Gaming addiction level
- `stress_level` – Stress category (Low, Medium, High)
- `grades` – Academic performance (target variable)

---

## 🎯 Objectives

- Analyze how gaming habits affect academic performance
- Identify key factors influencing student grades
- Explore relationships between lifestyle behaviors and success
- Build a predictive model for academic performance

---

## 🔍 Exploratory Data Analysis (EDA)

The analysis includes:

- Distribution analysis of grades
- Correlation analysis between numerical features
- Relationship between:
  - Gaming hours and grades
  - Study hours and grades
  - Sleep and academic performance
  - Addiction score and grades
- Categorical analysis:
  - Stress level vs grades
  - Gaming genre vs grades

---

## 📊 Key Insights

- 📚 **Study hours** show a strong positive correlation with grades
- 🎮 **Gaming hours** negatively impact performance when excessive
- 😴 **Sleep** is critical — both low and high sleep reduce performance
- ⚠️ **Addiction score** is negatively associated with academic success
- 🧠 **Stress level** significantly affects grades (higher stress → lower performance)
- 🏫 **Attendance** is one of the strongest predictors of success
- 🎯 **Gaming genre** has minimal impact compared to time spent
- ⚡ **Reaction time** shows a weak but notable relationship with performance

---

## 🤖 Machine Learning Model

A **Random Forest Regressor** was used to predict student grades.

### Steps:
- Data preprocessing (one-hot encoding)
- Train-test split (80/20)
- Model training
- Evaluation using Mean Absolute Error (MAE)

### Outcome:
The model successfully identifies key factors affecting academic performance, with strong contributions from:
- Study hours
- Attendance
- Addiction score
- Sleep patterns

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Future Improvements

- Use advanced models (XGBoost, LightGBM)
- Perform feature engineering for better accuracy
- Hyperparameter tuning
- Build an interactive dashboard (Streamlit)
- Add real-time prediction system

---

## 📌 Conclusion

Gaming is not inherently harmful, but excessive gaming combined with poor habits (low sleep, high stress, low study time) can significantly reduce academic performance. Maintaining balance is key.

---

## 👩‍💻 Author

Gizem Sena Çengel
