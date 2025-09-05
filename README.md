# Task 03 – Decision Tree Classifier (Bank Marketing Dataset) 🌳

## Objective
The goal of this task was to build a Decision Tree Classifier to predict whether a customer will purchase a product/service based on their demographic and behavioral data.

---

## Dataset
- **Source:** UCI Machine Learning Repository – Bank Marketing Dataset  
- **Description:**  
  The dataset contains details about bank clients such as:
  - Demographics (age, job, marital status, education, etc.)
  - Banking-related features (balance, housing loan, personal loan, etc.)
  - Campaign-related data (contact type, number of contacts, previous outcome)

- **Target Variable:**  
  `y` → whether the client subscribed to a term deposit (`yes` / `no`).

---

## Steps Performed
1. **Data Preprocessing**
   - Handled categorical variables using one-hot encoding.
   - Split dataset into training and testing sets.

2. **Model Building**
   - Implemented a Decision Tree Classifier using Scikit-learn.
   - Tuned parameters (max depth, criterion).

3. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

4. **Visualization**
   - Decision Tree plotted with feature names.
   - Feature importance extracted to identify key predictors.

---

## Results
- **Accuracy Achieved:** ~XX% (replace with your result)  
- **Key Features Influencing Prediction:**
  - Duration of last contact
  - Age
  - Previous campaign outcome
  - Balance  

---

## Visualizations
📊 **Decision Tree Output**  
<img width="1891" height="903" alt="image" src="https://github.com/user-attachments/assets/0e91c2de-0536-4de5-b445-b54480d29123" />

📊 **Feature Importance Chart**  
<img width="437" height="251" alt="image" src="https://github.com/user-attachments/assets/61592783-d0a5-4594-8356-0f883ff1e9a1" />

📊 **Confusion Matrix**
<img width="653" height="337" alt="image" src="https://github.com/user-attachments/assets/b39a8fde-1fbe-4be5-8afc-e7e242060760" />


## Repository Contents
- `decision_tree.png` → Decision tree visualization  
- `feature_importance.png` → Feature importance bar chart  

---

## Conclusion
This task demonstrates how machine learning models like Decision Trees can be applied to marketing data to predict customer behavior and assist in targeted campaigns.
