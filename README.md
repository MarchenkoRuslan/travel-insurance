# Travel Insurance Prediction Model

## Project Overview
This project involves creating a machine learning model to predict whether customers of a travel agency will purchase travel insurance. The dataset includes details such as age, employment type, family members, chronic diseases, and previous travel and insurance history.

## Dataset
The dataset for this project contains the following features:
- `Age`: The age of the customer.
- `Employment Type`: The sector in which the customer is employed.
- `GraduateOrNot`: Whether the customer graduated from college or not.
- `AnnualIncome`: The annual income of the customer.
- `FamilyMembers`: The number of members in the customer's family.
- `ChronicDiseases`: Whether the customer has any chronic diseases.
- `FrequentFlyer`: Whether the customer is a frequent flyer.
- `EverTravelledAbroad`: Whether the customer has ever travelled abroad.
- `TravelInsurance`: Whether the customer bought travel insurance.

## Methods Used
- Exploratory Data Analysis (EDA)
- Statistical Inference
- Logistic Regression Modeling
- Performance Evaluation with a Confusion Matrix and ROC Curve

## Results
The logistic regression model achieved an accuracy of 76% on the test set, with an AUC score of 0.71 for the ROC curve.

## Conclusions and Future Work
The model serves as a good baseline, with potential improvements to be made in feature engineering, model complexity, and class imbalance treatment. Future work will focus on implementing these enhancements to increase predictive performance.
