# XGBoost


Tennessee Eastman process was developed by Eastman Chemical company to deliver a realistic industrial application process for assessing process control and monitoring methods.

![alt text](https://github.com/prudhvinathreddymalla/XGBoost/blob/master/TE.png?raw=true)

The TE process has five main unit: a reactor, a condenser, compressor, separator, and stripper. The process has 21 pre-programmed faults. Out of 21, only sixteen faults are known and remaining five faults are unknown.


There are 44 data sets given to us. Out of them, 22 are considered as training data sets and other 22 data sets. Among these 22, the first data set in both the training and testing data sets the data set named as “d00” and “d00_te” are for normal operating conditions. Remaining are the data sets for faulty conditions for training and testing. Each training data file contains 480 rows and 52 columns. Each testing set contains 960 rows and 52 columns. The 52 columns here are the 52 variables of the TE process. But there are 53 variables in TE process.

Out of 53 variables, there are 12 manipulated variables and 41 measured variables. The data sets have all the 52 variables except Agitation speed because it was not manipulated. A 3 minutes sampling interval time was used to collect simulated data for both training and testing data sets. With 22 different simulation runs the training data sets are collected varying random seed for each run. The d00 data set is generated with no faults and d21 is generated by fixing the valve position of Stream 4 at the steady state position. And remaining 20 faults are generated corresponding to each fault.

The number of observations is the number of rows in each training and testing data set. In training data set, there are 500 observations for d00 fault i.e. in the normal operating conditions. But there are only 480 observations for each fault, which are generated after one hour of the simulation run. The testing data set consists of 960 observations. After 8 hours of simulation run the fault are introduced and testing observations are generated. Before the fault introduction, the normal operating conditions observations are generated.
