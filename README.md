# Challenges with data

--CHALLENGE 1: P>N

There is a dataset with 300 random variables (each drawn from [0,1]). A secret algorithm was used to compute a binary target variable based on these data.

The training dataset has 250 rows, and the test dataset has 19,750 rows. The goal is to build a model based on the training dataset that accurately classifies the test dataset. You'll be evaluated using "area under the ROC curve".

Submit a brief report describing your methodology and results. Apply your best model to the 19,750 Target_Evaluate rows and submit the probabilities that each is equal to 1.  The format of this file must be a comma separated values file (.csv) with 19,750 rows, the first column being the row id, the second being the predicted probabilities.


--CHALLENGE 2: FUZZ-OGRAPHY

In this problem, there is an input data set that is nearly three million City/Country pairs. To validate this data use the city name and country code from the free world cities database (http://www.geodatasource.com/download). The output of your program should accurately match each entry to its correct/cleaned city spelling and country code. 

The output file should be distinct data set (no duplicates) provided as a pipe '|' delimited .txt file. The output file should contain five fields: Input_City, Input_CountryCode, Output_City, Output_CountryCode, Output_BlankCity (Yes/No). Other descriptions or Lat Long pairs may be added as additional output fields.

You’ll be evaluated solely on the basis of a correct match percentage—although there'll be bonus points for geo-coding your results!
