# **DATA SCIENCE PROJECT:NO CHURN TELECOM**
![image](https://github.com/user-attachments/assets/41094ad3-06b3-4cd2-9124-666c7ad462c7)

## **BUSINESS CASE: PREDICT WHETHER A CUSTOMER WILL CHURN (LEAVE THE SERVICE) OR NOT.**
## **TASK: CLASSIFICATION**
## **INTRODUCTION OF PROJECT**:
* No-Churn Telecom is an established Telecom operator in Europe with more than a decade in Business. Due to new players in the
market, telecom industry has become very competitive and retaining customers becoming a challenge.

 * In spite of No-Churn initiatives of reducing tariffs and promoting more offers, the churn rate (percentage of customers migrating to competitors) is well above 10%. 

* No-Churn wants to explore possibility of Machine Learning to help with following use cases to retain competitive edge in the industry.
## **PROJECT GOAL**:

#### 1. Understanding the variables that are influencing the customers to migrate.

#### 2. Creating Churn risk scores that can be indicative to drive retention campaigns.

#### 3. Introduce new predicting variable “CHURN-FLAG” with values YES(1) or NO(0) so that email campaigns with lucrative offers be targeted to Churn YES customers.

## **PROJECT IS DEVICE INTO CERTAIN STEPS:**

**1.Fetching data from data-base.**

**2.Domain Analysis.**

**3.EDA: [Univariate, Bivariate &  analysis condition]**

**4.Data preprocessing/Feature Engineering.**

**5.Features Selection.**

**6.Model Creation.**

**7.Model Evaluation.**

**8.Model Comparison.**

**9.Conclusion**

## **DOMAIN ANALYSIS**
- **State** - 2-letter code of the US state of customer residence.
- **Account Length** - Number of months the customer has been with the current telco provider.
- **Area Code** - 3 digit area code.
- **Phone** - Phone number of customer.
- **International Plan** - The customer has international plan or not.
- **VMail Plan** - The customer has voice mail plan or not.
- **VMail Message** - Number of voice-mail messages.
- **Day Mins** - Total minutes of day calls.
- **Day Calls** - Total number of day calls.
- **Day Charge** - Total charge of day calls.
- **Eve Mins** - Total minutes of evening calls.
- **Eve Calls** - Total number of evening calls.
- **Eve Charge** - Total charge of evening calls.
- **Night Mins** - Total minutes of night calls.
- **Night Calls** - Total number of night calls.
- **Night Charge** - Total charge of night calls.
- **International Mins** - Total minutes of international calls.
- **International calls** - Total number of international calls.
- **International Charge** - Total charge of international calls.
- **CustServ Calls** - Number of calls to customer service.
- **Churn** - Customer churn or not. (target variable)

  # **EXPLORATORY DATA ANALYSIS**
## UNIVARIATE ANALYSIS
### USING HISTOGRAM 
![image](https://github.com/user-attachments/assets/86ceebd5-bbfe-422c-856d-f1c62b99788f)


### USING COUNTPLOT
![image](https://github.com/user-attachments/assets/c9209569-87ad-4e2e-a8a4-aaa743349074)

![image](https://github.com/user-attachments/assets/ae804dde-8359-450a-9e74-9e0e40ffa5ee)

![image](https://github.com/user-attachments/assets/7c1ef068-3b69-49e6-8eda-1f8bc6d3ce73)

### BIVARIATE ANALYSIS
![image](https://github.com/user-attachments/assets/d4ac39ab-8226-4872-bac7-b92178feb004)

**PAIRWISE SCATTER PLOTS**
![image](https://github.com/user-attachments/assets/efe0494d-9fab-4050-bb59-77ee7478ba4f)

**BOXPLOTS**
![image](https://github.com/user-attachments/assets/b1ebde96-6d1b-4345-98e5-2ea07bfbee27)

![image](https://github.com/user-attachments/assets/3e31ba7f-8aa8-4e1b-be5e-d2c9a82df3b8)
![image](https://github.com/user-attachments/assets/90ed08f4-5c5b-4034-8666-d392a6b567e5)



##  **DATA PREPROCESSING**
 * HANDLING NULL VALUES
 * HANDLING CATEGORICAL DATA 
## **OUTLIERS HANDLING**
![image](https://github.com/user-attachments/assets/9593752f-2dfc-4684-8a52-4e387cb20a09)
## **SCALING THE DATA**
**Using MinMaxScaler**
## **FEATURES SELECTION**

###  **CHECKING THE CORRELATION**
![image](https://github.com/user-attachments/assets/5273572b-b6ba-421c-91eb-869068575bba)

 ## MODEL COMAPRISION REPORT:

 * Logistic Regression :- 71.21%
* Cross validation on logistic regression :- 86.26%
* Logistic Regression with best hyperparameter :- 86.47%


* Support Vector Machine :- 85.49%
* Cross validation on SVM :- 89.06% 


* K-Nearest Neighbor :- 87.66% 
* Cross validation on KNN :- 87.35%
* K-Nearest Neighbor with best hyperparameter :- 88.52%

* Decision Tree Classifier :- 96.53% 
* Cross validation on Decision Tree Classifier :- 86.00%
* Decision Tree with best hyperparameter :- 85.49%


* Random Forest Classifier :- 97.51%
* Cross validation on Random Forest Classifier :- 92.18%
* Random Forest with best hyperparameter :- 97.83%


* Gradient Boosting :- 91.23%
* Cross validation on Gradient Boosting :- 92.31% 
* Gradient Boosting with best hyperparameter :- 98.05%

* XGBoost :- 97.94%
* Cross validation on XGBoost :- 94.63%
* XGBoost with best hyperparameter :- 92.42%


* Artificial Neural Network :- 13.52%
* Cross validation on  ANN :- 92.31%
* ANN with best hyperparameter :- 97.94%


##### The best accuracy is given by the  Gradient Boosting with best hyperparameter  i.e. 98.05%

# **CONCLUSION**
**In the "NO-churn telecom" dataset comprising 4617 entries, the Gradient Boosting model, fine-tuned with the best hyperparameters, demonstrated an exceptional accuracy of 98.05%.**

**This signifies the effectiveness of Gradient Boosting in accurately predicting churn within the telecommunications dataset. The high accuracy underscores the model's robust performance and suitability for deployment in predicting customer churn.**

**Careful consideration should be given to potential applications in real-world scenarios, and further analysis may be conducted to ensure the model's reliability and generalizability.**
