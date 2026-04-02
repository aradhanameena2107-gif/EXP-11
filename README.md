AIM
To create, load, and analyze datasets using the Pandas library in Python, and to perform basic data inspection and statistical operations on structured data.

THEORY
 1. Introduction to Pandas
Pandas is a powerful Python library used for:
Data manipulation
Data analysis
Handling structured datasets (tables)
It mainly uses DataFrame and Series structures.

 2. Dataset Creation
A dataset can be created using a dictionary in Python.
It is converted into a DataFrame using:

3. Saving Dataset to File
The dataset can be saved as a CSV file using:
df.to_csv("students.csv", index=False)
 
 4. Viewing Dataset
To display dataset:
print(df)

 5. Shape and Size of Data
Number of rows and columns:
df.shape
Total number of elements:
df.size

 6. Data Information
To get data types, columns, and memory usage:
df.info()

 7. Statistical Summary
Provides statistical details like mean, min, max:
df.describe()

 8. Loading Dataset from File
To read CSV file:
df = pd.read_csv('/content/Cars93.csv')

 9. Viewing Top and Bottom Data
First 5 rows:
df.head()
Last 5 rows:
df.tail()

 10. Column Information
To get column names:
df.columns

 11. Random Sampling
To get random rows:
df.sample(5)

 12. Handling Missing Data
To check null values:
df.isnull().sum()

 13. Duplicate Data
To check duplicate values:
df.duplicated().sum()

CONCLUSION
Thus, we successfully created and loaded datasets using the Pandas library in Python. We learned how to:
Create a DataFrame
Save and load CSV files
Analyze dataset structure and statistics
Check for missing and duplicate values
