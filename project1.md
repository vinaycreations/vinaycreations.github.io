# Undergraduate Capstone Project: Building Models to Predict Ratings of Federal Judicial Nominees

## Introduction
- **Client:** University of Georgia - Political Science Department

- **Context:** When a vacancy arises in the Federal Judiciary, the President of the United States appoints a candidate to fill the position. The American Bar Association (ABA) assigns one of three ratings to the nominee: Not Qualified, Qualified, or Well Qualified.


## Objective
Analyze potential correlations between ABA ratings and various demographic or professional factors of judicial nominees—including age, sex, race, geographic location, appointment year, prior work experience, and political affiliation. Additionally, develop a predictive model to assess these relationships and forecast future ABA ratings for judicial appointments.

## Methodology
- **Random Forest:** An ensemble learning method that constructs multiple decision trees and combines their outputs to improve prediction accuracy and reduce overfitting. It is commonly used for classification and regression tasks.

- **Ordinal Logistic Regression (OLR):** A statistical modeling technique designed for predicting an ordinal dependent variable, where the response categories have a meaningful order but unequal spacing. It extends logistic regression to handle ordered outcomes.

- **K-Modes Clustering:** A clustering algorithm that extends K-Means for categorical data by using mode-based updates instead of mean-based updates. It is used to identify distinct groups within a dataset based on shared characteristics.

## Results
### **Random Forest**
- The figure below illustrates a single decision tree.
- With each additional split, the decision tree becomes more specific, progressively improving the classification accuracy by isolating data points based on relevant feature thresholds.
- In this case study, the Random Forest Algorithm used 50,000 decision trees to train the model and make predictions.

<img src="assets/Picture1.png" alt="Figure 1" width="600">

- The confusion matrix below compares the predicted results from the Random Forest model to the actual data.
- The model achieved an overall accuracy of 72%, though it shows a bias towards predicting 'Well Qualified'.
- Since there were only three 'Not Qualified' ratings in the dataset, none of them appeared in the randomized test set, which influenced the results.

<img src="assets/Picture2.png" alt="Figure 1" width="600">

**Ordinal Logistic Regression (OLR):**

**K-Modes Clustering:**

## Future Improvements
Mention any ideas or plans for further improving the project or areas that could be expanded upon.
