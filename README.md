# Mini-Project-1-Product-Demand-Prediction

1. The aim
The aim of this project is to predict how many units of a product will be sold given it initial price and the price after discount.

3. How to run
To run the code, first download the notebook and the data. Then you can run it locally if you have Jupyter installed, or upload it to google colab,
for which you will need google account.

5. Libraries used  
Pandas is used to open the dataset and to get some statistical information.
matplotlib is used to visualize the relationships between features.
The train_test_split from scikit-learn is used to divide the data into training and test parts 
I used decision tree regressor from scikit-learn library to build the regression model. 
For evaluation I used the model.score function which is the same r2 score and mean squared error.  

6. The result
Decision tree had r2 score of 0.43594810058559585 and mean squared error of 1845.8316721211518 on test data.

