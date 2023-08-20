# Mini-Project-1-Product-Demand-Prediction

1. The aim of the project.
The aim of this project is to predict how many units of a product will be sold given it initial price and the price after discount.

2. How to run and test the code.
To run the code, first download the notebook and the data. Then you can run it locally if you have Jupyter installed, or upload it to google colab,
for which you will need google account.

3. Libraries used.  
Pandas is used to open the dataset and to get some statistical information.
matplotlib is used to visualize the relationships between features.
The train_test_split from scikit-learn is used to divide the data into training and test parts. 
I used decision tree regressor from scikit-learn library to build the regression model. 
For evaluation I used the model.score function which is the same r2 score and mean squared error.  

4. The dataset contains 'ID', 'Store ID', "Base Price', and 'Total Price' features from which only 'Base Price' and 'Total Price' are used for prediction.
The label is 'Units Sold'.

5. Data visualization
![total price - units sold](https://github.com/SargisArzumanyan/Mini-Project-1-Product-Demand-Prediction/assets/82839525/1c90542a-6ae3-41a2-b9fb-c82ab5383a28)

6. The result of the model.
Decision tree had r2 score of 0.43594810058559585 and mean squared error of 1845.8316721211518 on test data.

