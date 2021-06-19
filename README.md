# data612
Repository for Data Mining assignments 
In Homework #5, I converted three of the stocks_yahoo features to different data types:
1. I loaded the stocks_yahoo dataset from https://raw.githubusercontent.com/frankData612/data_612/master/stock_data/stocks_yahoo.csv using the Pandas read_csv function.
2. I printed the data types from the original data frame.
3. I then converted the 'price_at_close' feature from a float to a category data type and printed all of the data types.
4. After that I converted the 'no' feature from an int to a string and printed all of the data types.
5. Finally, I converted the 'volume' feature from a string to a float by including the 'coerce' attribute in the Pandas to_numeric() function.

In Homework #4, I concatenated two data frames and then removed the rows with missing values:
1. I loaded the stocks_yahoo dataset from https://raw.githubusercontent.com/frankData612/data_612/master/stock_data/stocks_yahoo.csv using the Pandas read_csv function.
2. I manually created a new data frame with one row that matched the structure of the stocks_yahoo dataset.
3. I concatenated the two data frames using the pd.concat() method.  I included ignore_index=True so the new data frame would have a contiguous index.
4. I counted the number of rows in the data frame.
5. I then calculated the number of rows with missing data by subtracting the number of rows with missing values from the total number of rows.
6. Finally I dropped the rows with missing values by calling the dropna() method on the data frame.

In Homework #3, I created three Seaborn plots:
1. I loaded the stocks_yahoo dataset from https://raw.githubusercontent.com/frankData612/data_612/master/stock_data/stocks_yahoo.csv using the Pandas read_csv function.
2. I converted the string 'date' variable into a new datetime field.  
3. The first plot, I created a new Data Frame with the Apple stock entries and used a Line plot to display the value of the Apple stock over a period of time. I used the date on the x-axis and the closing price on the y-axis.
4. With the second plot, I pulled all of the records from April 28, 2020 into a new Data Frame and used a Bar plot to display the stock price values for the top 5 stocks that day.
5. On the third plot, I created a new variable named 'daily_return' and populated it with the difference between the previous closing price and the current closing price.  I then used a histogram to show a distribution of daily returns for the Apple stock.


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
