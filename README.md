# Predicting Customer Bank Term Deposit Subscription

The project aims to predict whether a customer will subscribe to a bank term deposit based on direct marketing campaigns conducted by a Portuguese banking institution. The marketing campaigns involved phone calls, and the goal is to determine if the client will subscribe to a term deposit or not.

## Dataset

The dataset used for this project is sourced from Kaggle and contains information about customers and their interactions with the marketing campaigns. The dataset includes the following features:

- Categorical variables: job, marital, education, housing, loan, contact, month, poutcome, and the dependent variable, y.
- Numeric data types: age, day of week, campaign, pdays, and previous.

In the dataset, the number of rows with data for a customer subscribing to a term deposit is around 12% of the total data.

Dataset link: [Bank Marketing Campaign Predictive Analytics](https://www.kaggle.com/benroshan/bank-marketing-campaign-predictive-analytics/data)

## Data Pre-processing

The data preprocessing steps involve converting string-type column values to integer type and transforming the target variable, 'y', to binary values (0 for 'no' and 1 for 'yes').

## Analysis

The analysis section includes exploring the data and extracting insights from it. Some of the analysis performed in this project includes:

- Number of subscribed and non-subscribed customers for term deposits.
- Top 5 professions with term deposits subscribed.
- Month with the highest percentage of term deposits.
- Top 5 age groups with the highest number of term deposit subscriptions.

## Building the Models

The project builds three classification models to predict customer bank term deposit subscription:

1. Logistic Regression Model
2. Decision Tree Model
3. Random Forest Classifier

The models are evaluated based on metrics such as accuracy, confusion matrix, area under ROC and PR curves, precision, and recall.

### Logistic Regression Model

The logistic regression model uses the VectorAssembler to create a vector of input features and fits the logistic regression algorithm to the training data. The model's accuracy, confusion matrix, area under ROC and PR curves, precision, and recall are evaluated.

### Decision Tree Model

The decision tree model also uses the VectorAssembler to create a vector of input features and fits the decision tree algorithm to the training data. The model's accuracy, confusion matrix, area under ROC and PR curves, precision, and recall are evaluated.

### Random Forest Classifier

The random forest classifier uses the RandomForestClassifier algorithm to fit the training data. The model's accuracy, confusion matrix, area under ROC and PR curves, precision, and recall are evaluated.

Please refer to the code for implementation details.

