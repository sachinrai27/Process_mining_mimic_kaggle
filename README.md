# Process mining mimic kaggle
The Jupyter notebook contains code to perform process mining on an open-source mimic dataset present on Kaggle.
It performs the following steps:
## Step1: ##
Required files are loaded and converted to dataframe objects.
## Step2: ##
Each dataframe is labeled with their respective activities by melting the dataframe on the basis of timestamp. Post-this, all the dataframes are concatenated and joined with the patient file to obtain analysis at gender granularity as well. This helps in creating an event log.
## Step3: ##
Exploratory data analysis (EDA) is performed at various granularities. A pivot dataframe is created to further analyze the event log.
## Step4: ##
The process mining algorithm (here hueristic miner) is applied and further visualized.

