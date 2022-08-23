# Jiaqi_Guo_SDIC_Project_PHAS0077  

## Introduction  
This project is the created for the content of thesis of PHAS0077, the project contains 3 models:
 ARIMA model, univariate LSTM model and multivariate LSTM model. The following sctions will introduce the way to run each model and output results.  

## ARIMA model
The parameters that users can change is mainly the 2 lists: stepwise_list and n_pred_period_list.  

Outputs include the multiple plots with clear naming and the output inside the notebook. We create the variable perf_df to store all the results of possible parameter pairs.  

## Univariate LSTM model
The parameters that users can change is: timestep, range of list of units, list of learning rate, max_trials, EPOCHS, batch_size. All the variables could be found by searching function.

Since the path used in the script is local path, user should be able to amend the path as their local one.

Outputs include the multiple plots with clear naming and the output inside "uni_var_tuner_result\uni_var_WTI", results of each trial are stored in the json file. We create the variable perf_dict to store all the results of trial parameter pairs.  

## Multivariate LSTM model
The parameters that users can change is: timestep, range of list of units, list of learning rate, max_trials, EPOCHS, batch_size. All the variables could be found by searching function.

Also, if users have some usable variables to be added to the model, they could follow the structure in the data loading module.

Since the path used in the script is local path, user should be able to amend the path as their local one.

Outputs include the multiple plots with clear naming and the output inside "multi_var_tuner_result\multi_var_WTI", results of each trial are stored in the json file. We create the variable perf_dict to store all the results of trial parameter pairs.  
