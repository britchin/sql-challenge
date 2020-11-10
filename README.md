# Employee Database: A Mystery in Two Parts
## SQL - Data Engineering, Data Analysis

![SQL_Picture](https://github.com/britchin/sql-challenge/blob/main/Images/sql.png)

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

## Demonstrate Data Modeling by inspecting the provided CSV and sketching an Entity-Relationship_Diagram (ERD)
![ERD](https://github.com/britchin/sql-challenge/blob/main/EmployeeSQL/Employee_SQL_ERD.png)

## Data Engineering 
Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

For the primary keys check to see if the column is unique, otherwise create a composite key. Which takes to primary keys in order to uniquely identify a row.
Be sure to create tables in the correct order to handle foreign keys


## Data Analysis

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_1.png)

2. List first name, last name, and hire date for employees who were hired in 1986.

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_2.png)

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_3.png)

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_4.png)

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_5.png)

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_6.png)

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_7.png)

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

![Questions](https://github.com/britchin/sql-challenge/blob/main/Images/number_8.png)



# Bonus (Optional)
As I've examined the data, I was overcome with a creeping suspicion that the dataset is fake. I surmised that my boss handed me spurious data in order to test the data engineering skills of a new employee. To confirm my hunch, I decided to take the following steps to generate a visualization of the data, with which I will confront your boss

A histogram to visualize the most common salary ranges for employees 
![histogram](https://github.com/britchin/sql-challenge/blob/main/Images/Histogram.png)

A bar chart of average salary by title
![barchart](https://github.com/britchin/sql-challenge/blob/main/Images/BarChart.png)

## Epilogue
Evidence in hand, I marched into my boss's office and presented the visualization. With a sly grin, my boss thanks me for my work. On my way out of the office, I hear the words, "Search your ID number." I look down at my badge to see that my employee ID number is 499942

![emp_ID](https://github.com/britchin/sql-challenge/blob/main/Images/emp_no.png)
