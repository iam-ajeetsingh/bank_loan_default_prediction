# German Bank Loan Default Prediction Project:
- This project aims to build a machine learning model for predicting whether a customer will default on a loan based on historical data from German Loan dataset.
-  The project follows a structured approach, including data exploration, visualization, and the application of various machine learning models.

## Project Organization - 
The project is organized into the following 3 parts:

### (PART-1.) Data Cleaning:
- Read and understand the dataset's contents and column descriptions.
- Exploring the data using descriptive statistics on numerical and categorical data
- Checking the data for missing values and null values.
- Performing data cleaning.



### (PART-2.) Data Visualization:
- Visualize the distribution of numerical features using histograms, density plots, and boxplots.
- Explore correlations between numerical features using a pairplot and heatmap.
- Analyze categorical features using count plots with and without 'default' as the hue.



### (PART-3.) Building Machine Learning Models:
- Identify the target and predictor variables.
- Categorization of the features into numerical and categorical variables
- Encoding the categorical features using one-hot encoding and ordinal encoding
- Encoding the target variable as 0 for non-default and 1 for default
- Spliting the dataset into Train-Test split of data
- Scaling the numerical features using Standard Scaler
- Creation of Various Machine Learnng Models.
- Comparison of all ML models and Selection of Best model.
- Further optimization of performance of the selected model.formance.


## Directory Structure:

It Contains Jupyter notebooks for each project step.
- Part1_Data_Cleaning.ipynb: Data exploration and cleaning.
- Part2_Data_Visualization.ipynb: Data visualization.
- Part3_Machine_Learning_Models.ipynb: building various machine learning models.
- German_bank.csv: Original dataset.
- Part1_Output.csv: Cleaned dataset.

It also contains the HTML files for all 3 parts of the project. 



## Necessary Python Libraries - 
The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter


## Conclusion:
- The project demonstrates a comprehensive approach to building and evaluating machine learning models for loan default prediction.
- By following the given steps in 3 notebooks of the Project, one can gain insights into the data, model performance, and
  strategies for improving recall in imbalanced classification scenarios.
