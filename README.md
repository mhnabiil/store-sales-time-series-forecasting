# store-sales-time-series-forecasting
predict sales for the thousands of product families sold at favorita stores located in ecuador (kaggle competition). The training data includes dates, store and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models.

- in this notebook, sales prediction uses the commonly used regression model (rf) and gradient boosting algorithm (Xgboost, LightGBM, CatBoost)

The evaluation metric for this competition is Root Mean Squared Logarithmic Error:
![image](https://user-images.githubusercontent.com/70517346/211182517-3d0748ce-1dd5-41b1-9842-ec5b95eb7213.png)

- The best forecasting model obtained is the gradient boosting algorithm model, catboost with an RMSLE value of 0.22 and a model score of 97.80%.
