# JavaScript Practice Exercises with Employee Data

This repository contains JavaScript exercises designed to improve your problem-solving skills using an employee dataset. The exercises focus on manipulating and analyzing employee data using fundamental JavaScript concepts like loops, conditions, string manipulation, object manipulation, and arrays.

**Constraints:**
- You are **not allowed** to use **map**, **filter**, **reduce**, or **Object.keys/Object.values/Object.entries**
- Only use `for`, `while`, and standard logic
- Focus on the provided `employees` array object

---

# Table of Contents
- [Easy](#easy)
  - [Basic Data Retrieval](#easy-basic-data-retrieval)
  - [Simple Calculations](#easy-simple-calculations)
- [Medium](#medium)
  - [Employee Data Analysis](#medium-employee-data-analysis)
  - [Department Operations](#medium-department-operations)
  - [Project Operations](#medium-project-operations)
- [Advanced](#advanced)
  - [Complex Data Transformations](#advanced-complex-data-transformations)
  - [Statistical Analysis](#advanced-statistical-analysis)
  - [Search and Grouping](#advanced-search-and-grouping)

---

# Easy

## Easy - Basic Data Retrieval
1. Get the first name of the first employee
2. Get the last name of the last employee
3. Get the department of employee with ID 5
4. Count how many employees are in the array
5. Check if any employee is inactive (isActive: false)

## Easy - Simple Calculations
6. Calculate the average age of all employees
7. Find the employee with the highest salary
8. Count how many employees are in the "Développement" department
9. List all unique department names
10. Check if any employee has no projects assigned

---

# Medium

## Medium - Employee Data Analysis
11. Count how many employees speak English
12. Find all employees who work on "Project Gamma"
13. List employees who have more than 2 skills
14. Find employees whose last name starts with 'L'
15. Calculate the average salary per department
16. Find employees who joined after 2020
17. List employees who speak more than 2 languages
18. Find the most common skill among all employees
19. List employees with a salary above 60000
20. Find the longest-serving employee

## Medium - Department Operations
21. Count how many employees are in each department
22. Find the department with the most employees
23. Calculate the total salary expenditure per department
24. List all positions in the "Marketing" department
25. Find the average number of projects per employee by department

## Medium - Project Operations
26. List all unique project names
27. Count how many employees work on each project
28. Find projects with only one employee assigned
29. List employees who work on multiple projects
30. Find the most popular project (most employees)

---

# Advanced

## Advanced - Complex Data Transformations
31. Create a new array with full names (firstName + lastName)
32. Normalize all names: capitalize first letter, lowercase rest
33. Create initials for each employee (e.g., "JD" for Jean Dupont)
34. Add a new property 'yearsOfService' calculated from joinDate
35. Create an object grouping employees by first letter of last name
36. Build a dictionary of projects with assigned employee names
37. Create a nested structure: departments → projects → employees
38. Reverse all employee names (firstName and lastName separately)
39. Replace all vowels in names with '*'
40. Create a string of all employee emails separated by ';'

## Advanced - Statistical Analysis
41. Calculate the median salary company-wide
42. Find the standard deviation of employee ages
43. Determine salary percentiles (25th, 50th, 75th)
44. Find the correlation between age and salary
45. Calculate the average number of skills by department
46. Find the most common language combination
47. Calculate the average project participation by age group
48. Determine the most frequent first name initial
49. Find the average salary difference between active/inactive employees
50. Calculate the retention rate by join year

## Advanced - Search and Grouping
51. Find employees whose skills include both "JavaScript" and "React"
52. List employees with special characters in their last names
53. Find employees whose email domain is not "company.com"
54. Group employees by number of projects (0, 1-2, 3+)
55. Find employees with anagrams in their names (e.g., "Jean" and "Jane")
56. List employees whose full name contains all vowels
57. Find employees with the same first name but different last names
58. Group employees by the length of their first name
59. Find employees whose last name is a palindrome
60. Create a search function that finds employees by any property value

---

# Bonus Challenges
- Create a function to validate employee data (check for required fields)
- Build a nested object showing employees grouped by department then project
- Simulate a search system that finds employees matching multiple criteria
- Create a promotion eligibility checker based on years of service and performance
- Build a team generator that creates balanced teams based on skills

---

# Notes
- Focus on using only loops and conditions
- Avoid using advanced array methods unless explicitly required
- The employee data structure should remain unchanged
- Try to optimize your code for readability and clarity
