# Average-Rainfall-Prediction
Rainfall Prediction is the application of science and technology to predict the amount of rainfall over a region. Different factors such as the month, year, period, temperature, humidity , etc. affects the rainfall in a region

 ## Dataset
 
The dataset that is being used is the Average Rainfall in UK(2010-2019) from kaggle.
This data consists of year, month and the period of UK for the 10 years. Prediction has been made looking at these factors.

![image](https://user-images.githubusercontent.com/54113500/125158488-2eff7a80-e18f-11eb-89cf-bbd8ba559520.png)

Our dataset consist of 4 columns- Year, Type of peroid, Period(month) and Avg rainfall. The average rainfall is the rainfall over the peroid in millimeters. There are two categorical columns - Type of peroid and Peroid; which is encoded into numeric using the labelencoder() for preprocessing. 

## Algorithm 

![image](https://user-images.githubusercontent.com/54113500/125158683-47bc6000-e190-11eb-9deb-e68f49ba4c5d.png)

The algorithm used for the prediction is ****'Random Forest'****. Since our data is labelled, we have used the supervised algorithm.****The Random forest is a supervised algorithm which uses multiple decision trees, and chooses the optimum result by selecting the majority****.Since we are working on multiple decision trees there is a chance of less over-fitting. Its accuracy is high and we can estimate missing values. But, one of the biggest advantages of random forest is its versatility. It can be used for both regression and classification tasks

## Metrics

![image](https://user-images.githubusercontent.com/54113500/125158790-f95b9100-e190-11eb-838e-da75fe56b2f7.png)

Metrics are used to analyze the model. Its show how good is our model's perfomance. Three metrics Mean Absolute Error, Mean Squared Error and Root Mean Squared Error have been used in this task. 
****Mean Absolute Error (MAE)**** measures how far predicted values are away from observed values. It sums the absolute value of the residual and divides by the number of observations.
****Mean Squared Error (MSE)**** tells you how close a regression line is to a set of points. 
****Root Mean Square Error (RMSE)**** is a standard way to measure the error of a model in predicting quantitative data.
