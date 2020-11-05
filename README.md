# Supervised_Machine_Learning
supervised machine learning challenge 17
# Naive Random Oversampling

Precision - 0.01, 1.00
Recall - 0.71, 0.61
Balanced Accuracy Score - 0.6594349419740851

# SMOTE Oversampling
Precision - 0.01, 1.00
Recall - 0.62, 0.69
Balanced Accuracy Score - 0.6591391394752197

# Undersampling Cluster Centroids
Precision - 0.01, 1.00
Recall - 0.66, 0.40
Balanced Accuracy Score - 0.5296777894580852

# Combination Sampling
Precision - 0.01, 1.00
Recall - 0.73, 0.59
Balanced Accuracy Score - 0.6593675036353027

In summary all models had similar precisionw with a high precision on identifying low_risk loans and a loan precision on identifying high_risk loans. The accuracy of each was similar except for the undersampling and it was much lower accuracy than the rest. I would proceed with the Combination Sampling because it had the highets recall rate which means it was able to detect the most high_risk loans.
