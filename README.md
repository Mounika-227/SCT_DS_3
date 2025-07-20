# 📊 Task 3 – Decision Tree Classifier on Bank Marketing Dataset

### ✅ SkillCraft Technology Internship – Data Science Track

This task focuses on building and visualizing a Decision Tree Classifier using the Bank Marketing dataset. The goal is to predict whether a client will subscribe to a term deposit based on their demographic and campaign-related attributes.

---

## 📁 Dataset Overview

- **Dataset**: Bank Marketing Dataset
- **File Name**: `bank-full.csv`
- **Delimiter**: Semicolon (`;`)
---

## 🛠️ Tools & Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib

---

## 📌 Workflow Summary

1. **Import Libraries**: Load all required Python libraries.
2. **Load Dataset**: Read the CSV file using `pandas`.
3. **Data Preprocessing**:
   - Encode categorical variables using `LabelEncoder`.
   - Split features (`X`) and target (`y`).
4. **Train-Test Split**: Divide the data into training and testing sets.
5. **Model Building**: Train a `DecisionTreeClassifier` on the training set.
6. **Prediction**: Predict outcomes on the test data.
7. **Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
8. **Visualization**: Plot the trained decision tree using `plot_tree()` from `sklearn.tree`.

---

## 📈 Model Evaluation

The classifier was evaluated using standard classification metrics:
- **Accuracy**
- **Precision, Recall, F1-Score**
- **Confusion Matrix**

These metrics help assess how well the model distinguishes between clients who subscribed and those who didn’t.



