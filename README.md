                Data Exploration Summary:
The dataset contains 148 rows and 6 columns: Company, Age, Salary, Place, Country, and Gender.
Missing values are present in Company, Age, Salary, and Place columns.
The Gender column is stored as integers (likely encoded as 0 and 1).
Age and Salary are numerical columns, while Company, Place, and Country are categorical

             Unique Value Counts:
Company: 6 unique values
Age: 29 unique values
Salary: 40 unique values
Place: 11 unique values
Country: 1 unique value (only one country present)
Gender: 2 unique values
Since Country has only one unique value, it doesn't contribute to the analysis and can be dropped
                                   Updated Missing Value Counts:
Company: 8 missing values
Age: 24 missing values (after replacing 0 with NaN)
Salary: 24 missing values
Place: 14 missing values
Country: No missing values (but only 1 unique value, so can be dropped)
Gender: No missing values
                  Missing Values Treated Successfully!
All missing values have been replaced appropriately:
Age & Salary: Replaced with median.
Company & Place: Replaced with mode.
Country column removed (since it had only one unique value).
                       Duplicate Rows Removed:
4 duplicate rows were removed from the dataset.
