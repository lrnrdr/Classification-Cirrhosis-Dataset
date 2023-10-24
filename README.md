# Cirrhosis Predictions

## Analyzing various attributes contributing to Cirrhosis

Author: Loraine Rodriguez

___
## **Business Problem**

To assist a drug company to evaluate Drug D- penicillamine and its effects on different known contributors to Cirrhosis.   The goal of this is to help the drug company understand the effects and know how to properly market the drug, if it is shown in the data, that it prevents Cirrhosis. 

## **Data**

Cirrhosis Prediction Dataset: 
https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset
___

## **Methods**
With the data provided, we were able to create various different machine learning models. 
___

## **Comparision of 2 Explanatory Visuals**
Visual #1 - Using Barplot to compare choleterol to Stages (For Drug)
Visual #2-  Comparing Subplots of Cholesterol vs Bilirubin (For Drug)
___


## Visual #1
![image](https://github.com/lrnrdr/Classification-Cirrhosis-PredictionDataset/assets/138408700/49c534ce-4304-4e46-9804-83974457b9d5)

All stages had high cholesterol of >200 mg/dl while on Drug D.   The placebos and Drug performed neck and neck through most of the stages with an exception to stage 1 which Drug D had a Cholesterol of ~300 mg/dl and placebo had just under 200 mg/dl.  Given that the placebo's performed so close to Drug D, it doesn't seem as if tihs drug was effective when evaluating Cholestrol and the stages. 


The (test_R2) metric in the models is probably the most important metric. It shows that the model can explain a specific % of the data.
The Tuned Random Forest model can explain for 59% of the test data which means the others explain less of the variations in the target.

  
## Visual #2

![image](https://github.com/lrnrdr/Classification-Cirrhosis-PredictionDataset/assets/138408700/4484fe32-2227-4101-9e0a-f793b41b1522)


-Comparing the cholesterol on Drug D and Placebo, they are almost symmetric.    There is a slight positive correlation between Bilirubin and Cholesterol.
