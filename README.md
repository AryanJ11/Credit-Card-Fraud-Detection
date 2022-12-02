# Credit-Card-Fraud-Detection
With the digital revolution of payments, and of course how banks are pushing to buy credit cards ,the credit card market is growing in India year-by-year.
With the advent of this growth credit/debit card frauds have also exponentially increased. 

<b> And who bears the cost of these frauds ? </b>

It's usually the bank or merchant who bears the cost of fraud. And thus Banks and Intermediary body spend a lot of money in building strong fraud detection systems 

This repository contains a step-by-step explanation of the ML pipeline which is usually followed by big companies for fraud detection. The aspects of pipeline covered are:

### 1. Formulation of problem statement in context of business requirement

Defining the fraud in terms of what the company thinks of as a fraud is important

For eg: 
* For company A, a fraud might be the user giving false information to borrow money 
* But for company B, it might be called as unauthorised transactions done by someone else apart from the user

For our purpose we use the latter definition (company B)

### 2. Data collection, processing and exploration

Gathering the right data which is in accordance with the problem defined is crucial to get the best results

But getting data in exactly the format we need is very rare. So some processing of data has to be done

In this repository, we cover a major aspect of data processing in fraud detection which is <b> feature engineering </b>

Data source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

References
* Bahnsen A. C., Aouada D., Stojanovic A., Ottersten B., _Feature engineering strategies for credit card fraud detection_, Expert Systems With Applications, 2016, doi: https://doi.org/10.1016/j.eswa.2015.12.030
* https://medium.com/dataman-in-ai/how-to-create-good-features-in-fraud-detection-de6562f249ef

### 3. Model building and training

Once data exploration is done, we get useful insights of which algorithm to use and how to use them.

Some ML algorithms covered in the above repository:
* Logistic Regression
* K-Nearest Neighnours
* Isolation forests

### 4. Model Evaluation

Model training in followed by estimating the evaluation of model performance on test set which gives an idea on how it might perform on real-time data

The techniques covered keep in mind that the data might be imbalanced and therefore includes computing precision. recall and other appropriate metrics

### 5. Model deployment

Finally, once we think our model is ready its time to push it into deployment. But its hardly as easy as it sounds.

To keep the model relevant and adaptive, certain measures have to be undertaken which includes model retraining and counterfactual evaluation.

References
* https://www.youtube.com/watch?v=rHSpab1Wi9k



