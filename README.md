# BIg-data-Credit-card-fraud-detection

Dataset:

Link for the dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The data-set used here consists of 284,807 European credit
card transaction instances of which 492 (0.172%) are fraudu-
lent (denoted by the class label ’1’). 2 of the 30 predictors are
the output of PCA transformation applied in part to anonymize
the data set. The remaining 2 are the ’Time’ and ’Amount’
features.

Three aproaches are used to solve this problem.

1. Local - Local Map Reduce

<img width="251" alt="image" src="https://user-images.githubusercontent.com/49164907/181906310-51397cd5-caba-4b3d-9dd0-86f66518e1f7.png">


<img width="1841" alt="Local SMOTE+ENN" src="https://user-images.githubusercontent.com/49164907/181906259-aa0b4e06-b366-4139-b50a-19cda92c4e9f.png">

<img width="221" alt="image" src="https://user-images.githubusercontent.com/49164907/181906383-cfa9a4bd-d600-4bcd-8519-51159bf25c4d.png">


2. Global - Smote_Enn_Global
<img width="251" alt="image" src="https://user-images.githubusercontent.com/49164907/181906323-39dfcf3f-dd84-49af-89b5-1ea36e8c8a1f.png">


![GlobalSMOTEEN](https://user-images.githubusercontent.com/49164907/181906260-82968d5b-78c9-402a-953b-de7bdd0e59e3.png)

3. Hybrid - Smote_Enn_Cluster_Global

<img width="254" alt="image" src="https://user-images.githubusercontent.com/49164907/181906344-0b61b380-62a0-4965-a0ae-4064557e325c.png">


![HybridSMOTEENN](https://user-images.githubusercontent.com/49164907/181906257-972d629c-a57d-42f5-8f00-439929ba0524.png)



