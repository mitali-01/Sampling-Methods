# Sampling_Assignment_UCS654
assignment based on sampling methods in machine learning


Step1: Download dataset from https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv

Step2: Convert dataset into balanced class dataset - for this step, use imbalanced_learn library (imblearn). There are multiple ways to resample data. Here, I have used a combination of random oversampling and random undersampling.

Step3: Create five samples - Apply five different sampling techniques.
The five sampling methods used in this code are:

  (i) Simple Random Sampling: sample size = floor((Z^2*p*(1-p))/(e^2))

  (ii) Systematic Sampling: step_size=8
  
  (iii) Stratified Sampling: sample size = floor((Z*2*p*(1-p))/(e^2*S))
  
  (iv) Cluster Sampling: sample size = floor((Z*2*p*(1-p))/(e^2*C))
  
  (v) Conveniece Sampling: 50 from head, 50 from tail
  
  
  Step4: Apply the different sampling techniques on five different ML models.
  The five ML models used are:
  
   (i) K-Nearest Neighbor Classification
    
   (ii) Logistic Regression
    
   (iii) Decision Tree Classification
    
   (iv) Random Forest Classification
    
   (v) Gaussian Naive Bayes Classification
   
    
ACCURACY TABLE:

![image](https://user-images.githubusercontent.com/100083614/219969816-8fa87f2d-980a-4928-a344-3fff31ccc490.png)

CONCLUSION:
1. Cluster Sampling method is the most suitable sampling method for this dataset as it gives maximum accuracy for all selected ML models
2. Out of all ML models, Random Forest Classifcation gives maximum accuracy for this dataset on all sampling methods.
