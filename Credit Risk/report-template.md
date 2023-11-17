# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
     * The purpose of this analysis was to predict the credit risk for those who lend loans to others. 
* Explain what financial information the data was on, and what you needed to predict.
     * The financial information included several features about loans given out including the interst, size, account size of the individual etc. The information also included the status of the loan which is essentail to testing the data. 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
     * Using value counts I was able to see how much data was in the testing data, including 75k Healthy Loans and 2k High-Risk Loans. Because I was trying to predict the health of a loan given out by a lender it was essential to know how much past data I had. The model ended up predicting better healthy loans because there was more previous data that led to healthy loans than high-risk loans. 
* Describe the stages of the machine learning process you went through as part of this analysis.
     * We had to train/test/split the data into training sets and testing sets
     * Next we had to fit the model to a logestic regression
     * Then we had to feed it training data in order for it to make predictions.
     * Next we found accuracy score and confusion matrix to show how well this model would predict.
     * Next we produced the Classification Report in order to see the total precision, recall, and accuracy to see how well the model predicted both healthy and high-risk loans. 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
     * In this excersize we only used LogisticRegression because the resampling method was omitted by our SSC Bret Payne.
     * The Logistic Regression is usually considered great at predicting items that only have 2 outcomes, such as a healthy or high-risk loan.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
       * Over all the accuracy of the model was 99% including all of the testing data for Healthy and High-Risk loans
       * The Precision of the Healthy loans was 100%, and 85% for the High-Risk Loans
       * The Recall scores for the healthy loans was 99% for healthy loans, and 91% for High-Risk Loans.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
       * THIS PORTION WAS OMITTED BY OUR SSC BRETT PAYNE

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

     * Because the LogisticRegression model was the only model we used, I would reccomend to use the LogisticRegression model. This model nearly 100% of the time predicts whether or not it would be a healthy loan which is important for lenders. Although the High-Risk loan prediction is lower which lenders may not like, because the overall Accuracy of the model is still 100% despite the low precision and recall for the High-Risk loans, I would still reccomend the Logistic Regression Model. 
