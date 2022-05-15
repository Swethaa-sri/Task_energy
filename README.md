# Task_energy

Project Title : Energy Efficiency
Domain : Industrial Automation

Problem Statement:
The effect of eight input variables (relative compactness, surface area, wall area, roof area, overall height, orientation, glazing area, glazing area distribution) on two output variables, namely heating load (HL) and cooling load (CL), of residential buildings is investigated using a statistical machine learning framework. 
Using classical and non-parametric statistical analytic tools analyze the strength of each input variable's correlation with each of the output variables in order to discover the most strongly associated input variables. 
We need to estimate HL and CL, we can compare a traditional linear regression approach to a sophisticated state-of-the-art nonlinear non-parametric method, random forests.


Tools Used:
Python
Matplotlib
Seaborn
Sklearn


Approaches:
EDA done on all features
Splitting of data into train and test set 
Standardisation
Performing cross validation on Linear Regression and Random Forest Regressor
Feature Selection
Prediction of Target on Test set.

EDA Insights:
1) Relative Compactness, Overall Height ==> show positive effect on Cooling Load while Surface Area shows inverse effect on Cooling Load.
2) Wall Area, Glazing Area ==> show positive effect on Heating Load.
3) Roof Area ==> shows almost same (inverse)effect on both Heating Load and Cooling Load.
4) Orientation, Glazing Area Distribution shows no effect on both Heating Load and Cooling Load.

Best ML Model:
Cross validation score of Linear Regression : 90.06
Cross validation score of Random Forest Regressor : 97.58
Random Forest Regressor is the best for predicting Cooling Load and Heating Load.

['Relative Compactness', 'Surface Area', 'Wall Area', 'Roof Area', 'Glazing Area', 'Glazing Area Distribution_0']==> with these selected features random forest regression shows R-squared value of 0.98 which is very close to 1.







