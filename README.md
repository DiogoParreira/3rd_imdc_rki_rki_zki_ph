Collaborators:
- Benjamin Bangert
- Christopher Irrgang 
- Diogo Parreira
- Jakob Genger
- Luis Fernando Ruiz
- Sten de Schrijver
- Melina Voss


Repo structure :
  Each model has its folder within the model folders

Data used:
  Raw data obtained from the mosqlimate platform 

Data was aggregated to State level and a function to produce train and test dataset for each validation dataset was created - data_factory 

Each model used its own data preprocessing and manipulation to adequately use the model architecture 

models used :
  - geo_lstm
  - xgboost
  - univariate chronos

Each of the models has its own read me file with a description of the methodological choices in data processing and production of forecast intervals and predictions results. 
