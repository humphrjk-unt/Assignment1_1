# Assignment1_1

# Assignment: Logistic Regression with Stepwise Selection
Course: Advanced Data Analytics
Module: Logistic Regression
Total Points: 100

Objective
In this assignment, you will analyze the German Credit Dataset to develop a logistic regression model for predicting loan defaults. You will apply stepwise regression techniques to improve model performance while interpreting key statistical metrics.

Instructions
# Part 1: Data Preprocessing (20 points)
Load the dataset (GermanCredit.csv) and display its structure.
Check for missing values and decide on appropriate handling strategies.
Convert categorical variables into numerical representations using one-hot encoding.
Drop any irrelevant columns (e.g., observational indices).

# Part 2: Logistic Regression Model (30 points)
Split the dataset into training (70%) and testing (30%) sets.
Fit an initial logistic regression model using statsmodels.api.Logit(), predicting RESPONSE as the target variable.
Extract and interpret key metrics such as:
Coefficients and their statistical significance
Model fit statistics (AIC, BIC, Log-likelihood)

#Part 3: Stepwise Regression (30 points)
Implement a stepwise selection process to refine the model by iteratively adding or removing predictors.
Use forward selection (start with no predictors and add the most significant ones).
Use backward elimination (start with all predictors and remove the least significant ones).
Implement bidirectional elimination (combine both forward and backward approaches).
Compare the refined model’s performance metrics with the initial model.

# Part 4: Model Evaluation and Interpretation (20 points)
Compute the confusion matrix, accuracy, and classification report on the test dataset.
Evaluate the effect of feature selection on model performance.
Discuss whether multicollinearity was an issue and how it was handled (use Variance Inflation Factor (VIF) if applicable).
Provide a summary of findings, including model limitations and potential improvements.

# Deliverables
A Jupyter Notebook with documented code, outputs, and explanations.
A brief summary report (1-2 pages) interpreting the results and explaining model refinements.
