## Bike_sharing_demand
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free


## Table of Contents

- This notebook is divided into the following sections:

- Data Exploration
- Data Visualisation
- Data Preparation
- Model Building and evaluation

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
- The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business 
  plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends.
- Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
  - Which variables are significant in predicting the demand for shared bikes.
  - How well those variables describe the bike demands


## Conclusions
- The initial model has an Adjusted R-squared value of 84.5% which seems pretty good. But we tried to reduce the number of independent features using RFE.
  So we reduced the features from 28 to 15 and then to 10.
- After reducing features with high p-value and high VIF we have only 7 features and now VIF values and p-values seem to be in the permissible range.The Adj R-squared is   79.1% using 7 variables. So, this model explains most of the variance without being too complex. So this will be the final model.
