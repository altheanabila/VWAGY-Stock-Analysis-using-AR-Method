# VWAGY-Stock-Analysis-using-AR-Method

This time, I have made an Auto regressive model of Volkswagen group stock ($VWAGY). 

1. First of all we need to download the csv data from yahoo finance and extracting the data into panda data frames.

[VWAGY](https://github.com/altheanabila/VWAGY-Stock-Analysis-using-AR-Method/commit/038f24a77f80390c6f75e29a6dd85b068b697dc8)

![Test image1](https://github.com/altheanabila/VWAGY-Stock-Analysis-using-AR-Method/commit/739298ae33edef8440d834a6e6e588744512f457)

2. We use Autoregressive model to obtain the forecasted values

![Test image1](


3. and then we need to create residual values on forecasted values, and define test_y prediction


4. we use AR model to create a model in residual values, and to create future forecasted residual values

`from statsmodels.tsa.ar_model import AR`
`model = AR(train)`
`model_fit = model.fit()`
`model_fit.k_ar`
`model_fit.params`




5. then we used forecasted residual values to be added to predictive residual model


6. Visualize the result

