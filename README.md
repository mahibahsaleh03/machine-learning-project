# Machine Learning Project - Credit Card Default Data

# Introduction and Background

1. Evaluation of Credit Risk - [LINK](https://cs229.stanford.edu/proj2012/SittWu-EvaluationOfCreditRisk.pdf)
2. Machine Learning for Credit Risk Prediction: A Systematic Literature Review - [LINK](https://www.mdpi.com/2306-5729/8/11/169#)
   > This review explores the use of ML in credit risk prediction, highlighting the importance of AI in processing large datasets for financial institutions. It identifies common models, metrics, and challenges like explainability and data imbalance, while offering guidance for developing credit risk management tools to minimize defaults. Key variables include demographic, operational, and payment behavior data.
3. Advancing credit risk modeling with Machine Learning: A comprehensive review of the state-of-the-art - [LINK](https://www.sciencedirect.com/science/article/pii/S0952197624012405)
   > This reviews the use of ML in consumer credit risk modeling, emphasizing its growing importance in handling large datasets and improving predictive power compared to traditional methods like Logistic Regression (LR). While ML algorithms such as Decision Trees (DT), Support Vector Machines (SVM), and Neural Networks (NN) offer potential enhancements, they face challenges in practical application. The review highlights the key steps in ML model development, from data pre-processing to parameter optimization, and stresses the need for standardized modeling procedures before deploying complex ML models commercially.

# Problem Definition
In today’s digital economy, financial institutions rely heavily on credit transaction data to evaluate creditworthiness. However, many credit scoring models primarily focus on historical credit data, which can overlook valuable insights from transaction behavior that indicate changes in an individual's financial risk.

The core problem is creditworthiness prediction: Accurately assessing an individual's credit risk is essential for lenders to make informed decisions about loans and interest rates. Current models often miss important patterns in transaction behavior that could provide a clearer picture of creditworthiness. Our model will aim to accurately predict if an individual will default on loans or not.

# Dataset
Link: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

Description: The Default of Credit Card Clients UCI Dataset contains data on credit card holders in Taiwan and aims to predict whether a client will default on their payment. It includes 30,000 observations and 24 features such as demographics (age, education, marital status, gender), credit card usage (bill statements, payment history), and default payment status (whether the client defaulted the next month).

# Methods
To handle the preprocessing of the data, there are multiple methods to implement prior to applying the dataset to a machine learning model. First, our process will involve data cleaning in order to eliminate inaccurate data. Next, we will make use of feature engineering to obtain better features for the dataset from features that are already present. Lastly, we will address imbalanced data using SMOTE or other methods to address the issue of loan defaults being the minority in our dataset. After processing the data, we will use supervised learning models such as logistic regression, random forest, and gradient boosting. Logistic regression will be helpful in initially classifying the data as default or not and random forest will help improve our predictions. We will also use gradient boosting to gradually improve upon each model.

# Potential Results and Discussion
We will use several quantitative metrics to measure the accuracy of our model. First, we will utilize accuracy, the number of times our model correctly predicts loan defaulting. Another is the F1 Score, which measures the precision and recall of our model. Precision measures false positives, approving an untrustworthy individual for a loan. Recall measures false negatives, denying a good credit risk. We will also utilize the Receiver Operating Characteristic curve, which helps us measure the number of false positives versus true positives in our model. Our goal in this project is to create a model that will accurately predict if an individual will default on a loan or not. Stanford researchers Sitt and Wu were able to achieve accuracy of 70% in a similar credit-prediction model, so we hope to achieve similar or greater results. Additionally, we hope to create an ethical model, which does not discriminate based on demographic characteristics or predict vastly different results for slightly different input values.

# References
A. Montevechi, R. Miranda, A. Medeiros, and J. Montevechi, Eds., “Advancing credit risk modelling with Machine Learning: A comprehensive review of the state-of-the-art,” Aug. 2024.

Jomark Pablo Noriega, Luis Antonio Rivera, and Jose Alfredo Herrera, “Machine Learning for Credit Risk Prediction: A Systematic Literature Review,” Aug. 2023, doi: https://doi.org/10.20944/preprints202308.0947.v1.

‌M. Sitt and T. Wu, “Evaluation of Credit Risk.” Accessed: Oct. 04, 2024. [Online]. Available: https://cs229.stanford.edu/proj2012/SittWu-EvaluationOfCreditRisk.pdf


# Tables
Gantt Chart: [LINK](https://docs.google.com/spreadsheets/d/1_VUAMo002Tv-8mLRiyFK3bGIlX5s4-en/edit?usp=sharing&ouid=112209367681545806735&rtpof=true&sd=true)

Contribution Table
|Name|Contributions|
|---|---|
|Sive|Video Presentation, Potential Results and Discussion|
|Maha|Video Presentation, Methods|
|Esther|Introduction, Literature Review, Problem Definition|
|Avalyn|Methods|
|Mahibah|Dataset, Github Page|



