# Boston-housing-price-prediction

This project is baed on the Boston housing data set. It contains details of 506 houses in Boston city. 

The aim of this project was to try different Machine Learning models and see which model has the highest accuracy. I have tried the following Machine Learning Models:
- 


Our aim of this project is to try differnt Machine Learning models and see which model 
- Linear Regression
- Decision Trees
- Random Forest
- Ada Boost
- XGBoost
- KNN
- SVM

The project consist of the following steps:

- Reading the data in python
- Defining the problem statement
- Identifying the Target variable
- Looking at the distribution of Target variable
- Basic Data exploration
- Rejecting useless columns
- Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)
- Feature Selection based on data distribution
- Outlier treatment
- Missing Values treatment
- Visual correlation analysis
- Statistical correlation analysis (Feature Selection)
- Converting data to numeric for ML
- Sampling and K-fold cross validation
- Trying multiple Regression algorithms
- Selecting the best Model
- Deploying the best model in production


**Multiple Linear Regression**
LinearRegression()
R2 Value: 0.6850018441906278

 Model Validation and Accuracy Calculations 
      LSTAT        RM   PTRATIO  price  Predictedprice
0  0.201711  0.547040  0.425532   23.6            27.0
1  0.049669  0.612569  0.531915   32.4            31.0
2  0.450883  0.464074  0.797872   13.6            16.0
3  0.104581  0.479785  0.702128   22.8            25.0
4  0.428808  0.524238  0.808511   16.1            18.0
Mean Accuracy on test data: 81.04132004578314
Median Accuracy on test data: 87.30561189993239

Accuracy values for 10-fold Cross Validation:
 [88.37192572 89.23998008 85.56651342 82.81688229 86.22931798 88.02359532
 84.16099243 48.536584   53.91670842 85.22065221]

Final Average Accuracy of the model: 79.21
