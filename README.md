# Loan Prediction with Random Forest Classification

## Introduction
Dream Housing Finance faced the challenge of efficiently validating customers eligibility for home loans. To address this, the company decided to automate the validation process in real-time using customer data such as gender, marital status, income, loan amount, and credit history.

The project utilized the available datasets to develop machine learning models capable of identifying eligible customers. This solution not only improves operational efficiency but also enables the company to target customers more precisely.

## Variable Description
| Variable           | Description                               |
|--------------------|-------------------------------------------|
| Loan ID            | Unique Loan ID                            |
| Gender             | Male/ Female                              |
| Married            | Applicant married (Yes/ No)               |
| Dependents         | Number of dependents                      |
| Education          | Applicant Education (Graduate/ Not Graduate) |
| Self Employed      | Self employed (Yes/ No)                   |
| Applicant Income   | Applicant income                          |
| Coapplicant Income | Coapplicant income                        |
| Loan Amount        | Loan amount in thousands                  |
| Loan Amount Term   | Term of loan in months                    |
| Credit History     | Credit history meets guidelines           |
| Property Area      | Urban/ Semi Urban/ Rural                  |
| Loan Status        | (Target) Loan approved (Yes/ No)          |

## Conclusion
The evaluation results showed that the F1-Score value of the model before hyperparameter tuning was 85,25%, while after tuning, the value increased to 85,87%. This increase indicates that the tuning process has a positive impact on the performance of the model, although the increase is relatively small.
