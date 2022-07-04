# Disease-Progession-Prediction

Course work completed in Data Mining Class at Carnegie Mellon University


In this project I will be predicting "Disease Progression" for different diabetic patients in the dataset. The work flow consists of Data Processing, Linear regression &amp; Multiple linear regression models, Polynomial Regression with scikit-learn Ridge and Lasso Regression Cross Validation. We use these different regression to see which best fits our model and is able to give the most accurate results. 

Diabetes dataset
----------------

Ten baseline variables, age, sex, body mass index, average blood
pressure, and six blood serum measurements were obtained for each of n =
442 diabetes patients, as well as the response of interest, a
quantitative measure of disease progression one year after baseline.

**Data Set Characteristics:**

  :Number of Instances: 442

  :Number of Attributes: First 10 columns are numeric predictive values

  :Target: Column 11 is a quantitative measure of disease progression one year after baseline

  :Attribute Information:
      - age     age in years
      - sex
      - bmi     body mass index
      - bp      average blood pressure
      - s1      tc, T-Cells (a type of white blood cells)
      - s2      ldl, low-density lipoproteins
      - s3      hdl, high-density lipoproteins
      - s4      tch, thyroid stimulating hormone
      - s5      ltg, lamotrigine
      - s6      glu, blood sugar level

Note: Each of these 10 feature variables have been mean centered and scaled by the standard deviation times `n_samples` (i.e. the sum of squares of each column totals 1).

Source URL:
https://www4.stat.ncsu.edu/~boos/var.select/diabetes.html


Libraries Used:
numpy , pandas , seaborn , matplotlib , plotly.express , statsmodels.api , sklearn
