# Loan Approval Prediction using Decision Trees

## Project Overview
This project applies machine learning techniques to predict whether a loan application should be approved based on applicant details.  
The objective is to support financial institutions in making faster and data-driven lending decisions.

---

## Technologies Used
- Python  
- Scikit-learn  
- Pandas  
- Matplotlib / Seaborn (for visualization)  
- Jupyter Notebook  

---

## Dataset
- The dataset contains applicant information such as income, loan amount, credit history, and employment details.  
- Data preprocessing steps were applied to handle missing values and categorical variables.  

---

## Methodology

### Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Normalized/standardized numerical features  

### Model Development
- Implemented a Decision Tree Classifier  
- Trained and validated using Scikit-learn  
- Hyperparameter tuning for optimal performance  

### Evaluation
- Metrics: Accuracy, Precision, Recall, and F1-score  
- Feature importance analysis to identify key approval factors  

---

## Results
- The Decision Tree model achieved high accuracy on the test set.  
- Key features influencing approvals included applicant income, loan amount, and credit history.  

---

## How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
   ```
2. Navigate to the project folder and open the notebook:
   ```bash
   jupyter notebook Loan_Approval_Prediction.ipynb
   ```
3. Run all cells to reproduce the results.

## Conclusion

This project demonstrates the application of decision trees for loan approval prediction.
The model not only provides reliable accuracy but also interpretability, making it suitable for practical use in financial decision-making.
