# ai-bme-final-project

Artificial Intelligence in BME Final Project

**Authors:** David Chang and Mikey Komaiha

**Date:** April 2020

## Summary: 

We evaluated different machine learning algorithsm for predicting primary biliary cirrhosis patient outcomes. 

This project used both unsupervised and supervised machine learning to predict patient survival time and status (alive or deceased) after a 10 year period.

Unsupervised learning used to explore data:

- Principal component analysis (PCA)
- K-means clustering

To predict patient survival time, we used the following models:

 - **Stepwise Regression [Performed best according to Pearson's correlation] --> Used subset of 12 noninvasive variables with log values substituted for albumin, bili, and protime**
 - Linear Regression
 - Lasso
 - Random Forest

To predict patient survival status, we used the following models:

- Logistic regression
- **Random forest [Performed best according to Pearson's correlation]**
- Support vector machine

Original data and reformatted data files contained in **data**

MATLAB live script and html output files contained in **results**. We standardized all the data and ran the code again for `finalProjectZscore.html`.

For full details, please view **Final Report.pdf**.

**Original Research Paper:** [Prognosis in primary biliary cirrhosis: Model for decision making](https://aasldpubs.onlinelibrary.wiley.com/doi/abs/10.1002/hep.1840100102)

**Original Dataset:** https://github.com/therneau/survival/blob/master/data/pbc.rda
