# Using Differentially Private ML to Identify MA Residents Unprotected by Health Insurance

This project’s aim is to contribute to the new initiative of the State of Massachusetts to help build machine learning models to predict which residents are not protected by health care insurance. Especially during the COVID-19 pandemic, without proper health insurance, the residents hesitate to seek medical care if they contract the virus as they will likely receive large medical bills. Therefore, it is crucial for us to build a prediction model that would identify MA residents that are not currently protected, so that the State government can reach out to these individuals and inform them of the no-cost plans provided by the State. We fit, compare, and contrast a range of models, including a Multivariate Logistic Regression (baseline), Decision Tree, Random Forest, and FFNN. 

Because the raw U.S. Census data includes sensitive personally identifiable information, including names and addresses, it is essential to preserve the privacy of people in the training set after the model's deployment. Therefore, we make use of a differentially private machine learning library in this project, SmartNoise, in training our models.

Completed as a final project for Harvard's CS 109b, Advanced Topics in Data Science, by Vlad Ivanchuk, Isheka Agarwal, Felicia Roman, and Harkirat Bhullar.

