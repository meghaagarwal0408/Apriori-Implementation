_____________________________________________________________________________________________
Name - Megha Agarwal

Roll No - 201506511

Course - M.Tech - CSIS (IInd Year)
_____________________________________________________________________________________________

============================================================================================
APRIORI IMPLEMENTATION
============================================================================================

============================================================================================
Files Required:
============================================================================================

input.csv: Input data file will be a comma separated (.csv) file, containing one transaction 
per line. The location of the input file will be against the key “input” in the config file. 
 
output.csv: The final output of frequent itemsets and association rules are written in the 
output file provided in config.csv file.


config.csv: 
input,$PATH
output,$PATH
support,value
confidence,value
flag,0 or 1
The values of the support and confidence parameters will lie in the range [0,1].
if flag==0 : Only frequent items are printed, both otherwise

Note: config.csv has to be in the folder where the code is present.

============================================================================================
How to Run the Code:
============================================================================================

To run the code : python filename.py
To get the idea of running time : time python filename.py

============================================================================================
Scalability and Time Complexity of the Code:
============================================================================================
Time complexity:
The code runs in 0.551 sec for a sample 10 MB dataset with 1 lac plus transactions.

Scalability:
The code is scalable to large dataset. The entire file is not saved in memory rather the 
required information is fetched from the file, while reading it. Hence the code is space
efficient as well.
_____________________________________________________________________________________________



