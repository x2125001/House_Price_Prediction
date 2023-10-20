# House_Price_Prediction
In this project, i have explored the data set of housing price available on Kaggle competition. The data has 79 trainning features and some of the values are missing. The goal is to predict the housing price labeld as 'SalePrice'. Therefore, it is a regression problem. 
Seaborn libaray is used to explore those features and their relationship with the target variable, following which four machine learning models implemened by sklearn libarary are built. These models are linear regression as the baseline model. Ridge regression is used for correlated features. More complex tree-based models of gradient boosting regressor and random forest are also built. 

Overal, we found that the gradient boosting method has the best performance. 
