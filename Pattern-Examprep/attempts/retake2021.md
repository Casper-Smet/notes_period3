1a. Cholesterol reduction is proportional to drug dosage, meaning that the greater the dosage, the greater the reduction in cholesterol. Furthermore, I am assuming that men get slightly greater benifit from the drug, though I have no scientific backing for this. Finally, as no drug being administered is unlikely to reduce cholesterol, I'm placing the bias term at 0. **CORRECT-ISH**

cholesterol reduction = 0 + 1.5dosage + 0.5man + 0.25woman
1b. This is assuming there are n clusters centres for k datapoints (e.g. after random initialisation). Step 1: group k datapoints based on their distance to n clusters, where each datapoint matches its closest cluster centre. Step 2: For each group, place the new cluster centre at the mean (center) of the current cluster.  **CORRECT**

1c. Greater dimensionality does two things: it makes your model more complex, and it inadvertently always increases the similarity between two points if the dimensions are sparse. One example is word-count vectors for large scale datasets. Relatively few words are bound to be shared between two texts, most words should be empty. The distance between the two word-count vectors would be small, because most of the counts are overlapping zeroes.  **MAYBE**

1d. SVMs prefer the line with the maximum margin. That is, the greatest distance between the boundary and the closest datapoint. The hope is that this avoids low confidence in classification. **LOOK AT THIS ONE**  **MAYBE AGAIN**

2a. 1/2 sum((3.70 + dm*0.66) - pr)^2  **PARTIAL AGAIN, SSE, I DID SE INSTEAD OF SSE**  
2b. The coefficient indicates that the data mining grade is, on average, higher than the pr exam. Odds are you'll have a slightly lower grade on pattern recognition. **WRONG, think in local scale next time**  
2c. 61%, as the r-squared of the model indicates the total variation explained by the regression model **CORRECT**   
2d. 3.70 + 5*0.66 = 7 **CORRECT**  
2e. 7.33 = 3.70 + dm * 0.66, 3.63 = dm * 0.66, dm = 3.63/0.66 = 5.5 **RIGHT METHOD WRONG MATH**  

3a. Investors and men are very likely to respond to the email. However, the dataset might also be unbalanced, as perhaps the mailing list is mostly men/investors, or most investors are men. **CORRECT**
3b. -2.49 + 0.95 + 0.07*30 - 0.07(30^2/100) = -0.07, exp(-0.07) / (1 + exp(-0.07)) =~ 0.48 **CORRECT**  
3c. The second age term punishes people who are too old. People build up capital for investment, but are eventually too old to be interesting. Alternatively, above a certain age these people do not know how email works. It's probably a combination of these two factors. The sweet spot lies at 50. **CORRECT**
3d. All coefficients except for the intercept, as the Pr(>|z|) (confidence level) is smaller than alpha. **CORRECT, maybe they'll take points for intercept**  

4a. sigmoid(z) = 1/(1+e^-z). The exponent is expensive to calculate, not zero centered
4b. 

points
1a. 5/5
1b. 5/5
1c. 2/5
1d. 5/5
2a. 1/4
2b. 0/4
2c. 4/4
2d. 4/4
2e. 0/4 (3/4 if i could give method)
3a. 5/5
3b. 5/5
3c. 5/5
3d. 4/5
4a.
4b.
4c.
4d.
5a.
5b.
5c.
5d.