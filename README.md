## Primary project objective
- Investigate the primary factors influencing used vehicle prices via multiple linear regression analysis. Partial regression plots, optimal transformations of dependent and indepenant variables, and stepwise variable selection are also explored.   

## Primary language

- R

## Highlighted visualizations
- (below) Correlation and estimated density plots for price (response) and selected continuous predictors.  Note that these plots included the optimal transformations for revealing linear relationships. 

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-regression/main/figures/EDA_selection_cont.png" width=675>

- (below) bar plots, box plots, and other plots for exploring the relationship between price (response) and selected discrete predictors.  Note that price is already on the log scale, and that many discrete variables have been recoded from their raw form (i.e., body styles and colors aggegated into fewer groups).

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-regression/main/figures/EDA_selection_discrete.png" width=675>

- (below) Added variable plots, otherwise known as partial regression plots. These plots attempt to show the effect of adding a new variable to an existing model by controlling for the effect of the predictors already in use.

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-regression/main/figures/partial_regression_plots.png" width=675>

- (below) An inverse response plot showing the optimal power transformation for the response (black line) given the model specification. Other common power transformations are also displayed.  In the final model, although not technically optimal, a power transformation of 0 (equivalent to a transformation to the log scale) is used for model parsimony.

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-regression/main/figures/inverse_response_plot.png" width=675>

- (below) Scatterplots between select predictors and the response variable, before and after transformations.  Illustrates the improved linearity of these relationships achieved from variable transformations. 

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-regression/main/figures/before_after_transformations.png" width=675>

- (below) Useful plots derived from stepwise variable selection. The left panel shows the incremental effect of increasing the number of predictors in the model (BIC bottoms out around 9 predictors).  The right panel shows which variables were present in each model assessed, organized in ascending BIC order.

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-regression/main/figures/variable_selection.png" width=750>
