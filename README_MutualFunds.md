# MutualFunds_BayesianOptimization 


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
The goal of this optimization is to find a function to maximize medium to long term returns of mutual funds taking into account financial and ESG metrics. 

## DATA
Data was extracted from Kaggle https://www.kaggle.com/datasets/stefanoleone992/mutual-funds-and-etfs, of US mutual funds since inception to 24 November 2021. I cleaned it up with a focus on only 11 columns based on domain expertise to remove irrelavant columns from the dataset and rows with null values deleted, as uploaded to https://github.com/veywong/MutualFunds_BayesianOptimization/blob/main/MutualFunds_complete.csv. Three out of the 11 variables are considered to be output variables, namely load_adj_return_3years, load_adj_return_5years, load_adj_return_10years. 

## MODEL 
Bayseian Optimation method was used. 

## HYPERPARAMETER OPTIMSATION
Hyperparameters adjustment was fully auto. 

## RESULTS
The model remained unresolved due to difficulties in converting argument Z into 2 dimentional, despite multiple attempts to redefine and reshape it, resulting in failure to create the 3D Surface Plot. The root cause may be due to the the fact that there are infinite levels of returns while the number of input variables are limited to just eight. To improve the results, we should group the return levels in a finite number, as a trade off between bias and accuracy of the model.   

