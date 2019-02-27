# NYC-Death-Rate-Predictor Pipeline

The NYC Death Rate Predictor takes publicly available NYC Data from NYC Open Data to perform a prediction on age adjusted death rate given 
the parameters of sex, race/ethnicity, and leading cause of death for the former two parameters. 

NYC_Death_Rate_Pipeline.ipynb is the pipeline for the analysis of NYC Death Rate Data: https://data.cityofnewyork.us/Health/New-York-City-Leading-Causes-of-Death/jb7j-dtam

The file: 
1) Downloads data from NYC Open Data.
2) Transforms that data using Pandas.
3) Offers ability to run different version of the data.
4) Applies a GBM using xgboost to perform predictions. 


Function_DRP.ipynb	<- Function for reusability
>> Essentially does every transformation step in NYC_Death_Rate_Pipeline.ipynb, but can be called using a function.


Youtube: https://youtu.be/C3YuUUQ4Nic

Please note that the results shown in the video aren't exactly like the results shown in the python notebook. However, they are very close. This occured due to the nature of the program that uses decision trees. So results will always be similar, but not exactly the same everytime. In the video, I say the max accuracy is 95%, while the code shows 92%. Another run of the data resulted in 93%. 

