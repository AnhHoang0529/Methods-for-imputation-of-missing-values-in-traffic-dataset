# Methods-for-imputation-of-missing-values-in-traffic-dataset

Dataset collected from Transport Infrastructure Ireland (TII) traffic counters located on the road network of Ireland as the basis for analysis. 
Dataset includes 4 traffic stations and 1 weather station collected hourly from 1/1/2020 to 31/12/2020
![image](https://user-images.githubusercontent.com/125748873/219922302-a2afb764-1e3d-40f5-93c5-0f445433d0df.png)
- Traffic attributes:
![image](https://user-images.githubusercontent.com/125748873/219922410-fc458354-084a-43d7-8175-edfa4cbdc16e.png)
- Weather attributes:
![image](https://user-images.githubusercontent.com/125748873/219922422-0dad8516-fce8-4a21-98c9-c84b4bd854aa.png)

This study compares 7 methods to imputated continously missing values: 
Linear Interpolation, SMA (Simple Moving Average), EMA (Exponential Moving Average), SMWA (Seasonal Moving Window Average), KNN, MICE (Random Forests with Multiple
Imputation by Chained Equations), DTWBI (Dynamic Time Wraping - Based Imputation)
![image](https://user-images.githubusercontent.com/125748873/219922500-f13f2b92-86b1-4bc3-b42a-1351cfccc5e9.png)


