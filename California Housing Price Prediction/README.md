
# California Housing Price Prediction

Overview :- 

This project involves predicting California housing prices using two different regression techniques: 
i) Simple Linear Regression and ii) Multiple Linear Regression. 
Each approach involves distinct steps in the machine learning process, detailed below.


## [Documentation](https://linktodocumentation)

Simple Linear Regression
1. Data Collection and Exploration
Load the Data: Import the dataset containing housing prices and various features.
Explore the Data: Use descriptive statistics and visualizations to understand the distribution and relationships within the data.

2. Data Preprocessing
Handle Missing Values: Identify and manage missing data through imputation or removal.
Feature Selection: Choose a single predictor variable based on correlation analysis.

3. Model Building
Split the Data: Divide the data into training and test sets.
Train the Model: Use the training data to fit a simple linear regression model.

4. Model Evaluation
Make Predictions: Apply the model to the test data.
Evaluate Performance: Calculate performance metrics such as Mean Squared Error (MSE) and R-squared.

5. Visualization
Plot the Regression Line: Visualize the relationship between the predictor and the target variable along with the regression line.
Multiple Linear Regression

Multiple Linear Regression: - 
1. Data Collection and Exploration
Load the Data: Import the dataset with housing prices and multiple features.
Explore the Data: Conduct exploratory data analysis to understand relationships and distributions.

2. Data Preprocessing
a) Handle Missing Values: Address missing data through appropriate techniques.
b)Feature Selection: Select multiple predictor variables based on correlation and domain knowledge.
c)Feature Engineering: Create new features if necessary to improve model performance.
d)Encode Categorical Variables: Convert categorical variables into a numerical format.

3. Model Building
Split the Data: Split the dataset into training and test sets.
Train the Model: Fit a multiple linear regression model using the training data.

4. Model Evaluation
Make Predictions: Use the trained model to predict housing prices on the test data.
Evaluate Performance: Assess the model using metrics such as MSE, R-squared, and Adjusted R-squared.

5. Visualization and Interpretation
Plot Residuals: Visualize residuals to check for patterns and heteroscedasticity.
Interpret Coefficients: Understand the impact of each predictor on the target variable.
## Model Evaluation Metrics
R-squared (R²) :

++ For Simple Linear Regression: R-squared measures the proportion of the variance in the dependent variable that is predictable from the independent variable. An R² value closer to 1 indicates a better fit of the model.

++ For Multiple Linear Regression: In this context, R-squared represents the proportion of the variance in the dependent variable explained by all the predictors together. Adjusted R² is often used to account for the number of predictors and provide a more accurate measure of model performance.

Mean Squared Error (MSE) :

++ Simple Linear Regression: MSE measures the average of the squares of the errors, that is, the average squared difference between the observed actual outcomes and the predictions made by the model. A lower MSE indicates a better fit.

++ Multiple Linear Regression: Similar to simple linear regression, MSE in multiple linear regression evaluates the average squared difference between the actual and predicted values. It helps in assessing the accuracy of the predictions made by the model.
## Requirements
Libraries: List of Python libraries used such as pandas, numpy, matplotlib, seaborn, and sklearn.
## References
Datasets: Source of the California housing dataset.

Further Reading: Links to relevant literature and documentation on linear regression in Scikit learn library.

link: 
https://scikit-learn.org/stable/supervised_learning.html
## Conclusion

# Interpretation in Simple Linear Regression:
- A higher R² value indicates that a larger portion of the variance in the housing prices can be explained by the median income.
  For example, an R² value of 0.47 means that only 47% of the variability in house prices is explained by the median income.
- MSE should always be minimal. This indicates that the models predictions are not closer to the actual value

# Interpretation of metrics in Multi Linear Regression :

- R² Score: Indicates the proportion of variance in house prices explained by all features in the model is only 64%.
 - Similarly higher MSE_err denotes- 
RMSE= MSE ≈ 4,751,862,443.572282 ≈ Sqrt. of 4,751,862,443.572282 ≈ 68,933. So, on average, the predictions are off by about $68,933.
