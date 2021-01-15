# Credit Card Fraud Classifier
The model prediction in this project were attempted to detect fraudelent credit card transactions, with a highly imbalanced dataset made by credit cards in September 2013 by European cardholders. 

- The top models selected were:
  - Extra Trees Classifier with an AUC score of 0.9876
  - Random Forest Classifier with an AUC score of 0.9813
  - Extreme Gradient Boosting with an AUC score of 0.9796
- The Extra Trees Classifier predicted AUC score of 0.9156 during model evaluation
- With the application of PyCaret's automated python library, a lot of time has been saved compared to traditional methods. 

## Resources Used
**Programming language:** Python 3.7

**Packages:** pandas, numpy, PyCaret (scikit-learn, spaCy), seaborn, matplotlib, shap

## Dataset
- Source: https://www.kaggle.com/mlg-ulb/creditcardfraud
- The fraudelent transactions amount for 2% of all transactions, which was anonmyized from a result of a PCA transformation as a purpose of protecting the confidentiality of the data. 
- SMOTE (Synthetic Minority Over-sampling Technique) was applied using fix_imbalance() to handle the imbalanced nature of the dataset
- Data points:-
  - Time (date/time) 
  - V1, V2....V28 (float)
  - Amount (numerical)
  - Class (boolean)

## Exploratory Data Analysis

<p float="left">
  <img src="https://github.com/PannaD8ta/Creditcard_Fraud_Classifer/blob/main/AUC.png" alt="AUC" width="400" height="350"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/PannaD8ta/Creditcard_Fraud_Classifer/blob/main/Confusion_Matrix.png" alt="Confusion Matrix" width="400" height="350" />
</p>
