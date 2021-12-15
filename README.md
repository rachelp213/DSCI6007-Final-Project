# PROJECT TITLE
# NETFLIX MOVIE RECOMMENDATION SYSTEM 
## INTRODUCTION:
The purpose of this project was to create a Netflix movie recommendation system utilizing the Netflix dataset that contained 3.5 million movie ratings from its users. In doing so, Python’s interface PySpark was utilized to first analyze the Netflix data and determine what the best approach would be to collaborative filtering. 

## Methods & Approach
The first step was to conduct an analysis on the Netflix data using Pyspark. Some initial insights into the data were gathered. There were 28,978 distinct users who had rated movies in the training dataset. There were a total of 1,821 distinct movies that had been rated by people in the training dataset and a total of 17,769 total movies available for rating in the movies.txt file, which means there are a lot of movies that were not rated by people in the training data. 

The approach taken to produce the model was the alternating least squares method (ALS). It is a matrix factorization algorithm that uses Alternating Least Squares with weighted-lambda-regularization (ALS-WR). It factors the user to item matrix A into the user-to-feature matrix U and the item-to feature matrix M and runs the ALS algorithm in a parallel fashion. It was optimized using different parameter settings for the rank and the best model was chosen. The model has a Root Mean Square Error (RSME) of 0.87 and a Mean Squared Error (MSE) of 0.69. So overall the predicting ratings were pretty accurate and able to predict within one star the majority of the time. 

## Results

The optimized model had a Root Mean Square Error (RSME) of 0.87 and a Mean Squared Error (MSE) of 0.69. So overall the predicting ratings were pretty accurate and able to predict within one star the majority of the time. 
