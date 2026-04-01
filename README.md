Machine Learning with Administrative Data for Energy Poverty Identification in the UK
Lin Zheng and Eoghan McKenna - Reproduction for MSc AI and Sustainable Development
The research explores how machine learning models can leverage adminisative and survey data to improve energy poverty assessment in the UK.
Assignement 1 - Dave Austin

The reproduction is copied using https://github.com/linzzuk/Energy_Poverty_Prediction_paper_EHS_data
That repository contains the code and data for the paper: https://www.mdpi.com/1996-1073/18/12/3054)
The replication code is extracted from: ep_prediction_model.ipynb, and the data from:clean_data.csv

AS THE ASSIGNMENT DETAILS - THE REPLICATION REQUIRED IS FOR ONE TABLE
The table chosen is as the report Section 3 - Results, Table 2, "Model Performance for handling class imbalances"
The code is as the file https://github.com/DaveAUni/EnergyPovertyReproAss1/blob/main/GitEnergyPovertyUpload.ipynb

This can be recreated in Google Colab as the link  https://colab.research.google.com/github/DaveAUni/EnergyPovertyReproAss1/blob/main/GitEnergyPovertyUpload.ipynb
Or by searching Google Colab for:  https://github.com/DaveAUni/EnergyPovertyReproAss1/blob/main/GitEnergyPovertyUpload.ipynb

The code for the table is notated as # COM-1 : Census only model

The Output is:
1 to 4 of 4 entries
Filter

index	Accuracy	Balanced accuracy
Random forest with undersampling	0.7782832433636593	0.7830557036486059
Random forest with balanced class weights	0.7782832433636593	0.7830557036486059
XGBoost with undersampling	0.7797961659791313	0.7803905185994039
XGBoost with scale_pos_weight	0.8286054236398137	0.783107035526954

Other Outputs: are for information only







The original Jupyter Notebook version is also included as file
JupyterNotebookCreatedEnergyPovertyUpload.ipynb
