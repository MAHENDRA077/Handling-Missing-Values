Handling Missing Values is of the crucial steps in Data Preprocessing.

There are three ways to handle Missing Values:

    1. Ignoring the Null Values: Simply Drop the null value rows in the Data.
    
    2. Imputation: Filling the Misiing values from the known part of the Data. 
    
    3. An Extension To Imputation: Making the Rows with missing values unique.
    
Imputers are of two types:

    1.Univariate Imputer : Uses a Single column to fill the missing Data.
  
     SimpleImputer(Strategy='mean')
     Strategy can be Mean,Median,Most Frequent, Constant (Fill value). 
     Mean,Medain helps when working with numerical data. Most frequent used for Categorical Data.
          
    2.Multivariate Imputer: Estimates values to impute for each column with missing values from all the other features.
    
    IterativeImputer: Passes Regressors as estimators for prediction missing values.
    
    KNN Imputer: Uses nearest Samples to fill the missing values of the data.
    
 Extension to Imputation:
    
    Filling missing data, makes missing part data highly valued (or) priortized beacuse mostly we are using Measure's of Central Tendancy
    (Or) other data features which uses regressors, nearest_neghibours. We can't rely on that type of data. Solution is the we keep track
    of record whether it is a missing value or not.
    
    
