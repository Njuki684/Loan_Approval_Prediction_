# Loan Approval Prediction

## **Overview**
This project predicts loan approval outcomes based on applicant profiles, financial data, and credit history using machine learning models.  
The goal is to assist financial institutions in automating and improving their loan approval process, reducing manual errors and risk.

---

## **Dataset**
- **Source:** Kaggle - Loan Approval Prediction Dataset.
- **Description:** Contains loan application records with both categorical and numerical features.
- **Target Variable:** `loan_status` (Approved / Rejected).
- **Key Features:**
  - `loan_id`: Unique identifier for each loan.
  - `no_of_dependents`: Number of dependents of the applicant.
  - `education`: Graduate or Not Graduate.
  - `self_employed`: Whether the applicant is self-employed.
  - `income_annum`: Applicant’s annual income.
  - `loan_amount`: Amount of loan requested.
  - `loan_term`: Duration of the loan.
  - `cibil_score`: Credit score.
  - Asset-related columns: `residential_assets_value`, `commercial_assets_value`, `luxury_assets_value`, `bank_asset_value`.

---

## **Project Workflow**
1. **Business Understanding**  
   Define the problem and identify success metrics (loan approval prediction).

2. **Data Understanding & Exploration**  
   - Initial data checks: shape, missing values, data types.
   - Exploratory Data Analysis (EDA): Visualizations of trends, distributions, and correlations.

3. **Data Preparation**  
   - Handle missing values.
   - Encode categorical variables (e.g., education, self_employed).
   - Scale numerical features if needed.

4. **Modeling**  
   - Machine Learning algorithms applied:
     - Logistic Regression
     - Random Forest Classifier
     - XGBoost Classifier
   - Hyperparameter tuning for performance optimization.

5. **Evaluation**  
   - Metrics used: Accuracy, Precision, Recall, F1-score.
   - Confusion matrices and feature importance visualizations.

---

## **Key Insights**
- Applicants with **higher CIBIL scores** have a significantly higher approval rate.
- A lower **loan-to-income ratio** increases the likelihood of approval.
- Self-employed applicants tend to have slightly fewer approvals compared to salaried applicants.

---

## **Deliverables**
- **Jupyter Notebook:** `Loan_Approval_Prediction.ipynb`  
  Contains all steps from EDA to model evaluation.  
- **Presentation:** `Loan_Approval_Prediction_Presentation.pptx`  
  Non-technical presentation summarizing the approach and findings.  
- **requirements.txt:** Lists all necessary dependencies.  

---

## **Installation**
Clone the repository:

---

## Steps Followed in the Project
1. **Business Understanding** – Defining the problem and expected outcomes.  
2. **Data Understanding** – Exploring the dataset structure, identifying data types, and distributions.  
3. **Data Preparation** – Handling missing values, encoding categorical variables, and scaling numeric features.  
4. **Modeling** – Applying machine learning algorithms like Logistic Regression, Random Forest, or XGBoost.  
5. **Evaluation** – Measuring accuracy and performance using metrics such as confusion matrix, precision, recall, and F1-score.  
6. **Insights** – Identifying the most important factors affecting loan approvals.  

---

## Installation
Clone this repository and install the required dependencies:

```bash
pip install -r requirements.txt
