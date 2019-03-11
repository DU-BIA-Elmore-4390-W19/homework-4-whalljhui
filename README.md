# Homework-4
Homework 4: Chapter 8 work
Name: Will Hall

 
## Problem 1 

37 #Conclusive Random Forest with Corresponding MSEs:

74 #Graphical Display:

82 #Model Interpretation:
Through this model, 5 appears to be the best random predictor variable limit for random forests. The display shows 5’s corresponding MSE values stay consistently lower relative to other limits. And from the lab, even though higher limits display lower MSEs through cross-validation, it is my intention to avoid overfitting. So after interpreting the model above, and also keeping in mind the cross-validation run, 5 is the ideal mtry.

88 #Fitting the model with the best random predictor variable (5):

104 #Test MSE for 5:
MSE = 5.754378

110 #Understanding variable importance through the best random predictor variable (5):


## Problem 2

149 #Loading Data:

155 #Splitting Training and Validating Set:

165 #Fitting a Regression Tree to the Validation Data:

172 #Summary and Plot

180 #MSE for Tree:
MSE = 4.484515

187 #Cross-validation for Carseats Using Random Forest

199 #Plotted Random Forest CV

206 #Test MSE for Random Forest: mtry = 4
MSE = 3.281054
I chose 4 based on 5's small relative gain in R2, and small relative drop in RMSE to 4. Using mtry = 4 within random forest, compared to the initial tree regression, ends up lowering the test MSE from 4.48 to 3.28.

232 #Variable Importance:

240 #Graphical Representation of Variables via Best rf mtry (4):

263 #Bagging Approach:

271 #Estimating the Bagged MSE:
MSE = 3.040513

283 #Importance of Bagged Variables:

293 #Gradient-boosting Approach:

312 #Graphical Representation of Gradient-boosted Tree (mtry = 6):

318 #MSE for Gradient-boosted Tree:
MSE = 1.776613

332 #Training a Multiple Regression (OLS):

378 #MSE for OLS Model:
MSE = 1.012709

350 #Gradient-boosted Tree vs. OLS Model MSE Results:

The OLS Model actually has a lower MSE than the Gradient-boosted Tree model. This result demonstrates that more simple models should not be discounted in lieu of so many other complex instruments. Context and simple model comparisons must also play a key role in  choice. 

