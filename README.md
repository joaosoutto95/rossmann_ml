
![ddd](https://user-images.githubusercontent.com/81658694/159159879-7b6c0600-840d-45bb-9e3f-e842b78d2d2a.png)

# Drug store sales prediction using XGBoost Regressor

( Data from a Kaggle competition - https://www.kaggle.com/c/rossmann-store-sales )

The objective of the project is to discover business insights based on public market data and use the findings in order to choose and train a prediction model. In this case, the sector evaluated is drug store, in which the company seeks to predict the turnover in the next 6 weeks. It is expected as a final product, a report with the performance of the business and the performance of the machine learning model tuned.

## Overview of the project results:

After choosing through Boruta the main features of the model, comparing the errors (MAE, MAPE, RMSE) of six different maching learning regressors, cross-validating the chosen model and finally after tunning it, the results obtained were:

![results_4](https://user-images.githubusercontent.com/81658694/159250618-7634bfd8-1781-4dd3-84da-bae4d96ca7e0.PNG)

In the image above, is possible to see the errors of the XGBoost Regressor model, it got an 4% mean absolute percentual error.
In the image bellow, the upper graph shows the predictability of the model (lineplot in blue) and the real sales (lineplot in orange), the other graphs shows
the distribution of the error, error rate through predicted time, error relative to the sales prediction and   

![results_1](https://user-images.githubusercontent.com/81658694/159250602-10249a6f-3ddc-4bba-9d22-468bdede83af.png)
![results_2](https://user-images.githubusercontent.com/81658694/159250608-5a9b7ab7-649d-4b37-9958-f181ca6c721f.PNG)
![results_3](https://user-images.githubusercontent.com/81658694/159250612-72b998f3-826f-4c19-bd46-2abfd49cd582.png)

