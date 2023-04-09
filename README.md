# AT-T
Assignment project

1. set up a python environment with all packages given requirements.txt installed
2. .ipynb files in the root folder can be run using either jupyter or vscode with necessary extension installed
3. data folder contains all data files in csv, pdf, plot, png format related to this assignment 
4. models folder contains all machine learning models trained as part of this assignment in .pkl format

Execution steps:
1. run EDA.ipynb by clicking on run all option. this will create/overwrite "loan_stat_df_nonull_cleaned.csv" file in data folder
2. run all cells in plots.ipynb file. which will show all plots and visualizations which are useful for feature selection. Also creates/overwrites "loan_stat_df_for_training.csv" in data folder
3. run all cells in model_train.ipynb which will train machine learning models and write these models in .pkl format into models folder
4. for consuming this trained model for predicting on test set, place the test_file.csv in data folder and run all cell in model_predict.ipynb file.