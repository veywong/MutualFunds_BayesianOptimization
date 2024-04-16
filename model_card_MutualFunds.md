# Model Card

## Model Description

**Input:** 
total_net_assets = total net assets of a mutual fund
fund_year3_expense_projection = projected fund expenses in 3 years
fund_year5_expense_projection = projected fund expenses in 5 years
fund_year10_expense_projection = projected fund expenses in 10 years
morningstar_return_rating = Morningstar rating on a mutual fund's return
sustainability_score = sustainability score of a mutual fund
sustainability_rank = sustainability rank of a mutual fund
esg_score = ESG score of a mutual fund

**Output:** 
load_adj_return_3years = 3-year actual return an investor sees after accounting for fees and sales charges are deducted from a mutual fund's performance
load_adj_return_5years = 5-year actual return an investor sees after accounting for fees and sales charges are deducted from a mutual fund's performance
load_adj_return_10years = 10-year actual return an investor sees after accounting for fees and sales charges are deducted from a mutual fund's performance

**Model Architecture:** 
Bayesian Optimization from Anaconda

## Performance

The model remained unresolved due to difficulties in converting argument Z into 2 dimentional, despite multiple attempts to redefine and reshape it, resulting in failure to create the 3D Surface Plot. 

## Limitations

There are infinite levels of returns while the number of input variables are limited to just eight. 

## Trade-offs

To improve the results, we should group the return levels in a finite number, as a trade off between bias and accuracy of the model.    
