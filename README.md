# Credit_Risk_Analysis

## Purpose

The purpose of this analysis was to use machine learning to predict credit risk. 

A dataset from LendingClub, a peer-to-peer lending services company was used. The data was oversampled using RandomOverSampler and SMOTE algorithms, undersampled using ClusterCentroids algorithm, and a combination approach of over- and undersampling was then used using the SMOTEEN algorithm. Then BalancedRandomForestClassified and EasyEnsemblerClassifier, which are both machine learning models that reduce bias, were compared. 

## Results

- ### Naive Random Oversampling
  - Balanced Accuracy Score: 6460813581992739
  - Precision: 
      - avg/total: 0.99
      - high risk: 0.01
      - low risk: 1.00
  - Recall Scores: 
      - avg/total: 0.67
      - high risk: 0.57
      - low risk: 0.68

<img width="489" alt="image" src="https://user-images.githubusercontent.com/105942622/191980697-935fdd33-4b5b-4acc-bde6-aa2b32bfde1e.png">


- ### SMOTE Oversampling
  - Balanced Accuracy Score: 0.6249249630354818
  - Precision:
      - avg/total: 0.99
      - high risk: 0.01
      - low risk: 1.00
  - Recall Scores:
      - avg/total: 0.64
      - high risk: 0.66
      - low risk: 0.64
  
  <img width="495" alt="image" src="https://user-images.githubusercontent.com/105942622/191981066-baab6e8d-43c3-4b39-a2fa-fc578c89eb2e.png">
  
  
 - ### Undersampling
   - Balanced Accuracy Score: 0.6460813581992739
   - Precision: 
      - avg/total: 0.99
      - high risk: 0.01
      - low risk: 1.00
   - Recall Scores: 
      - avg/total: 0.45
      - high risk: 0.61
      - low risk: 0.45
    
  <img width="487" alt="image" src="https://user-images.githubusercontent.com/105942622/191981546-5fd76513-ea72-4ba9-a98c-8ac84a10397d.png">

   
 - ### Combination (Over and Under) Sampling
   - Balanced Accuracy Score: 0.5303834237805738
   - Precision: 
      - avg/total: 0.99
      - high risk: 0.01
      - low risk: 1.00
   - Recall Scores: 
      - avg/total: 0.58
      - high risk: 0.79
      - low risk: 0.58
  
   
 <img width="479" alt="image" src="https://user-images.githubusercontent.com/105942622/191982028-9f5eb4b9-6679-4f01-83e3-04bd97e1267f.png">

   
 - ### Balanced Random Forest Classifier
   - Balanced Accuracy Score: 0.7877672625306695
   - Precision: 
      - avg/total: 0.99
      - high risk: 0.04
      - low risk: 1.00
   - Recall Scores: 
      - avg/total: 0.91
      - high risk: 0.67
      - low risk: 0.91
   
   <img width="490" alt="image" src="https://user-images.githubusercontent.com/105942622/191982603-0ae310bf-4dd7-4dad-b2b2-5139e1f686cd.png">


- ### Easy Ensemble AdaBoost Classifier
   - Balanced Accuracy Score: 0.925427358175101
   - Precision:
      - avg/total: 0.99
      - high risk: 0.07
      - low risk: 1.00
   - Recall Scores: 
      - avg/total: 0.94
      - high risk: 0.91
      - low risk: 0.94
   
   <img width="488" alt="image" src="https://user-images.githubusercontent.com/105942622/191982849-0d0305a6-ad62-4216-83fc-91f4356a6cae.png">
   

## Summary
Summary of results and recommendation on what model to use, or if no recommendation a justification. 

I would recommend using the Easy Ensemble AdaBoost Classified as compared to the other models. It had the highest precision is accurately identifying high risk loans as compared to all other models. It also has the best recall scores and balanced accuracy scores. 
