# covid19-analysis
covid analysis with world happiness data

In this file main objective is to find the relationship between the covid 19 cases with the world happiness index and see if they are related some how.

1.  Firstly the useless columns form both the datasets have to be removed to make data easy to work with.
2. Then visualization of the graph has been done to see the trend and how much information does the curve provide us.
3. The list of "Maximum Infection Rate" is made to calculate the rate at which the infection is rising by taking the derivative of the curve and adding the maximum value of it from the given time period to the list.
4. add this list to the aggregate data frame.
5. Then create an another dataframe of just Country and Max_Infection_Rate.
6. Join both the aggregated date frames to get the final dataframe.
7. apply the Karl Pearson method of Correlation between the features.
8. Finaly ploting every columns data with logrithm of Max_Infection_rate (because of very large values of this column compare to others)


