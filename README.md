# About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on one of the most prevalent chronic diseases, Diabetes. 

# Problem Definition
Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. Diabetes also raises the risk of a number of problems, including kidney damage and cardiovascular disease. Early diabetes detection can facilitate efficient treatment, underscoring the significance of understanding the variables that are highly correlated with diabetes.
"What are the most important factors in predicting whether a person has diabetes?"

# Libraries and Models
* Numpy
* Pandas
* Matplotlib
* Seaborn
* SMOTE (IMBLearn)
* Pearson's Correlation Matrix (Numerical Varaibles)
* Cramer's V Correlation Matrix (Categorical Variables)
* Sklearn
* Train Test
* Standard Scalar
* Decision Tree
* Random Forest
* Naive Bayes
* Neural Network
* OneHotEncoder
* LabelEncoder

# Setup and Process
**1. Data Collection**
   
Dataset (Kaggle): https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

**2. Data Cleaning and Preparation**
* Renamed binary data
* Splitted dataset into 80% for training and 20% for testing
* Normalisation not required since the dataset from Kaggle has been normalised
  
**3. Exploratory Data Analysis**
  
Univariate
* Explored the distribution of each variables

Multivariate
* Explored relationship of each variables vs Diabetes
Removed Outliers Based on NIL on smoking history and NIL on gender

**4. Model Training**
   
The following supervised classification machine learning models were trained on the train dataset:
* Logistic Regression
* Random Forest
* Naive Bayes
* Neural Network

**5. Model Evaluation on Test Dataset**
   
The following metrics were used to evaluate the models
* Classification Accuracy
* True Positive Rate
* True Negative Rate
* False Positive Rate
* False Negative Rate
The most important variables in each models were extracted using Feature Importance function

**6. Model Re-training**
   
The models were retrained using only the most important variables to reduce overfitting issues

**7. Model Re-evaluation on Test Dataset**
   
The same metrics were used to evaluate the performace of the new models

**8. Insights and Conclusion**

# Contributors
* Joshua Tan
* Harith
* Rohan
