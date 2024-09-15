# AI-Based-Home-Loan-Approval-Predictor
Home Loan Approval prediction is a vital part of financial services. Traditionally, loan approval has relied on subjective human judgment, which can be slow and error-prone. This project tackles these issues by developing a predictive system using machine learning models like Logistic Regression and Random Forest to predict loan approval based on applicant profiles.


## Dataset

The dataset consists of 1033 loan applications, each containing attributes like:

- **Loan_ID**: A unique identifier for each loan application.
- **Gender**: Gender of the applicant (Male/Female).
- **Married**: Marital status of the applicant (Yes/No).
- **Dependents**: Number of dependents (0, 1, 2, 3+).
- **Education**: Education level of the applicant (Graduate/Not Graduate).
- **Self_Employed**: Indicates whether the applicant is self-employed (Yes/No).
- **ApplicantIncome**: Applicant's income.
- **CoapplicantIncome**: Co-applicant's income.
- **LoanAmount**: Loan amount (in thousands).
- **Loan_Amount_Term**: Loan repayment term (in months).
- **Credit_History**: Applicant's credit history (1: Good, 0: Bad).
- **Property_Area**: Area of the property (Rural/Urban/Semi-urban).


The dataset is split into two subsets:

70% for training (723 entries)
30% for testing (310 entries)
## Methodology

1. Data Preprocessing: Cleaned the dataset to handle missing values and standardized the features.
2. Model Selection: Implemented two machine learning models:
- Logistic Regression
- Random Forest Classifier
3. Training: Models were trained using the training set, and hyperparameters were optimized.
4. Evaluation: Evaluated the models using accuracy metrics and confusion matrices on the test dataset.
## Results

- Logistic Regression achieved an accuracy of 80.13%.
  
  ![image](https://github.com/user-attachments/assets/59b8513e-d3fb-46d8-ab93-2bfb08493f32)

- Random Forest Classifier achieved an accuracy of 76.01%.
  
  ![image](https://github.com/user-attachments/assets/ad578de6-da03-4da5-a54d-3e89214f4985)

- Logistic Regression performed slightly better than the Random Forest Classifier for this dataset, making it the more suitable model for this task.
