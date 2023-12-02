# Module 12 Report Template

## Overview of the Analysis

* Purpose : 
Using machine learning, the purpose of this analysis is to predict the risks associated with loans. Meaning that we want to find out whether a loan has potential high risks . 

* Basic Information:
 To discover which model provides the best results, we are provided with a csv containing information such as: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. 


## Results

* Machine Learning Model 1:
     * According to the initial data:
         Overall Balance Accuracy: 99.2%

         Healthy Loan: -Precision:99.7% ,  -Recall:99.5%

         High-rish Loan: -Precisiom:84.7% , -Recall:91%

* Machine Learning Model 2:
     * According to the Oversampled dats:
      Overall Accuracy:99.2% 
  
       Healthy Loan: - Precision: 100% , -Recall: 99.4%
    
       High-risk Loan: - Precision: 84.1% , -Recall 99.4%


## Summary
Overall, when we analyze both models, we notice that both models have a high accuracy performance. Both the Original Data Model(model 1) and the Over Sampled Model(model 2) have similiar performnce. However, if we were to narrow it down to which one "performs best" once can say Model 2 is the Best. Both have High Precisions , but when looking at the "recall" section, we notice that in the first model the High-risk loan , the increased from 91% to 99.4% which is approximately an 8% difference. Because of this difference , Model 2 is considered the best. 

