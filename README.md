# Medical_Insurance_Price_Prediction_Using_ML

# Project Overview

This project aims to analyze the factors that significantly affect medical insurance costs and to develop a predictive model to assist in pricing and risk assessment.

# Objective

The primary goal is to predict medical insurance expenses using various factors, including age, sex, BMI, smoking status, number of children, and region.

# Steps Taken

1. Data Import and Exploration

- Loaded a dataset containing information about 1338 individuals with 6 independent features and 1 target variable (charges).
- Performed exploratory data analysis (EDA) to identify relationships between features and the target variable.

2. Data Preprocessing

- Checked for and addressed duplicates in the dataset.
- Identified and treated outliers in the BMI column using the IQR method.
- Examined the distribution of continuous variables such as age and BMI.
- Encoded categorical data (sex, BMI, region) for use in the predictive model.

3. Model Development
   
- Tested multiple machine learning models, including Linear Regression, SVR, Random Forest Regressor, Gradient Boosting Regressor, and XGBoost Regressor.
- Used cross-validation and grid search to fine-tune hyperparameters.
- Found XGBoost to be the best-performing model based on evaluation metrics.

4. Feature Importance
   
- Analyzed feature importances in the final XGBoost model to determine which features most significantly impact predictions.

5. Final Model

- Trained the final XGBoost model with optimized hyperparameters.
- Simplified the model by removing less important features.

6. Prediction on New Data

- Showcased the trained model's ability to predict medical insurance charges for new data.

# Conclusion

The XGBoost model, after comprehensive analysis and tuning, proved to be the most effective for predicting medical insurance charges. The model's feature importance analysis provides valuable insights into the factors that drive insurance costs.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any inquiries or feedback, please reach out to:

- Name: Yuvraj Badmal
- Email: badmal.uv@gmail.com
