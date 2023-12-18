# Insurance-Prediction

+ Dataset Column Description - 

    1. id - Unique ID for the customer
  
    2. Gender - Gender of the customer
  
    3. Age - Age of the customer
  
    4. Driving_License - 0 : Customer does not have DL, 1 : Customer already has DL
  
    5. Region_Code - Unique code for the region of the customer
  
    6. Previously_Insured - 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance
  
    7. Vehicle_Age - Age of the Vehicle
  
    8. Vehicle_Damage - 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.
  
    9. Annual_Premium - The amount customer needs to pay as premium in the year
  
    10. PolicySalesChannel - Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
  
    11. Vintage - Number of Days, Customer has been associated with the company
  
    12. Response - 1 : Customer is interested, 0 : Customer is not interested

+ Objective - Create a ML Model to predict the heart disease.

+ Tools - Python code in Jupyter notebook, Powerpoint, Excel.

+ Algorithm Used - Logistic Regression, Decision Trees, Random Forest, K-Nearest Neighbors, Support Vector Machines (SVM), Naive Bayes.

  + Logistic Regression - Logistic regression is a statistical method used for binary classification, which means predicting the probability of an observation belonging to one of two classes. Despite its name, logistic regression is a classification algorithm, not a regression algorithm. It is widely used in machine learning and statistics for tasks such as spam detection, medical diagnosis, and credit scoring.
 
  + Decision Trees - Decision Trees are a popular machine learning algorithm used for both classification and regression tasks. The main idea behind a decision tree is to recursively partition the data into subsets based on the most significant attribute at each step. This process continues until a stopping criterion is met, such as a certain depth of the tree or a minimum number of samples in a leaf node.
 
  + Random Forest - Random Forest is an ensemble learning method that builds multiple decision trees during training and merges their predictions for more robust and accurate results. The main idea behind Random Forest is to reduce overfitting and improve generalization by aggregating the predictions of multiple base models (decision trees).
 
  + K-Nearest Neighbors - K-Nearest Neighbors (KNN) is a simple and intuitive machine learning algorithm used for both classification and regression tasks. It belongs to the family of instance-based or lazy learning algorithms, as it doesn't explicitly learn a model during training. Instead, it memorizes the training data and makes predictions based on the similarity of new instances to those in the training set.
 
  + Support Vector Machines (SVM) - Support Vector Machines (SVM) is a powerful supervised machine learning algorithm used for both classification and regression tasks. SVMs are particularly effective in high-dimensional spaces and are capable of creating non-linear decision boundaries through the use of different kernel functions.
 
  + Naive Bayes - Naive Bayes is a family of probabilistic machine learning algorithms based on Bayes' theorem. It is particularly popular for text classification tasks, such as spam filtering and sentiment analysis, but it can be applied to various types of data. Despite its simplicity and "naive" assumptions, Naive Bayes often performs well and is computationally efficient.

 
+ Methodology:
  
  •	Data Collection - The data used to build the model was provided in the csv format. It has gender, age, salary and whether the said person purchased the phone or not in 1 and 0 
    format, where 1 stands for yes and 0 for no.

  •	Data Pre-processing - Data pre-processing is a crucial step to ensure the quality and suitability of the dataset for training machine learning models.

  •	Feature Selection - Feature selection is a critical step to identify the most relevant variables that contribute to the predictive power of the model.

  •	Model Selection - In the model selection section, provide a detailed overview of the machine learning algorithms chosen for the predictive analysis. Explain the rationale behind the 
    selection of each algorithm and discuss how they align with the project objectives.
  
  •	Model Training - In the model training section, the processed data is fit to train the selected model so that it is able to predict the future entered data.

  •	Model Evaluation - In the model evaluation section, the performance of the trained machine learning models is assessed to select the best suited model for deployment.
