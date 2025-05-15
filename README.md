# MTA-Regression-Analysis
This analysis looks to use the MTA's Subway Customer Journey data, which records train progress data for each train in the MTA system on a daily basis. The focus of this analysis is to predict 'customer journey time performance', defined as the percent of customers with journeys completed within 5 min of scheduled time.

The included features are:

month - The month in which the metrics are being calculated (yyyy-mm-dd).

division - The A Division (numbered subway lines and S 42nd) and B Division (lettered subway lines).

line - Each subway line (1, 2, 3, 4, 5, 6, 7, A, C, E, B D, F, M, G, JZ, L, N, Q, R, W, S 42nd, S Rock, S Fkln).

period - Represents both the peak and off-peak service periods.

num_passengers - Total number of estimated passengers reported each month and on each line.

additional platform time - The average estimated additional time in minutes (above scheduled time) customers wait for their train, reported each month and on each line.

additional train time - The average estimated additional time in minutes (above scheduled time) customers spend  onboard a train, reported each month and on each line.

total_apt - The total number of estimated additional time in minutes (above scheduled time) customers wait for their train, reported each month and on each line

total_att - The total number of average additional time in minutes (above scheduled time) customers spend onboard a train, reported each month and on each line.

over_five_mins - The estimated total number of customers whose journeys are not completed within 5 minutes of the  scheduled time, reported each month and on each line.

over_five_mins_perc - The estimated percentage of customers whose journeys are not completed within 5 minutes of the scheduled time, reported each month and on each line.

customer journey time performance - The estimated percentage of customers whose journeys are completed within 5 minutes of the scheduled time, reported each month and on each line


Regression models used (see notebook for reasoning for their use) are: simple linear regression, robust regression, best subset regression, Ridge regression, LASSO regression.
