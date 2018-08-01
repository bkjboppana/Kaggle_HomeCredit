# Home Credit Deafult Risk Kaggle competition
### There are several Datasets in Kaggle for approaching this problem. application_train and application_test files are used in this project
### Steps implemented to predict probability of client repaying lone or not
 * Figured out top 25 and bottom 25 correlated features
 * Used exploratory data analysis to view distributions of data with Target 0 and 1
 * Created a function to pre-process the data. Filling missing values, dropping columns and converting categorical variables to numeric
 * Modeled the data to calculate probabilities using Logistic Regression and LightGBM
 * Light GBM has 2% more AUC than Logistic regression abd submitted results from Light GBM
