# An Analysis of Credit Risk Analysis

## Purpose of Analysis
The main prupose of this analysis was to utlize machine learning to analyze credit card risk. To perfrom this analysis I utilized a variety of different resampling models and algorithims to see how the models perfomed when prediciting credit card risk. These techniques allowed me to see which models may predict credit risk over others. 

## Summary of Results
-  The first sampling method used was the Naive Random Oversampling technique. The results, which can be seen [here](https://github.com/jmerenstein/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling.png), show that the model has an accuracy score of .65. The results also show it has a high precision score for the high-risk loans, but a low precicision score for the low-risk loans. The model also has pretty equivalent recall scores between both type of loans.
-  The second sampling method used was the SMOTE Oversampling technique. The results, which can be seen [here](https://github.com/jmerenstein/Credit_Risk_Analysis/blob/main/SMOTE%20Oversampling.png), show that the model has an accuracy score of .64. The results also show it has a high precision score for the high-risk loans, but a low precicision score for the low-risk loans. The model also has pretty equivalent recall scores between both type of loans.
-  The third sampling method used was the ClusterCentroids Undersampling technique. The results, which can be seen [here](https://github.com/jmerenstein/Credit_Risk_Analysis/blob/main/ClusterCentroids%20Undersampling.png), show that the model has an accuracy score of .53. The results also show it has a high precision score for the high-risk loans, but a low precicision score for the low-risk loans. The model also has higher recall score for the high-risk loans then the low risk loans.
-  The fourth sampling method used was the SMOTEEN sampling technique. The results, which can be seen [here](https://github.com/jmerenstein/Credit_Risk_Analysis/blob/main/SMOTEEN%20Sampling.png), show that the model has an accuracy score of .64. The results also show it has a high precision score for the high-risk loans, but a low precicision score for the low-risk loans. The model also has higher recall score for the high-risk loans then the low risk loans.

## T-Tests on Suspension Coils
- When comparing the population mean of 1500 PSI to the mean PSI lot, I found that only lot 3 had a significantly different average PSI. Lot 1 and Lot 2 both had p values well above the .05 number that would have made them significantly different from the population mean of 1500. But, as can bee seen [here](https://github.com/jmerenstein/MechaCar_Statistical_Analysis/blob/main/Lot3_Ttest.png) the Lot 3 mean had a p value at .04 which is below the .05 mark needed to be statisticallly significant. Therefore, we can reject the null hypothesis for Lot 3 and state there is a significant difference between the population mean and the Lot 3 mean.


