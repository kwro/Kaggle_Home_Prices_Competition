# Housing Prices Competition for Kaggle Learn Users

The goal is to predict sale price of house based on Kaggle data: https://www.kaggle.com/c/home-data-for-ml-course/overview/

## Executive summary
1. Initially the data set consists of 80 features. 
2. 5 features were removed due to high share of nulls (more than 50%)
3. A few categorical features were coded in number format, so format changing to string was needed.
5. Many of remaining features had distribution with dominance of particular label, for example the lowest value of YearRemodAdd (year of remodelling) was 1950, while there were older houses in the dataset. Such variables were removed from the analysis.
6. The otuliers were removed from train set.
7. Next the initial models were trained. Algorithms used in this example: Random Forest Regressor, SVR, Bayesian Ridge, Liner Regression. The scoring statistic was RMSE.
8.Liner Regression archived higher score calculated as average result of cross-validation on the train set: RMSE =  17 750
