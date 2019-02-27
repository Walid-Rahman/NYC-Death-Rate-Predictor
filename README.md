# NYC-Death-Rate-Predictor Pipeline

The NYC Death Rate Predictor takes publicly available NYC Data from NYC Open Data to perform a prediction on age adjusted death rate given 
the parameters of sex, race/ethnicity, and leading cause of death for the former two parameters. 

I designed a pipeline that

1) Downloads data from NYC Open Data
2) Transforms that data using Pandas
3) Offers ability to run different version of the data
4) Applies a GBM using xgboost to perform predictions. 


Function_DRP.ipynb	<- Function for reusability
NYC_Death_Rate_Pipeline.ipynb <- Main pipeline

Youtube: https://youtu.be/C3YuUUQ4Nic

