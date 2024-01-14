# KNN Classification
***

### Projects:

(i) Predicting the purchase of Iphones by male and females based on their age and salary. 

(ii) Prediction of Bangalore house price depnding upon the various parameters including area of house, house location, number of rooms, bathrooms, balconies etc

### Objectives:

Exploring Insights/Inferences by performing EDA on the given data. Relevant graphs were plotted to get some insights on data using seaborn package. Model fitting via KNN Classification by Importing sklearn package. Selecting the best fitted model via python programming.
***

### Python Libraries Used:
   * Pandas
   * Numpy
   * Matplotlib
   * Seaborn
   * Scikit learn
   * Joblib

***

### Methodology:
 1. Data copying and cleaning:
    * Read the csv file
    * copy the data
    * check for null values and other informations
 
 2. Exploratory Data Analysis:
    * Conduct all the necessary EDA using various graphs on the dataset
    * interpret the graphs
    * check for outliers and correlation among the coloumns
    * perform one hot encoding in case of categorical columns

 3. Sampling of data:
    * Divide the data into x and y
    * standardize the data using StandardScaler lib
    * import test_train_split from sklearn.model_selection
    * divide the data into training and testing


  4. Modelling of data:
     * import KNeighborsClassifier and initialize it
     * fit the model
     * predict the model

  5. Model validation (Error Calculation):
     * From sklearn.metris import accuracy_score, confusion_matrix
     * check the accuracy of the model

  6. Save the Model:
     * import joblib
     * save the model

  ***
  ## Iphone Purchase data Probelm: 
  
  *File name: Iphone-Purchase-data-files*
  
  #### EDA Inferences:
  * The number of females and males in the dataset are 204 and 196, respectively.
  * Out of 204 females, 77 purchased Iphones.
  * Out of 196 males, 66 purchased Iphones.
  * The data is normally distributed in all the cases. The skewness is calculted to be **0.5 and 0.23** for salary and age, respectively.
  * Salary and Age of the customers are correalted with the Iphone purchase.
  * The correlation of salary and age with the Iphone purchase is **62 and 36%**, repectively.
  * There are no outliers present in the dataset.

 
  #### KNN Model Results:
  The accuracy of the model is came out to be:
  
  |K value | Accuracy score|
  
  |k=3 | 0.85      |
  
  |k=20 | 0.9      |
  
  
**For K=20, the model shows the highest accuracy and is the best fitted model.**
***



       
      
     
     
     



