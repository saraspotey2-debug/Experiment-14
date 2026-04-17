# Experiment-14
# Aim
Data Binning And Data Formatting Using Python.
# Theory
1. Data binning in python is the process of grouping continuous data into discrete intervals (bins) to simplify analysis.
2. Data formatting in python means converting data into a structured or desired format (like changing data types, date formats, or number styles) for easier analysis.
3. import pandas- This line imports the pandas library.Pandas is used for data handling and analysis.
4. import numpy- This line imports the NumPy library to perform numerical and array operations in python.
5. pd.DataFrame-It is used to create a structured table (rows and columns) from data like lists, dictionaries, or arrays.
6. df['Price_Category'] = pd.cut(df['Price'], bins=bins1, labels=labels1)- It categorizes the Price values into defined bins with given labels.
7. print(df.dtypes)-It displays the data types of each column in the dataFrame using pandas.
8. df['Units_Sold']= df['Units_Sold'].astype(float)-It converts the Units_Sold column to float data type.
9. df['Product'] = df['Product'].str.upper()-It converts all values in the Product column to uppercase.
10. df['Price'] = df['Price'].round(2)-It rounds the Price values to 2 decimal places.
11. sorted_df=df.sort_values (by='Price')-sorted_df=df.sort_values (by='Price').
12. sorted_df1=df.sort_values(by='Price',ascending=False)-It sorts the dataFrame in descending order based on the Price column.
13. print(df['Price_Category'].unique())-It returns all unique values in the Price_Category column.
14. 
