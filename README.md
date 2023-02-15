# VARMAX-BITCOIN

This repository includes exploratory data analysis and a VARMAX implementation model. This repository is a work in progress. The current results are a good start, but there is room for improvement. For example, there are many outliers in this dataset.

## Notice
**** After further research, many statistical errors were found in this repository *****

1. VARMAX Models are used in cases with multiple endogenous variables, but the goal here is to have one endogenous variable and several exogenous variables in the model.
2. This means a SARIMAX model is better suited for the task. 
3. Additonally, even in a case where a VARIMAX model is more appropriate, the metrics used in this model would not all have been endogenous to eachother. 
4. There are VARMAX models that can incorporate exogenous regressors but more consideration is needed in order to confirm each exogenous regressor is in fact exogenous to each endogenous regressor in the model. 



