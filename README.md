## Readme


### Requirements
matplotlib: 2.2.2
numpy: 1.16.3
pandas: 0.23.0
scikit-learn: 0.21.2


### Program Structure
(1) Data pre-processing: 
	- data preparation
	- training/testing data split
	- plot feature distribution
	- modify features
	- one-hot encoding
	- plot data correlation and importance
	
(2) Basic Model: 
	- check model performance with no tuning
	
(3) Looking into the parameters:
	- check how parameter affects each model's performance and plot them
	
(4) Model tuning:
	- Use GridSearchCV for parameter tuning to achieve best performance
	
(5) Plotting the best performance:
	- Plot test accuracy and AUC for each model optimized by GridSearchCV


### Run
(1) Open Jupyter notebook and run all the cells in project.ipynb
(1) If you want to run the model with modified features (removed features), please make sure to change the flag in 'FEAT_MOD' from 'False' (default value) to 'True' and RERUN all the cells 