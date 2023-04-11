# Pneumonia Detection
Using an AI model that predicts pneumonia using x-ray scans of the patients' lungs.
We used KNN, Logistic regression and decision tree models. We also experimented with the images using data augmentation.
## Data
- Class: 0-benign, 1-malignant
- Split: 80% training, 20% testing
- index: upto 2400 rows

## Modeling
We trained K Neighbors Classifier, Logistic Regression, Decision Tree Classifier, and transfer leraning and achieved an accuracy of about 60-70%.
CNN: Activation using 'relu' and 'softmax' functions

## Data augmentation
We also used data augmentation(flipping, rotating, shearing, coloring images) to provide more training data and observe the effects on the prediction.

## Conclusion
Data augmentation, hidden layers, more epochs do improve the accuracy of the models to a certain extent.
