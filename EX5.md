# Ex. No: 5 Creating Triggers using PL/SQL

### AIM: To create a Trigger using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create salary_log table with following attributes (log_id NUMBER GENERATED ALWAYS AS IDENTITY, empid NUMBER,empname VARCHAR(10),old_salary NUMBER,new_salary NUMBER,update_date DATE);
3. Create a trigger named as log_salary-update.
4. Inside the trigger block, Insert the values into the salary_log table whenever the salary is updated.
5. End the trigger.
6. Update the salary of an employee in employee table.
7. Whenever a salary is updated for the employee it must be logged into the salary_log table with old salary and new salary.
8. Display the employee table, salary_log table.

### Program:
### Create employee table

![Screenshot 2023-10-19 142151](https://github.com/vidhyadharan-03/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/114286357/cf856b4b-1dd6-4a26-975e-03d20d6ce4c3)

### Create salary_log table


![Screenshot 2023-10-19 142618](https://github.com/vidhyadharan-03/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/114286357/defb7458-3797-4e53-b2fd-98e4997bd1a6)


### PLSQL Trigger code

![Screenshot 2023-10-19 143829](https://github.com/vidhyadharan-03/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/114286357/f235781c-190c-432f-9522-e5185f0d37b1)



### Output:

![dbms](https://github.com/vidhyadharan-03/Ex-No-5-Creating-Triggers-using-PL-SQL/assets/114286357/deef767f-7dfe-408d-9d04-5af9c00a4050)



### Result:
Thus the trigger using pl/sql has been created sucessfully.
