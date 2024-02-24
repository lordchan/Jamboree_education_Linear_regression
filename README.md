# Jamboree_education_Linear_regression
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

# Project Overview:

## Aim: Analyze factors affecting Ivy League admissions for Indian students.
Dataset: jamboree_admission.csv with columns for GRE scores, TOEFL scores, university rating, SOP, LOR strength, GPA, research experience, and admission chances.
Data Cleaning and Preprocessing:

1. Removed 'Serial No.' as it's irrelevant for modeling.
Checked for and treated missing values.
Identified and treated outliers to normalize data distribution.
Engineered features to enhance model's predictive capabilities.
Exploratory Data Analysis (EDA):

2. Utilized distribution plots, box plots, and scatter plots for univariate and bivariate analysis.
Analyzed relationships between GRE scores, TOEFL scores, GPA, and admission chances.
Examined university rating, research experience, SOP, and LOR strength impacts.
Model Building:

3. Employed linear regression, Ridge, and Lasso regression using Statsmodels and Scikit-learn.
Displayed model coefficients to understand predictor variable significance.
Conducted Recursive Feature Elimination (RFE) to identify key predictors.
Testing Linear Regression Assumptions:

4. Multicollinearity assessed via VIF scores, ensuring no variable exceeded a VIF of 5.
Checked residuals for zero mean, linearity, homoscedasticity, and normal distribution.
Model Performance Evaluation:

5. Evaluated using MAE, RMSE, R², and adjusted R² metrics.
Compared train and test performance to assess model generalizability.
Insights and Recommendations:

6. Identified GRE scores, CGPA, and LOR strength as significant predictors of admission chances.
Suggested enhancing the predictive feature by focusing on these key areas.
Recommended further model improvements and data sources exploration for more accurate predictions.
Conclusion:

The project provided Jamboree with valuable insights into graduate admission factors, aiding in the refinement of their admission chance feature.
Offered actionable recommendations for students aiming for Ivy League colleges, emphasizing the importance of academic and recommendation strengths.
