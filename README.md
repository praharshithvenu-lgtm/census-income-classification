Census Income Classification using Machine Learning

This project predicts whether a person’s annual income is ≤ 50K or > 50K based on demographic and work-related features using machine learning.

The goal is to build, compare, and evaluate multiple classification models and identify the best-performing one.

 Models Implemented
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

 Problem Type
- Binary Classification  
- Target Variable: Income (`0` = ≤50K, `1` = >50K)

 Dataset Information
The dataset contains features such as:
- Age
- Education
- Occupation
- Workclass
- Marital Status
- Gender
- Capital Gain & Loss
- Hours per Week
- Native Country

Missing values were handled and categorical variables were encoded before training.

 Project Workflow

1. Load Libraries  
2. Data Loading  
3. Exploratory Data Analysis (EDA)  
4. Preprocessing  
   - Handling missing values  
   - Encoding categorical features  
   - Feature scaling  
   - SMOTE for class imbalance  
5. Model Building  
6. Model Evaluation  
7. Performance Comparison  
 Model Performance Comparison

| Model | Accuracy | F1-Score |
|--------|------------|------------|
| Logistic Regression | 76% | 0.78 |
| Decision Tree | 82% | 0.82 |
| Random Forest | 85% | 0.85 |

 Conclusion
- Logistic Regression provides a good baseline.
- Decision Tree improves performance using non-linear patterns.
- **Random Forest is the best-performing model** in terms of Accuracy and F1-score
Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Imbalanced-learn
 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/praharshithvenu-lgtm/census-income-classification.git
cd census-income-classification
