



# Insurance-Prediction

+ Problem -
    Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company. An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee. For example, you may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalised in that year, the insurance provider company will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalised that year and not everyone. This way everyone shares the risk of everyone else. Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer. Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue. Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc..

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

+ Objective - Create a ML Model to predict whether a customer would be interested in Vehicle Insurance.

+ Tools - Python code in Jupyter notebook, Excel.

+ Algorithm Used - Logistic Regression, Decision Trees, Random Forest, K-Nearest Neighbors.

  + Logistic Regression - Logistic regression is a statistical method used for binary classification, which means predicting the probability of an observation belonging to one of two classes. Despite its name, logistic regression is a classification algorithm, not a regression algorithm. It is widely used in machine learning and statistics for tasks such as spam detection, medical diagnosis, and credit scoring.
 
  + Decision Trees - Decision Trees are a popular machine learning algorithm used for both classification and regression tasks. The main idea behind a decision tree is to recursively partition the data into subsets based on the most significant attribute at each step. This process continues until a stopping criterion is met, such as a certain depth of the tree or a minimum number of samples in a leaf node.
 
  + Random Forest - Random Forest is an ensemble learning method that builds multiple decision trees during training and merges their predictions for more robust and accurate results. The main idea behind Random Forest is to reduce overfitting and improve generalization by aggregating the predictions of multiple base models (decision trees).
 
  + K-Nearest Neighbors - K-Nearest Neighbors (KNN) is a simple and intuitive machine learning algorithm used for both classification and regression tasks. It belongs to the family of instance-based or lazy learning algorithms, as it doesn't explicitly learn a model during training. Instead, it memorizes the training data and makes predictions based on the similarity of new instances to those in the training set.

 
+ Methodology:
  
  •	Data Collection - The data used to build the model was provided in the csv format. It has gender, age, salary and whether the said person purchased the phone or not in 1 and 0 
    format, where 1 stands for yes and 0 for no.

  •	Data Pre-processing - Data pre-processing is a crucial step to ensure the quality and suitability of the dataset for training machine learning models.

  •	Feature Selection - Feature selection is a critical step to identify the most relevant variables that contribute to the predictive power of the model.

  •	Model Selection - In the model selection section, provide a detailed overview of the machine learning algorithms chosen for the predictive analysis. Explain the rationale behind the 
    selection of each algorithm and discuss how they align with the project objectives.
  
  •	Model Training - In the model training section, the processed data is fit to train the selected model so that it is able to predict the future entered data.

  •	Model Evaluation - In the model evaluation section, the performance of the trained machine learning models is assessed to select the best suited model for deployment.
