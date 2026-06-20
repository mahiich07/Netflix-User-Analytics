# Netflix User Analytics

## Project Overview

This project analyzes Netflix user behaviour using Machine Learning techniques.  
The objective is to understand viewing patterns, analyze subscription details, predict subscription renewal, and estimate monthly spending.

The dataset contains information about Netflix users including demographics, viewing habits, subscription details and spending behaviour.

---

## Dataset Information

The dataset contains the following features:

| Column | Description |
|--------|-------------|
| UserID | Unique user identifier |
| Age | Age of user |
| Gender | User gender |
| SubscriptionType | Type of subscription plan |
| WatchHoursPerWeek | Weekly watching hours |
| DevicesUsed | Number of devices used |
| FavoriteGenre | Preferred content genre |
| AdClicks | Number of advertisement clicks |
| MonthlySpend | Monthly spending amount |
| SubscriptionRenewed | Subscription renewal status |

---

## Tasks Performed

### Dataset Understanding
- Loaded dataset
- Displayed records
- Checked rows and columns
- Identified numerical and categorical features
- Checked missing values

### Exploratory Data Analysis
- Calculated average user age
- Analyzed weekly watch hours
- Calculated average monthly spending
- Analyzed subscription categories
- Checked renewal percentage

### Data Preparation
- Converted categorical data into numerical format
- Created feature and target variables
- Split data into training and testing sets

---

## Machine Learning Models

### Decision Tree Classifier
Used to predict whether a user will renew their Netflix subscription.

Evaluation:
- Accuracy Score
- Confusion Matrix


### K-Nearest Neighbors (KNN)

A KNN model with K = 5 was trained for subscription renewal prediction.

The accuracy was compared with the Decision Tree model.


### Linear Regression

Linear Regression was used to predict monthly spending of Netflix users.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- GitHub

---

## Conclusion

Machine Learning models help analyze customer behaviour and predict important business outcomes.

These predictions can help streaming platforms improve customer retention, provide better recommendations and make data-driven decisions.
