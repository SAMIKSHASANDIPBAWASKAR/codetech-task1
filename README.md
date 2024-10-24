# codetech-task1
<h1>INPUT</h1>
import pandas as pd

# Step 1: Load the data
data = pd.read_csv('data.csv')

# Step 2: Display the original data
print("Original Data:")
print(data)

# Step 3: Clean the data by removing rows with missing values
cleaned_data = data.dropna()

# Step 4: Display the cleaned data
print("\nCleaned Data:")
print(cleaned_data)

# Step 5: Calculate the average salary
average_salary = cleaned_data['salary'].mean()

# Step 6: Display the average salary
print("\nAverage Salary:")
print(average_salary)
<h1>OUTPUT</h1>



Original Data:
      name   age   salary
0    Alice  30.0  70000.0
1      Bob  25.0  80000.0
2  Charlie   NaN  75000.0
3    David  40.0      NaN
4      Eve  35.0  90000.0

Cleaned Data:
    name   age   salary
0  Alice  30.0  70000.0
1    Bob  25.0  80000.0
4    Eve  35.0  90000.0

Average Salary:
76666.66666666667








