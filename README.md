# Simple-Data-exploration-project

This Python script performs an analysis on an employee dataset using various libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The dataset contains information about employees, including their names, ages, teams, positions, and salaries.

Purpose
The purpose of this script is to provide valuable insights into the employee dataset, such as team-wise employee counts, employee counts based on positions, employee distribution across different age groups, and identifying the team and position with the highest salary spending. Additionally, the script generates a scatter plot to visualize the correlation between age and salary.

Libraries Used
The following libraries are utilized in this script:

Pandas: Used for data manipulation and analysis.
NumPy: Used for numerical operations.
Matplotlib: Used for creating basic visualizations.
Seaborn: Used for creating more sophisticated visualizations.
Dataset
The script reads the employee dataset from a CSV file named employee_dataset.csv .The dataset should have the following columns:

Name: Employee name
Age: Employee age
Team: Team to which the employee belongs
Position: Employee's position in the organization
Salary: Employee's salary
The script also adds a new column named 'height' to the DataFrame, which contains random integer values between 150 and 180.

Analysis and Visualizations
Team-wise Employee Count:
The script calculates the count of employees in each team and displays the result along with the percentage distribution.

Employee Count based on Positions:
The script calculates the count of employees in each position and displays the result.

Employee Count in Different Age Groups:
The script categorizes employees into different age groups using predefined bins (20-29, 30-39, 40-49, 50-59, and 60-69). It then counts the employees in each age group and displays the result.

Team and Position with the Highest Salary Spending:
The script groups the dataset by 'Team' and 'Position', calculates the sum of salaries for each group, and identifies the team and position with the highest salary spending.

Correlation between Age and Salary:
The script generates a scatter plot to visualize the correlation between age and salary. The x-axis represents employee age, and the y-axis represents their salary.
