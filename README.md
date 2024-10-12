# Well-Log-Data-Analysis

In this repository I have tried to present the information that a las file try to provide us. 

## Introduction to a Las File.

Las Files -  (Log ASCII Standard) is a file format which is used to contain and exchange the well logging data across the reservoirs and wells. 
A las file includes - 

Well Information - location and depth, basically the coordinates of the well.

Curve Information - includes the name of specific log data which is recorded like gamma, neutron-porosity etc.

Parameter Information - any additional data related well log data.

Data Section - Here the orginal well log data, arranged in the form of columns. 

## PP_Wells_data

My log data includes the following five logs - 

1. Gamma Ray Log
2. Neutron Porosity Log
3. Sonic Log
4. Deep Resistivity Log
5. Bulk Density Log

probably in the las files abbreviations are generally used, 
so we can refer to 
https://geoloil.com/LasCurveMnemonicsDictionary.php - for log abbrevaiton information

## EDA 

### Correlation Matrix -- 
In order to understand the relation between log data, 
I have plotted both the Pearson and Spearman Correlation Matrix. 

further, I have to take the help of libraries like searborn and matplotlib to construct a diagram of the above correlation matrix.

## Plotting the Curve and Understanding the log-info

I have plotted all the logs and using my own visualisation and interpreted that which region is highly beneficial for the extraction for oil and gas.

Now, you can go through the Well_Analysis pynb file for proper visualisation of my project.
