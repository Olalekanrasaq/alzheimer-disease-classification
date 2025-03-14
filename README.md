# alzheimer-disease-classification

- The aim of this project is to use features extracted from MRI images, together with additional data, retrieved from the Alzheimer’s
Disease Neuroimaging Initiative (ADNI) database (http://adni.loni.ucla.edu/ and www.adni-info.org) to classify the healthy cognitive
normal (CN) subjects and patients with Alzheimer's Disease (AD)
- These features come from a number of healthy cognitively normal (CN) subjects and patients with Alzheimer’s Disease (AD).
- Two classification models - Logistic Regression and Random Forest - are used.
- The performance metrics of the two models revealed that Logistic Regression Classifier perform better on the validation sets than
Random Forest Classifier.
- Therefore Logistic Regression (LR) Model is a better model for classifying AD and Normal patients.
- The LR model is tuned by reducing the regularization strength to 0.1 from 1.0 which is the default value. 0.1 is the regularization
strength that produced the least validation error.
