# Employee Attrition Control using Supervised Machine Learning (Logistic Regression) 

I. Aim of the Project
------
The Aim of the project is to apply data science techniques using supervised machine learning approach with Logistic regression model to predict the likelihood that an employee will either leave or stay in a company.

II. Dataset description
-----------------
The dataset contains the employee details and information regarding their work history with the company. The dataset contains 11 attributes; 9 attributes have numeric values and two attributes have string values

III. Methodology
------------------
The methodology above is implemented programmatically with python language using three libraries namely; Numpy, Pandas, and SkLearn. Sklearn is essential for 
Machine learning Model. The machine learning model to be used for the problem statement is Logistic Regression Model.
___
Modelling Techniques used
-------
1. #Feature transformation 1: The feature transformation is applied using Lambda function on two string columns (feature) i.e department and salary column. Both features will be transformed to have numeric values. Feature transformation technique was applied to boost the model prediction performance.

1. #Feature transformation 2:The feature transformation is applied using Lambda function on two columns (satisfaction_level & last_evaluation). Both features had floating point values therefore the features were transformed to percentage values. The columns were transformed and two new columns was created to replace both features. 

IV. Results / Conclusion
--------------------
The Logistic model was fit using the ordinary least squares (OLS) method to estimate accuracy score of finding the unknown parameters using the test data. The accuracy score was 0.92
