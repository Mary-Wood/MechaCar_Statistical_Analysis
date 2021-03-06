# MechaCar_Statistical_Analysis
This repository will store data that is analyzed in R to compare vehicle performance of the MechaCar against vehicles from other manufacturers. This will be done with a multiple linear regression, summary statistics, t-tests and a written summary to provide interpretation. 

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/89048287/145719053-342e980f-4af7-4db4-8bd2-36f667c99ccb.png)
A linear regression was conducted to determine if the mpg could predict the values of the other variables (length, weight, spoiler, clearance, and AWD). 
Length, and clearance provided a non-random amount of variance to the mpg values in the data set. 
The slope of the linear model , shows an adjusted R^2 (being used as this model has more than 1 variable) of 0.68. 
In general, this model of MechaCar prototypes not predict mpg, although it is clear that length, and clearance are the most predictive variables. The variables of spoiler, AWD, weight r values are not less than .05 and as such would not be considered statitically predictive of mpg. 

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils are not to have a variance of more than 100 pounds per square inch. Here the question is which manufacturing lots meet that specification. The first image here, shows the total summary statistics for all lots, showing less than 100 psi of variance per square inch. 
![image](https://user-images.githubusercontent.com/89048287/145719872-38fb2e5e-1a1d-4e9a-8472-20307d1ba145.png)
However, here, the summaries of the three lots can be seen, indicating that lot 1 and 2 are under 100 pounds of variance per square inch, while lot 3 is over that range at 170.29 pounds of variance per square inch. 
![image](https://user-images.githubusercontent.com/89048287/145719461-865ec88f-6038-435b-b29a-a32e2257d800.png)

## T-Tests on Suspension Coils
A T-Test was conducted on all manufacturing lots against the mean psi of the population (1500). The p value for this test was .06. In general, as the value is not equal to or less than .05, we would determine that the mean may indeed be equal to 1500. 
![image](https://user-images.githubusercontent.com/89048287/145719943-a0ab8d5a-75a3-4b9d-8eb7-a5898c9ae738.png)
Three additional T-Tests were then conducted to determine if there was a significant difference in the mean psi from each manufacturing lot to the population mean. Lot 1 and 2 were not signigicantly different from the population mean, however lot 3 was. This would continue to support manufacturing issues at Lot 3, due to the extreme variance of the lot and it's variance from the population mean. 
![image](https://user-images.githubusercontent.com/89048287/145720045-121a2c1f-d5a7-4ddf-b8ba-2856dd9cec86.png)

## Study Design: MechaCar vs. Competition
Following this exploritory analysis, a following research study would be required to determine whether MechaCar does perform better than it's competition. 
The following hypotheses were defined for this reseach: 

  ### Hypotheses: Null and Alternative
  * The Alternative Hypothesis of this research is that the MechaCar performs better than it's competition. 
  * The Null Hypothesis is that there is no statistical difference between the MechaCar and it's competion. 

  ### Metrics to be tested
  To test this hypothesis, the following metrics will be used: cost of vehicals, fuel efficiency (including city and highway), horse power, safety ratings, and general user ratings of the vehical after owning for 2 years. 
  ### Statistical tests to be conducted
To test these variables, the following tests will be conducted:
  * A two sample T-Test will be conducted on each of the following variables of MechaCar and that of a sample of competitors: Cost, Fuel Efficiency (city and highway), horse power, safety ratings, and general user ratings. The means should be statistically different and greater than the competition to determine if MechaCar is better than it's competition. 
  * A multiple linear regression would be conducted to determine if the variables of cost, fuel efficiency, horse power and safety ratings accounted for user ratings. In general, the alternative hypothesis will be retained if the user rating is statistically higher (determined by the two sample T-Test) than that of it's competitors, but additional tests will also show areas of strength and weaknesses of design. 
  ### Data Collection
  The data needed to conduct these tests would need to be a large, representative sample of car owners, both of MechaCar and it's competitiors. This should vary in ownership location and owner demographics. 

The following tests will test the hypothesis: 
The metric to be tested is mentioned. 
The data for the statistical test is described. 
  
