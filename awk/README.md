The input data for all exercises is stored in `data.txt`.

# Exercises

## 1. Print all data

**Task**: Print all the data from data.txt.

**Expected Output**: see `expected_output/1.txt`

**Solution**: `awk '{print}' data.txt`


## 2. Print a specific column

**Task**: Print only the `Name` column from the data.

**Expected Output**: see `expected_output/2.txt`

**Solution**: `awk -F',' '{print $2}' data.txt`


## 3. Print employees with salary greater than $70,000

**Task**: Print the entire row for employees who have a salary greater than $70,000.

**Expected Output**: see `expected_output/3.txt`

**Solution**: `awk -F',' '$5>70000 {print}' data.txt`


## 4. Print employees in the Engineering department

**Task**:  Print the Name and Position of employees who are in the Engineering department.

**Expected Output**: see `expected_output/4.txt`

**Solution**: `awk -F',' '$3=="Engineering" {print $2, $4}' data.txt`


## 5. Calculate the total salary for all employees

**Task**: Calculate and print the total salary of all employees.

**Expected Output**: see `expected_output/5.txt`

**Solution**:
```awk
BEGIN { total_salary = 0 }
{ total_salary=$5+total_salary } 
END { printf "Total Salary: %s\n", total_salary }
```

## 6. Calculate the number of employees in each department

**Task**: 

**Expected Output**: see `expected_output/6.txt`

**Solution**:
```awk
```

## 7. Count the number of employees in each department

**Task**: Count and print the number of employees in each department.

**Expected Output**: see `expected_output/7.txt`

**Solution**:
```awk
```

## 8. Find employees with the longest years of service

**Task**: Print the `Name` and `Years_of_Service` of the employee(s) with the longest years of service.

**Expected Output**: see `expected_output/8.txt`

**Solution**:
```awk
```

## 9. Print all employees sorted by their salary in descending order

**Task**: Print all employee records sorted by their salary in descending order.

**Expected Output**: see `expected_output/9.txt`

**Solution**:
```awk
```

## 10. Format the output to a table

**Task**: Print the data in a formatted table layout with headers.

**Expected Output**: see `expected_output/10.txt`

**Solution**:
```awk
```
