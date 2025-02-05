This project aims to predict the youtube views with the following features,

1. Shares	
2. Comments added	
3. Likes (vs. dislikes) (%)	
4. Average view duration	
5. Subscribers	
6. Impressions click-through rate (%)

The models I chose are,

1. Linear Regression, to handle linear relationships between the features and the views
2. Random Forest Regressor, for handling any non-linear relationship between the features and the views predictions
3. XGB Regressor for handing both linear and non-linear relationships between dependent features and independent features

The measurement metrics I used for performance evaluation are mean_squared_error and r2_score. With those metrics, the model with least mean_squared_error and high r2_score will be the most preferred model. In that case, Random Forest is preferred out of the three models. MLFlow is incorporated for tracking the model performance, saving the artifacts and loading the model for inferencing the test data.

![alt text](<Screenshot 2025-02-05 134855.png>)

