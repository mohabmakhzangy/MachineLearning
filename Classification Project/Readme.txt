Team Members:
Mostafa Shehab 46-0408
Mohab Yasser 46-0660
Wesam Aymen 46-5313

Data Set Used : 2010_Accidents_UK.csv
--------------------------------------------------------



Files Description:
1. Pre-processing.ipynb    -------->  Pre-processing of the dataset
2 mydata.csv    --------> Data set after processing it (Result from above step)
3. Diagnostics and Classifiers.ipynb   ---------> 2. Use all Diagnostics techniques explained && Compare between the performance of ALL the following classifiers:
  KNN / Naive Bayes / Logistic Regression / Neural Networks



--------------------------------------------------------


Part 1 : Pre-processing the data
  Removing data (Columns) that doesn't contribute substantial information to the Model.
  Detecting and handling missing entries in the dataset
  Detecting and Removing Duplicate entries
  Detecting and handling Outliers using IQR and Z-Score
  Removing "First_Road_number" column as it had 3000+ different values
  Normalizing "Speed_limit" column to ensure that all variables are on the same scale
  Exporting the processed dataset to be used in Diagnostics and Classifiers
  
  
  Part 2 & 3 :Diagnostics and Classifiers techniques:
Comparing the performance of different classifier techniques is crucial to identify the most suitable approach for a given problem. The performance of classifiers can be evaluated using various metrics, with accuracy being one of the commonly used measures. Accuracy calculates the percentage of correctly classified instances out of the total number of instances.We will use diagonstics techniques to improve overall performance
