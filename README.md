# dsc-linear-regression-checkpoint-master
In this modeling section, we will adopt an inferential modeling approach using StatsModels. Our primary objective is to create a robust model that explains the variance in the SalePrice target variable, primarily assessed through the R-squared metric. We focus on R-squared as our primary evaluation metric, emphasizing the explained variance rather than metrics like Root Mean Squared Error (RMSE) or other user-friendly measures. Additionally, we will not implement a train-test split in this context.

The modeling process will include the creation of two distinct models: a simple linear regression model and a multiple linear regression model. We will meticulously analyze the model summaries to extract meaningful insights and draw relevant conclusions.

Within this modeling framework, there are two key aspects that we will focus on when interpreting the model summaries:

Model Metrics: We will evaluate metrics such as R-squared, which quantifies the proportion of variance in the target variable (SalePrice) that the model explains. Higher R-squared values indicate a better fit to the data. We will rely on this metric to gauge the performance of our models.

Model Parameters: This aspect involves understanding the parameters of the model, which include the intercept and coefficients. The intercept represents the predicted value of SalePrice when all predictor variables are zero, while coefficients (also known as slopes) provide insights into how each feature (independent variable) contributes to the prediction of SalePrice.

Our ultimate goal is to create models that effectively explain the variation in home prices (SalePrice) and provide actionable insights into the relationships between the features and the target variable. By analyzing model metrics and parameters, we can make informed decisions about the importance of features and the overall performance of our models.
