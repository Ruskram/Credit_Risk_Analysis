# Credit_Risk_Analysis

# Supervised Machine Learning and Credit Risk

## Overview of Project

### Purpose

The purpose of this project is to perform loan risk analysis predictions using machine learning. This challenge has us using 6 different models to test the data and see how each model predicts the outcome. This will give us an understanding that is wise to test your data with multiple models to improve results.

## Results

- Naive Random Oversampling

Balanced Accuracy Score - This model had an accuracy of 65%

![image](https://user-images.githubusercontent.com/92827264/161456939-0cfa7fea-3c0e-4963-81bf-fffbe885d2eb.png)

Precision - This model has the following confusion matrix

![image](https://user-images.githubusercontent.com/92827264/161457262-be256b0f-bc9a-48af-bd3d-89f833885e89.png)

Recall scores

![image](https://user-images.githubusercontent.com/92827264/161457283-1b6e4b8b-6a77-4d6c-bf52-f6f854269a9c.png)

- SMOTE Oversampling

Balanced Accuracy Score

![image](https://user-images.githubusercontent.com/92827264/161457340-8d6bd6b9-7b0e-440d-bee5-c2ae6794124a.png)

Precision

![image](https://user-images.githubusercontent.com/92827264/161457356-42a15479-d9b2-4907-93c0-99a4cd75f8f8.png)

Recall scores

![image](https://user-images.githubusercontent.com/92827264/161457363-fee49c52-dc1b-4efb-bb1a-db91a3abc03d.png)

- Undersampling (Cluster Centroids)

Balanced Accuracy Score

![image](https://user-images.githubusercontent.com/92827264/161457439-087bf8b8-0a9c-4242-972c-953c52d96557.png)

Precision

![image](https://user-images.githubusercontent.com/92827264/161457467-4d0847d6-2c4a-4de6-8cb3-47909de15f7f.png)

Recall scores

![image](https://user-images.githubusercontent.com/92827264/161457484-a8e1b726-09e9-4a46-9965-ddbf07ece58e.png)

- Combination Over and Under Sampling (SMOTEENN)

Balanced Accuracy Score

![image](https://user-images.githubusercontent.com/92827264/161457509-a41d8d40-5f80-4f2b-b74d-a13ad0a77d59.png)

Precision

![image](https://user-images.githubusercontent.com/92827264/161457532-9d0ed8e3-5a31-4890-ab83-475ecab0c141.png)

Recall scores

![image](https://user-images.githubusercontent.com/92827264/161457543-a6e14985-7861-49d6-872d-4953edbf7c04.png)

- Balanced Random Forest Classifier

Balanced Accuracy Score

![image](https://user-images.githubusercontent.com/92827264/161457599-a1ee8056-b99d-4ef3-b1dd-91660c9c6a96.png)

Precision

![image](https://user-images.githubusercontent.com/92827264/161457609-4fb09f3b-b7fe-41c7-9dd8-c43774d0215b.png)

Recall scores

![image](https://user-images.githubusercontent.com/92827264/161457618-141cedf6-1336-4169-93ab-dcb39cc59663.png)

- Easy Ensemble AdaBoost Classifier

Balanced Accuracy Score

![image](https://user-images.githubusercontent.com/92827264/161457657-79d902b2-0658-4a78-a5e5-537ec6fb4b62.png)

Precision

![image](https://user-images.githubusercontent.com/92827264/161457670-319fe70c-cd45-4f80-8f88-58d5ad2e9276.png)

Recall scores

![image](https://user-images.githubusercontent.com/92827264/161457685-48bfa1cf-ad22-4b24-ad4c-3baec5309550.png)

## Summary

After running all of the models we can see that the resampling method is not the most ideal for this kind of data. From all the resampling models the highest accuracy model was the over sampling ones with SMOTE being the highest at 66%. I would clearly use ensemble methods for running machine learning on this kind of data. Looking at both models their accuracy is above 75% with the easy ensemble adaboost having a 93% accuaray, and only below 10% false positives/negatives.
