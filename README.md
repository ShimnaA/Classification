**Classification**
------------------------

**Logistic Regression**
    - Dataset - Social_Network_Ads.csv  [logistic_regression.ipynb]

    - A car company - manufacture a new SUV. Try to predict whether a customer will buy or not
    - Data set contains each customer details - Age, Estimated Salary, and whether bought older SUV model before.
    - Set up a Logistic Model to Predict
    - No need to do Feature Scaling for Logistic REgression, Still applying Feature Scaling improves the model
    - Scikit Learn -> linearmodel -> LogisticRegression class
    - Predict for a customer. Predict for Test Set
    - Accuracy Score = 0.89
   
   - Dataset - breast_cancer.csv  [logistic_regression2.ipynb]

    - Data set from UCI
    - Features are all integers less than 10, with no missing values
    - Read in features excluding the 'Sample code number' which have no significance on result
    - Model the data on Logistic Regression Algorithm
    - Predict and Evaluate

**K Nearest Neighbors**

    - Dataset - Social_Network_Ads.csv  [logistic_regression.ipynb]

    - A car company - manufacture a new SUV. Try to predict whether a customer will buy or not
    - Data set contains each customer details - Age, Estimated Salary, and whether bought older SUV model before.
    - Train  a K Nearest Neighbors classifier Model
    - Feature Scaling using Standard Scalar
    - Predict for a customer. Predict for Test Set
    - Visualize
    - Accuracy Score = 0.93
 
**Support Vector Machine**

    - Dataset - Social_Network_Ads.csv  [support_vector_machine.ipynb]
    
    - Kernel SVM. The rebellious algorithm.
    - Never bad to apply Feature Scaling.
    - SVM using linear kernel
    - Evaluate and Visualize
    - Accuracy Score = 0.90
    
**Kernel SVM**

    - Dataset - Social_Network_Ads.csv  [support_vector_machine.ipynb]
    
    - sklearn.svm -> SVC, with kernel='rbf' (non linear kernel)
    - Feature scaling applied
    - Evaluate and Visualize. Accuracy Score = 0.93
    
    
**Naive Bayes**

    - Dataset - Social_Network_Ads.csv  [support_vector_machine.ipynb]
    
    - sklearn.naive_bayes -> GaussianNB
    - Feature scaling applied
    - Non linear model
    - Evaluate and Visualize. Accuracy Score = 0.90
   
    
**Decision Tree**

    - Dataset - Social_Network_Ads.csv  [support_vector_machine.ipynb]
    
    - sklearn.tree -> DecisionTreeClassifier
    - Feature scaling applied
    - Evaluate and Visualize. Accuracy Score = 0.91
    
    
**Random Forest**

    - Dataset - Social_Network_Ads.csv  [support_vector_machine.ipynb]
    
    - sklearn.ensemble -> RandomForestClassifier
    - Number of trees selected as 10
    - To measure the quality of split - entropy - for information gain
    - Evaluate and Visualize. Accuracy Score = 0.91