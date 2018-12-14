# Housing-Model

  This is a draft of a Jupyter notebook working on a knowlege based competition hosted by [Kaggle](https://www.kaggle.com)
pridict housing prices based of a number numerical and categorical features. I walk through some the exploratory data anlysis 
(EDA) used to make decisions on feature transformations, imputation, and deletion using a combination of statistical and 
graphical techniques. 

  Upon preparing the data for machine learning stage I trained four regression models to predict the house price (or more 
  specifically the logarithm of the house price): 
  - Three regularized regression models
    - Lasso (L1 penalized linear regressor)
    - Ridge (L2 penalized linear regressor)
    - Elastic Net (combo of L1 and L2 penalized regressor)
  - Gradient Boosting Regressor 
I then created a custom ensemble regression model which averaged the price predictions of each model to attain a model which then
outperformed any sub-model. As a result I obtained a result which placed me in the top 7% of kaggle competitors for this
competition.
