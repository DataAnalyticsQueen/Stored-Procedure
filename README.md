# Stored-Procedure---Stored Procedures in SQL 

DELIMITER $$
CREATE PROCEDURE:Large_salaries2()
SELECT *
FROM employee_Salary;

WHERE salary > 50000;
CREATE PROCEDURE  large_salaries()
SELECT *
FROM Employee_salary
WHERE salary >= 50000;
END $$ 
DELIMETER ;
CREATE PROCEDURE large_salaries2()
BEGIN 
    SELECT *
	FROM employee_salary 
	WHERE salary = 50000
	SELECT * 
	FROM Employee_salary
END $$
DELIMETER;

CALL large_salaries 3();





