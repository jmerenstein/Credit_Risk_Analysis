# An Analysis of Credit Risk Analysis

## Purpose of Analysis
The main prupose of this analysis was to utlize machine learning to analyze credit card risk. To perfrom this analysis I utilized a variety of different resampling models and algorithims to see how the models perfomed when prediciting credit card risk. These techniques allowed me to see which models may predict credit risk over others. 

## Summary Statistics on Suspension Coils
-  The current manufacturing data does not meet the specification of the variance of the suspension coils not excedding 100 punds per square inch for every lot. As can be seen [here](https://github.com/jmerenstein/MechaCar_Statistical_Analysis/blob/main/lot_summary.png) the variance for Lot 1 and Lot 2 are way below 100, but the variance for Lot 3 is over 170 punds per square inch and therefore does not meet the manufacturing specifications. 

## T-Tests on Suspension Coils
- When comparing the population mean of 1500 PSI to the mean PSI lot, I found that only lot 3 had a significantly different average PSI. Lot 1 and Lot 2 both had p values well above the .05 number that would have made them significantly different from the population mean of 1500. But, as can bee seen [here](https://github.com/jmerenstein/MechaCar_Statistical_Analysis/blob/main/Lot3_Ttest.png) the Lot 3 mean had a p value at .04 which is below the .05 mark needed to be statisticallly significant. Therefore, we can reject the null hypothesis for Lot 3 and state there is a significant difference between the population mean and the Lot 3 mean.

## Study Design: MechaCar vs Competition
- For my MechaCar statiscal study I would compare how the MechaCar's mean fuel efficiency compared to the popultion mean of the main competitor car on the market.
- The main metric I am going to test if miles per gallon and I will pick the main competitor car on the market and calculate the population mean of that car's miles per gallon.
- The null hypothesis is that there is no difference between the MechaCar's fuel efficiency and the fuel efficiency of the main competitor car.
- For this study I would use a One-sample t-Test because I am comparing the sample fuel efficency mean from the MechCar, since it is a prototype and hasn't yet actually been driven by the public, and the population fuel efficiency mean of the competitor's car.
- I would need the miles per galllon that each car gets and certain knowledge about each car to make sure that they are similar enough to compare. 
