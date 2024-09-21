**Data Processing Task**
**Overview**
This project involves loading data from a provided CSV file into a Pandas DataFrame, cleaning and transforming the data, and performing statistical analysis. 
The final cleaned data will be saved into a new CSV file.

**Requirements**
Python 3.x
Pandas library
NumPy library

**Usage**
Place your CSV file in the same directory as the script.
Modify the script to specify the input file name and output file name if necessary.

**Steps**
1)Load Data
Load the CSV file into a Pandas DataFrame.

2)Remove Duplicates
Identify and remove any duplicate entries in the DataFrame.

3)Clean Age Column
Remove any decimal places in the "Age" column, ensuring it contains only integer values.

4)Convert Currency
Convert salaries from USD to EGP (Egyptian Pound). Use a predefined conversion rate, you can adjust this value as necessary.

5)Statistical Analysis
Calculate and print the following statistics to the console:
Average age of employees.
Median salary of employees.
Ratio of male to female employees.

6)Save Cleaned Data
Write the cleaned DataFrame to a new CSV file.

**Notes**
Ensure that the input CSV file has the required columns: "Age," "Salary," and "Gender."
Adjust the currency conversion rate based on current values for accuracy.
