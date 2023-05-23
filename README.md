# Santander-value-prediction

The aim of this project is to predict value of customer transaction from 4991 variables and 4459 transaction records. Random Forest, LGBM, XGBoost and Catboost regressors are used in this project. Among the 4 models, XGBoost model performs the best with lowest Root Mean Squared Logarithmic Error (RMSLE) of 1.43574. The top 10 features that affect the amount of customer transaction is `2c136905e`, `896d1c52d`, `186b87c05`, `82f715995`, `e78e3031b`, `2288333b4`, `f190486d6`, `715fa74a4`, `7ab926448` and `62e59a501`.   

## References
* Santander value prediction competition [Kaggle](https://www.kaggle.com/competitions/santander-value-prediction-challenge/data?select=train.csv)
* Useful kickstarter Notebook [Paul Rohan](https://www.kaggle.com/code/paulrohan2020/tutorial-lightgbm-xgboost-catboost-top-11)
