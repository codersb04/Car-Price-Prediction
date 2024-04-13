# Car-Price-Prediction
## Task:
Build a Machine Learning model to predict the prices of the car.</br> This comes under **Supervised learning** as we have provided labelled data. As in this problem, we need to predict the prices to use regression models to achieve the task. We have used 3 different regression models: Linear Regression, Lasso Regression and XGBoost Regression.

## Dataset:
The dataset contains information about the used car. The dataset contains 301 records of different cars with 9 features each about them. The features are:</br>
. name</br>
. year</br>
. selling_price</br>
. km_driven</br>
. fuel</br>
. seller_type</br>
. transmission</br>
. Owner</br></br>
Source: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv

## Steps Involved:
### Import Dependencies
Libraries needed to achieve the result are: </br>
. pandas</br>
. numpy</br>
. matplotlib.pyplot</br>
. seaborn</br>
. LinearRegression from sklean.linear_model</br>
. Lasso from sklearn.linear_model</br>
. train_test_split from sklearn.model_selection</br>
. xgboost</br>
. metrics from sklearn</br>
### Data Collection and Processing
. Use read_csv function from pandas to import the dataset.</br>
. Use the function such as shape, describe, head, and info to know more about the data set</br>
. Check for the missing value using the isnull function</br>
. Replace all the categorical data which are in the text form with numeric form.</br>
. Finally, splitting the dataset into features and labels. The label will contain the column **Selling Price** and the feature will contain the rest of the column except Car Name and Selling Price.
### Model Training and Evaluation 
. Split the dataset into training and test data. We have taken 10% of the for test purposes and the rest 90% for the training.</br>
. We have used 3 Different algorithms to predict the result. </br>
. Prediction and Evaluation are being carried out for both trained and test data.</br>
. **Linear Regression**: </br>
The R Square Error score for trained data is 0.8799451660493705 </br>
R square error square for test data is:  0.836576671502687</br>
. **Lasso Regression**: </br>
R square error square for trained data is:  0.8427856123435794</br>
R square error square for test data:  0.9739216554116775 </br>
. **XGBoost Regression**:</br>
R Square error score for Trained data:  0.9999882347921428</br>
R Square error score for Test data:  0.9717000722567458</br>

### Build a predictive system
. Take some random data from the X dataset.</br>
. Transform it to numpy array then reshape it into a 2D array.</br>
. Feed it to the created model.</br></br></br></br>

Reference: Project 7. Car Price Prediction using Machine Learning with Python | Machine Learning Projects, Siddhardhan, https://www.youtube.com/watch?v=L3OtLaCbJC8&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&index=9


