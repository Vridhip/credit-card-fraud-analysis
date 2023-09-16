# credit-card-fraud-analysis
It's a small project to analyze the credit card fraud, given certain input the model will detect if the customer is fraud or not.

The CSV file contains the following features:
NPA Status	
RevolvingUtilizationOfUnsecuredLines	
age	
Gender	
Region	
MonthlyIncome	
Rented_OwnHouse	
Occupation	
Education	
NumberOfTime30-59DaysPastDueNotWorse	
DebtRatio	
MonthlyIncome	
NumberOfOpenCreditLinesAndLoans	
NumberOfTimes90DaysLate	
NumberRealEstateLoansOrLines	
NumberOfTime60-89DaysPastDueNotWorse	
NumberOfDependents	
Good_Bad

Pipeline used:
Loading the data -- splitting the data into train and test -- finding the null values and treating it -- Checking for the Kernel distribution estimators and removing the outliers (YoeJohnson and 5th and 95th std) -- Converting categorical data to numerical data using (OneHot encoding, Ordinal encoding, Label encoding) -- Scaling down the feature value to decrease the GPU utilisation -- 
Feature selection(to check the threshold value of a particular feature) -- Finding the correlation b/w the features -- Hypothysis testing -- Model testing -- Hyper parameter tuning.  


Let me know if you like the project by following me on Github.

Have a nice day
