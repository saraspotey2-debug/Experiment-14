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
14. df['Order_Value_Category'] = pd.cut(df['Order_Value'], bins=bins, labels=labels)-It categorizes Order_Value into bins with specified labels.
15. df['Delivery_Speed'] = pd.cut(df['Delivery_Time'], bins=bins2, labels=labels2)-It categorizes Delivery_Time into bins with specified labels.
16. df['Distance_km'] = df['Distance_km'].astype(float)-It converts the Distance_km column to float data type.
17. df['Order_Category'] = df['Order_Value_Category'].str.upper()-It converts the Order_Value_Category values to uppercase.
18. print(df['Order_Category'].unique())-It returns all unique values in the Order_Category column.
19. print(df['Order_Category'].value_counts())-It counts the frequency of each unique value in the Order_Category column.
20. df.sort_values(by='Order_Value')-It sorts the DataFrame based on the Order_Value column.
# Conclusion
Data binning and data formatting in pandas are important preprocessing techniques that help make raw data more useful and meaningful. Data binning converts continuous values into discrete categories, which simplifies analysis and helps in identifying patterns and trends more easily. On the other hand, data formatting ensures that data is clean, consistent, and in the correct structure by converting data types, standardizing text, and refining numerical values. Together, these techniques enhance data quality, improve accuracy, and make the dataset more suitable for analysis, visualization, and decision-making.
