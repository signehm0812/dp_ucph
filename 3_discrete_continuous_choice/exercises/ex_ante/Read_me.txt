*******************************************************************************************
* 1. Functions for solving, simulating, and estimating the buffer-stock consumption model *
*******************************************************************************************

py-files:
tools.py: basic functions for finding GaussHermite nodes, interpolation, statespace etc.
model.py, egm.py, utility.py: functions for setting up model, solving it and simulating from it
estimate.py: functions for estimating the model

ipynb-files:
01_discrete_continous_choice: solve discrete and continous choice model using VFI
02_time_iteration: solve continous choice model using time iteration
03_buffer_stock_egm: solve and simulate the buffer-stock model with life-cycle using EGM
04_estimate_buffer_stock: Estimate rho and beta in the buffer-stock model 
05_dc_egm: solve the model


********************************************************************************************
* 2. Functions for solving a consumption-saving model with a discrete absorbing retirement *
********************************************************************************************

py-files:
tools.py: basic functions for finding GaussHermite nodes, interpolation, statespace etc.
model_dc.py, egm_dc.py: functions for setting up the model and solving it
model_dc_multidim.py, egm_dc_multidim: functions for setting up and solve a model with permanent income

