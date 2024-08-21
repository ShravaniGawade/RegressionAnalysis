# Regression Analysis on Synthetic Dataset

## Project Overview
This project involves performing regression analysis on a synthetic dataset consisting of 5,000 records with 255 columns. The goal was to evaluate the performance of various regression models, including Linear Regression, Lasso, Ridge, and Random Forest, and identify the best-performing model. Exploratory Data Analysis (EDA) was conducted to understand the data, and appropriate preprocessing steps were applied to prepare the dataset for modeling.

## Key Features
- Exploratory Data Analysis (EDA): Conducted thorough EDA on 5,000 records with 255 features to understand data distribution, detect outliers, and identify important variables.
- Data Preprocessing: Scaled and encoded 4 categorical variables, followed by feature scaling to ensure all features contributed equally to the model.
- Model Evaluation: Applied Linear Regression, Lasso, Ridge, and Random Forest models to predict the target variable. The models were evaluated based on Mean Squared Error (MSE) and R² score.
- Best Model Performance: The Random Forest model outperformed other models with a Mean Squared Error (MSE) of 11.8 and an R² score of 0.58.

## Project Structure
- Data Preparation: Preprocessed the dataset by encoding categorical variables, handling missing values, and applying feature scaling.
- EDA: Performed Exploratory Data Analysis to gain insights into the data and understand feature distributions.
- Modeling: Evaluated multiple regression models (Linear Regression, Lasso, Ridge, Random Forest) and fine-tuned hyperparameters.
- Results Analysis: Compared model performance based on MSE and R² scores, with the Random Forest model achieving the best results.

## Tools & Technologies
- Python
- Pandas
- Scikit-learn (Linear Regression, Lasso, Ridge, Random Forest)
- Matplotlib
- Seaborn

## Results
Achieved a Mean Squared Error (MSE) of 11.8 and an R² score of 0.58 using the Random Forest model.
Successfully processed and scaled a large dataset with 255 features, ensuring optimal model performance.
Identified the most effective regression model for the synthetic dataset, providing valuable insights for future predictive modeling tasks.

## Future Work
Explore feature selection techniques to reduce the dimensionality of the dataset and improve model performance.
Experiment with other advanced regression models, such as Gradient Boosting or XGBoost, for comparison.
Implement cross-validation to ensure the model's generalizability to new data.
