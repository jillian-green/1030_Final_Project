# Olympic Medal Prediction

<!-- #region -->


This project explores the Olympic Games from Athens 1896 to Rio 2016. Winning olympic medals is important for a country because it promotes job opportunities, increases investments (sponsorships, tourism, revenue) and creates a sense of national pride. In this report we want to predict the number of medals a country will win. 

A brief overview of the python code. Our target variable is “Medal_Won_Corrected”. We created the “Medal_Won_Corrected” target by accounting for single and team events (only counting a team win once rather than per athlete). Because we are trying to predict the number of medals, this is a regression problem. After manipulating and cleaning the data, the final dataset used is 20,799 data points with columns Team, Population, Total_Athletes, Female_Athletes, Male_Athletes, Year, Season, and Sport. We split this data using TimeSeriesSplit, and processes using OneHotEncoder and StandardScaler. GridSearchCV helps us fit the data and find the best parameters and test scores per model. Finally, we explore the model results and dive deeper into feature impact.

This project was for a data science course at Brown University.

Python Version: 3.7

Other Package Versions:
  - matplotlib=3.2.2
  - pandas=1.0.5
  - scikit-learn=0.23.1
  - numpy=1.18.5
  - py-xgboost=1.1.1
  - shap=0.35.0
  - jupyter_client
  - jupyter_core
  - jupyterlab
  - jupyterlab_server
  - jupytext
  - rise
  
See data1030.yml file as well.

Data: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results

<!-- #endregion -->

```python

```
