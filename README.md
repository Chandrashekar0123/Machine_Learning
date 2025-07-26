# 🩺 Disease Prediction from Medical Data

## 📌 Problem Statement

Predict the disease a patient might be suffering from based on a given set of symptoms using supervised machine learning algorithms. This project aims to assist healthcare professionals in early diagnosis and treatment planning.

---

## 🧾 Dataset Description

The dataset consists of 100+ symptoms and 40+ disease labels, where:

- Each row represents a unique patient record
- Each column (except `prognosis`) is a binary symptom: `0` (absent), `1` (present)
- The target column `prognosis` contains the predicted disease name

🗂 Example Symptoms:

- itching, skin_rash, nodal_skin_eruptions, shivering  
- acidity, fatigue, joint_pain, vomiting  
- headache, cough, chills, loss_of_appetite  
- ...and more

---

## 🔍 Project Workflow

```text
📁 Load Dataset
📊 Perform EDA (correlation, frequency, heatmaps)
🧹 Preprocess data (LabelEncoding, feature selection)
🤖 Train Machine Learning Model (DecisionTreeClassifier)
📈 Evaluate accuracy and visualize confusion matrix
🎯 Predict disease based on symptom input

---
```
##🔍 Exploratory Data Analysis (EDA)
```
✔️ Checked for symptom correlation using heatmaps
✔️ Visualized distribution of diseases
✔️ Identified top contributing symptoms using feature importance
✔️ Verified balance in class distribution
---


```
##  🎯 Model Insights

```text
✅ Algorithm: Decision Tree Classifier
✅ Accuracy Achieved: 98%
📉 Loss of Interpretability: Low (Tree-based visualization possible)
🧪 Evaluation Metric: Accuracy, Confusion Matrix
⚠️ Overfitting: Controlled via tree pruning

---

```
## Future Scope
 ```
Add frontend with Streamlit for easy symptom input

Enable multi-label classification for co-morbid diseases

Add NLP interface to process user-typed symptoms
