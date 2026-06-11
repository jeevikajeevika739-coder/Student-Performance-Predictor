# 🎓 Student Performance Predictor

A Machine Learning project that predicts a student's final grade
based on study hours, attendance, past failures, and mid-term grades.

## 📌 Problem Statement
Students often don't know if they are at risk of scoring low marks.
This system predicts their final grade and flags if they need urgent support.

## 📊 Dataset
- Source: UCI Machine Learning Repository
- 395 real student records
- Features: Study Hours, Absences, Past Failures, Mid1 Grade, Mid2 Grade

## 🤖 Models Used
| Model | R² Score | MAE |
|-------|----------|-----|
| Linear Regression | 0.782 | 1.339 |
| Ridge Regression | 0.782 | 1.339 |
| Random Forest ✅ | 0.871 | 1.055 |

> Random Forest performed best with 87% accuracy!

## 📈 Key Finding
Mid-term grades are the strongest predictor of final performance.
Even students with poor attendance can pass if mid-term scores are high.

## 🛠️ Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Project Structure
- `Student_Performance_Predictor.ipynb` — Main notebook with full code
