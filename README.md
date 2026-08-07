# 📘 AI-Driven Student Performance Prediction System 

## 📌 Introduction  
EduPredict is an AI-powered system designed to analyze student academic and behavioral data to predict performance outcomes such as **Pass/Fail classification, dropout risk, and overall academic trends**. By leveraging **Machine Learning** models, the system provides institutions and educators with **early intervention insights**, helping improve student success rates.  

---

## 🎯 Objectives  
- Predict student performance based on academic and behavioral attributes.  
- Identify patterns and risk factors that affect academic success.  
- Provide educators with actionable insights to support struggling students.  
- Develop a user-friendly analytics dashboard for visualization.  

---

## ✨ Features  
- 📊 **Performance Prediction** – Predicts student outcomes (pass/fail or grades).  
- 🧠 **Machine Learning Models** – Uses classification algorithms like Random Forest, Logistic Regression, and XGBoost.  
- 🔍 **Analytics Dashboard** – Visualizes trends, failure risk, and subject-wise performance.  
- 📈 **SHAP-based Explainability** – Explains why a prediction was made.  
- 📂 **Custom Dataset Handling** – Works with student academic and behavioral datasets.  

---

## 📂 Dataset  
The dataset includes:  
- Student academic scores (subject-wise marks, GPA, previous performance).  
- Attendance records.  
- Behavioral attributes (participation, assignments, activities).  
- Target label: **Pass/Fail or Grade classification**.  

---

## 🛠️ Tech Stack  
- **Programming Language**: Python 🐍  
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn    
- **Database**: SQLite / CSV for dataset storage  
- **Version Control**: Git & GitHub

## Methodology
The methodology adopted in this project follows a systematic
approach to build an AI-powered Student Performance & Analytics
System.
The process is divided into multiple phases as outlined below:

- Data Collection & Preprocessing
- Feature Engineering
- Model Selection & Training
- Explainability with SHAP
- User Interface Development
- Authentication & Database Integration
- Testing & Evaluation

## Data Visualization
Data visualization was performed to gain insights into the dataset and better
understand patterns in student performance. Various plots and charts were
created to analyze subject scores, attendance, and other academic behavior
factors.

- Distribution of Subject Scores
Histograms and boxplots were used to visualize the distribution of scores
across all subjects.This helped identify the spread of marks, detect outliers, and
observe performance trends in different subjects.

- Pass vs. Fail Comparison
Bar charts were plotted to compare the number of students who passed vs.
failed.This provided clarity on dataset balance and highlighted the importance
of certain features.

- Correlation Heatmap
A heatmap was generated to analyze correlations among subject scores and other numerical features.Strong correlations were observed between science
subjects (Physics, Chemistry, Biology), while weak correlations were seen with
extracurricular and demographic features.

- Weekly Self-Study Hours
Visual analysis indicated that students with higher self-study hours performed
better, confirming its importance as a feature in the model.

- Pass / Fail Distribution by Gender 
Pass and fail distribution on the baisis of gender represented by the Barchart.

## Why Random Forest?
- Handles Mixed Data Types: Efficiently processes both categorical (e.g.,
gender, activity participation) and numerical (e.g., scores, attendance)
features.
- Robust Performance: Delivers consistent results even on moderately
sized and imbalanced datasets.
- Captures Complex Patterns: Effectively models non-linear relationships
and feature interactions, which are common in student behaviour and
performance data.

## Explainability with SHAP (SHapley Additive Explanations)
 To ensure transparency in model predictions, the project integrates SHAP
(SHapley Additive Explanations). SHAP provides a way to understand how
individual features contribute to the model’s output for both single and batch
predictions.
- It assigns each feature a contribution value (positive or negative)
showing whether it pushed the prediction towards Pass or Fail.
- Teachers can visually interpret results using SHAP decision plots, which
illustrate how subject scores, attendance, study hours, and other
features influence predictions.
- For example, a low math score or high absence days may strongly
contribute towards a "Fail" prediction, while regular self-study and good
English performance may push the result towards "Pass".
- This improves trust and accountability, as teachers can understand not
just the prediction but also the reason behind it.


### 💡 Why This Project Matters

This project can help:

- 🏫 **Schools** identify academically weak students early
- 👩‍🏫 **Teachers** provide targeted, individualized support
- 👨‍👩‍👧 **Parents** monitor student progress proactively
- 💻 **Educational platforms** personalize learning strategies at scale

### 🌍 Real-World Applications

- 🚨 Student risk analysis
- 📈 Academic performance monitoring
- 🎯 Personalized education systems
- 📊 Educational analytics dashboards

---
### 📊 Results

- Achieved 96% accuracy using Random Forest.

- SHAP values highlighted key factors: subject performance, attendance, and assignment completion.

- Provided interpretable insights for educators to take timely action.
