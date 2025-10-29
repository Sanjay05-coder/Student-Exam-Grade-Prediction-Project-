Here’s the **final polished README.md** with a clear **summary section** and no code snippets:

---

# 📚 Student Exam Grade Prediction

## ✅ Summary
This project focuses on predicting **student final grades (A–F)** using machine learning classification techniques. The dataset was collected through a **Google Form survey**, where students provided details about their past academic habits and performance.  

I gathered **49 real responses** and added **17 synthetic entries** to balance underrepresented grades (D, E, F). The main objective was to identify which factors most strongly influence student performance and build a predictive model that can provide actionable suggestions for improvement.  

After training and testing multiple models, **XGBoost achieved the highest accuracy (~80%)**, outperforming Naive Bayes, Logistic Regression, and Decision Tree. The final solution was deployed using **Gradio**, allowing users to input three key features (Attendance, Study Hours, Midterm Score) and receive a predicted grade along with personalized improvement tips.  

I also tested the app with **three real users**, who confirmed that the predictions were fairly accurate and suggested adding more features like coursework and part-time job status for future versions.

---

##  Overview
The project aims to help students understand how factors like attendance, study habits, and midterm performance impact their final grades. It uses real-world data and machine learning to provide predictions and improvement suggestions.

---

##  Dataset
- **Total Records:** 49 real responses + 17 synthetic entries.
- **Target Variable:** Final Grade (A–F).
- **Key Features Selected:**
  - Attendance (%)
  - Average Study Hours per Week
  - Midterm Quiz Score

---

##  Workflow
1. Data Collection via Google Form.
2. Data Preprocessing:
   - Label Encoding for categorical values.
   - Feature scaling.
3. Exploratory Data Analysis (EDA):
   - Visualizations (box plots, count plots, heatmap).
4. Feature Selection based on correlation.
5. Model Training & Evaluation:
   - XGBoost, Naive Bayes, Logistic Regression, Decision Tree.
   - Metrics: Accuracy and Classification Report.
6. Deployment using Gradio for interactive predictions.

---

##  Model Performance
| Model              | Accuracy |
|--------------------|----------|
| **XGBoost**        | 0.80     |
| Naive Bayes        | 0.60     |
| Decision Tree      | 0.37     |
| Logistic Regression| 0.50     |

---

##  Features
- Real-world dataset with synthetic balancing.
- Multiple ML algorithms tested.
- Visualizations for EDA and performance comparison.
- Interactive Gradio interface for predictions.

---

##  Deployment
The Gradio app allows users to input:
- Attendance (%)
- Study Hours per Week
- Midterm Quiz Score

It predicts the **final grade** and provides **study improvement suggestions**.

---

##  Future Improvements from three participants who tested and  evaluates its accuracy, usability and gave suggestions which are:.
- Add more features (e.g., coursework, part-time job status).
- Collect larger and more diverse datasets.

---

## 📸 Screenshots
- Gradio Interface Output added in the ipynb file
