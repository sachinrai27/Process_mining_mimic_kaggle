# Process mining mimic kaggle
The jupyter notebook contains code to perform process mining on an open-source mimic dataset present on Kaggle.
It performs below steps:
# Step1: #
Required files are loaded and converted to dataframe object.
# Step2: #
Each dataframe is labelled with their respective activities by melting teh dataframe on the basis of timestamp. Post this all the dataframes are concatednated and joined with patients file to obtain analysis at gender granularity as well. This helps in creating an event log.
# Step3: # 
Exploratory data analysis (EDA) is performed at various granularities. Pivot dataframe is created to further analyse the event log.
# Step4: #
Process mining algorithm(here hueristic miner) is applied and furtejr visualised.

