# Simultaneous Estimation of Multi-state Multiple Systems Data

This repository contains the code and data files for executing the data analysis.

The data required for our data analysis is divided into two categories: (a) Roamer  (b) Seater. These datasets contain TRS data for 16 administrative regions of Ghana and are stored as csv files named 'Roamer_Data.csv' and 'Seater_Data.csv'. These must be read in the beginning of the data analysis code by updating their file path accordingly.

The data analysis codes are as follows:

1.FSW_HIV Code_Jeffrey(Roamer): Data Analysis code under Prior I for Roamer FSW.

2.FSW_HIV Code_Binomial(Roamer): Data Analysis code under Prior II for Roamer FSW.

3.FSW_HIV Code_Jeffrey(Seater): Data Analysis code under Prior I for Seater FSW.

4.FSW_HIV Code_Binomial(Seater): Data Analysis code under Prior II for Seater FSW.

Each of these codes will reproduce required estimates, trace plots and significance plots.

If the user wishes to use this code for a different dataset they may do so by replicating the dataset in the form of TRS (as shown in the above mentioned csv files) and may tune the parameters accordingly in the code.
