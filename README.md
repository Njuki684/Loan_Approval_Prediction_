# Loan Approval Prediction Project

## Overview
This project aims to predict whether a loan application will be **Approved** or **Rejected** based on applicant demographics, financial details, and credit history.  
Using machine learning, we identify patterns in borrower profiles to improve decision-making.

---

## Dataset
The dataset contains the following key features:
- **loan_id** – Unique loan identifier.
- **no_of_dependents** – Number of dependents the applicant has.
- **education** – Education level (Graduate or Not Graduate).
- **self_employed** – Whether the applicant is self-employed.
- **income_annum** – Annual income of the applicant.
- **loan_amount** – Requested loan amount.
- **loan_term** – Loan term in years.
- **cibil_score** – Applicant’s credit score.
- **residential_assets_value** – Value of residential assets.
- **commercial_assets_value** – Value of commercial assets.
- **luxury_assets_value** – Value of luxury assets.
- **bank_asset_value** – Total bank asset value.
- **loan_status** – Target variable (Approved or Rejected).

---

## Project Structure
- **Loan_Approval_Prediction_Project.ipynb** – Jupyter Notebook with all steps (EDA, modeling, and evaluation).
- **loan_approval_dataset.csv** – Dataset used for analysis and modeling.
- **README.md** – Project overview and documentation.
- **requirements.txt** – List of required Python libraries.

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
