# Analysis and prediction of house prices in Poland using XGBRegressor.

In this project, regression was applied to data related to housing prices in Poland. The first step was to clean the data, remove outliers using z-score, and perform EDA. Next, several models were tested to select the one model to focus on. The chosen model was the XGBRegressor for which I created a pipeline with hyperparameter tuning. Additionally, I created an Actual vs Predicted Price plot and a Feature Importance plot to visualize and interpret the results.

The project successfully applied various techniques to preprocess and clean the data, tested multiple models, and fine-tuned the chosen model using a pipeline with hyperparameter tuning. The Actual vs Predicted Price plot and Feature Importance plot also provided valuable insights into the model's performance and feature importance.


Data comes from the kaggle website and can be found at 
https://www.kaggle.com/datasets/dawidcegielski/house-prices-in-poland

Description:

1. address - Full addres
2. city - Warszawa (Warsaw), Kraków (Cracow), Poznań (Poznan).
3. floor - The number of the floor where the apartment is located
4. id - id
5. latitude - latitude
6. longitude - longitude
7. price - Price of apartment in PLN [TARGET]
8. rooms - Number of rooms in the apartment
9. sq - Number of square meters of the apartment
10. year - Year of the building / apartment
