The input data for all exercises is stored in `data.txt`.

# Exercises

1. Print all data
	```
	awk '{print}' data.txt
	```

2. Print the Name column
    ```
    awk -F',' '{print $2}' data.txt
    ```

3. Print employees with salary greater than $70,000
    ```
    awk -F',' '$5>70000 {print}' data.txt
    ```

4. Print employees in the Engineering department
    ```
    awk -F',' '$3=="Engineering" {print $2, $4}' data.txt
    ```

5. Calculate the total salary for all employees
    ```
    BEGIN { total_salary = 0 }
    { total_salary=$5+total_salary } 
    END { printf "Total Salary: %s\n", total_salary }
    ```

6. Calculate the number of employees in each department
    ```
    ```
