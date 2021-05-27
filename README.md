# data612
Repository for Data Mining assignments 

In Homework #2, I created a new file in Google Colabratory and did the following:
1. I loaded the stocks_yahoo dataset from https://raw.githubusercontent.com/frankData612/data_612/master/stock_data/stocks_yahoo.csv using the Pandas read_csv function.
2. I printed the first 5 records of the dataset using the DataFrame head() function.
3. I found the max date of the 'date' field by calling the max() function.
4. I subtracted the date in each record from the max date found in the previous step.
5. I converted the number of days difference found in the previous step to months by using the timedelta64() function.
6. I saved the results of the months conversion to a new column in the dataset.
7. I saved the updated dataset to a CSV file and I also read in the new CSV file to verify the new column was added properly.


In Homework #1, I created a new file in Google Colabratory and did the following:
1. I loaded the stocks_yahoo dataset from https://raw.githubusercontent.com/frankData612/data_612/master/stock_data/stocks_yahoo.csv using the Pandas read_csv function.
2. I printed the first 10 records of the dataset using the DataFrame head() function and passing in 10 as a parameter.
3. I printed the last 10 records of the dataset using the DataFrame tail() function and passing in 10 as a parameter.
4. I printed the column names by calling the columns attribute from the DataFrame.
5. I printed the type of the dataset by calling the type() function and passing in the reference to the dataset.
6. I printed the number of rows and columns by calling the shape attribute on the dataset object.
7. I used the groupby() function to find the mean of the "price_at_close" column in the dataset.
