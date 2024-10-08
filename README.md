# Healthcare Premium Loan Prediction

## Description
<p>In today’s world, healthcare costs are rising, and securing the right premium loan can be daunting. The Healthcare Premium Loan Prediction App simplifies this process by harnessing the power of machine learning and data-driven insights.The Healthcare Premium Loan Prediction App leverages machine learning to provide instant predictions on healthcare premium loans based on personal details like age, income, medical history, and more.</p>

## Features:
* Interactive User Interface: A simple and intuitive UI for users to input details.
* Real-Time Prediction: Instantly predicts the healthcare premium loan eligibility based on the input.
* Model Customization: Two separate machine learning models used based on the age group of the individual (young or rest).
* Data Preprocessing: Real-time scaling and one-hot encoding for the input data.
* Medical Risk Calculation: Integrated medical history-based risk scoring system.
  
## Technology Stack
* Pandas: For data handling and manipulation.
* Scikit-learn: Used for machine learning model training, scaling, and preprocessing.
* Joblib: For saving and loading the trained models and scalers.
* Python: Core language for the backend processing.
* Streamlit: For building the web application and user interface.

## Models
### Young Model (Age ≤ 25)
This model is designed for individuals aged 25 and below. It uses machine learning to predict healthcare premium loans based on input features like age, income, medical history, and more.
#### Feature Importance (Young Model)
The feature importance graph below shows which features contribute the most to predictions for individuals aged 25 and below.
![Feature Importance Young](assets/feature_importance_young.png)


### Rest Model (Age > 25)
For individuals aged above 25, the Rest Model is used. It also considers key factors such as income, genetical risk, and medical history but may prioritize different features compared to the Young Model.
#### Feature Importance (Rest Model)
The feature importance graph below illustrates which features are most influential for individuals older than 25.
![Feature Importance Rest](assets/feature_importance_rest.png)

## Health Insurance Cost Prediction App
This is a web app for predicting health insurance costs based on various inputs. You can check it out here:
[Visit the Web App](https://healthcare-insurance-cost-predictor.streamlit.app/)
### Web App Preview
![Health Insurance Cost Prediction Web App](assets/app.png)


