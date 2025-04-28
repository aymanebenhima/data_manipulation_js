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
   - **Function Name**: `getFirstEmployeeFirstName`
   - **Input**: `employees`
   - **Output**: `"Jean"`
   - **Expected Result**: Returns the first name of the first employee in the array.

2. Get the last name of the last employee
   - **Function Name**: `getLastEmployeeLastName`
   - **Input**: `employees`
   - **Output**: `"Leroy"`
   - **Expected Result**: Returns the last name of the last employee in the array.

3. Get the department of employee with ID 5
   - **Function Name**: `getEmployeeDepartmentById`
   - **Input**: `employees, 5`
   - **Output**: `"Marketing"`
   - **Expected Result**: Returns the department of the employee with ID 5.

4. Count how many employees are in the array
   - **Function Name**: `countEmployees`
   - **Input**: `employees`
   - **Output**: `50`
   - **Expected Result**: Returns the total number of employees in the array.

5. Check if any employee is inactive (isActive: false)
   - **Function Name**: `hasInactiveEmployees`
   - **Input**: `employees`
   - **Output**: `true`
   - **Expected Result**: Returns `true` if any employee is inactive, otherwise `false`.

## Easy - Simple Calculations
6. Calculate the average age of all employees
   - **Function Name**: `calculateAverageAge`
   - **Input**: `employees`
   - **Output**: `31.2`
   - **Expected Result**: Returns the average age of all employees.

7. Find the employee with the highest salary
   - **Function Name**: `getHighestPaidEmployee`
   - **Input**: `employees`
   - **Output**: `{ id: 34, firstName: "Paul", lastName: "Leclercq", ... }`
   - **Expected Result**: Returns the employee object with the highest salary.

8. Count how many employees are in the "Développement" department
   - **Function Name**: `countEmployeesInDepartment`
   - **Input**: `employees, "Développement"`
   - **Output**: `15`
   - **Expected Result**: Returns the number of employees in the "Développement" department.

9. List all unique department names
   - **Function Name**: `getUniqueDepartments`
   - **Input**: `employees`
   - **Output**: `["Développement", "Design", "Management", "Marketing"]`
   - **Expected Result**: Returns an array of unique department names.

10. Check if any employee has no projects assigned
    - **Function Name**: `hasEmployeesWithoutProjects`
    - **Input**: `employees`
    - **Output**: `true`
    - **Expected Result**: Returns `true` if any employee has no projects assigned, otherwise `false`.

---

# Medium

## Medium - Employee Data Analysis
11. Count how many employees speak English
    - **Function Name**: `countEnglishSpeakingEmployees`
    - **Input**: `employees`
    - **Output**: `45`
    - **Expected Result**: Returns the number of employees who speak English.

12. Find all employees who work on "Project Gamma"
    - **Function Name**: `getEmployeesByProject`
    - **Input**: `employees, "Project Gamma"`
    - **Output**: `[ { id: 1, firstName: "Jean", ... }, { id: 2, firstName: "Marie", ... }, ... ]`
    - **Expected Result**: Returns an array of employees working on "Project Gamma".

13. List employees who have more than 2 skills
    - **Function Name**: `getEmployeesWithMoreThanTwoSkills`
    - **Input**: `employees`
    - **Output**: `[ { id: 1, firstName: "Jean", ... }, { id: 3, firstName: "Pierre", ... }, ... ]`
    - **Expected Result**: Returns an array of employees with more than 2 skills.

14. Find employees whose last name starts with 'L'
    - **Function Name**: `getEmployeesByLastNameInitial`
    - **Input**: `employees, 'L'`
    - **Output**: `[ { id: 5, lastName: "Leroux", ... }, { id: 8, lastName: "Laurent", ... }, ... ]`
    - **Expected Result**: Returns an array of employees whose last name starts with 'L'.

15. Calculate the average salary per department
    - **Function Name**: `calculateAverageSalaryByDepartment`
    - **Input**: `employees`
    - **Output**: `{ "Développement": 60000, "Design": 50000, ... }`
    - **Expected Result**: Returns an object with average salaries for each department.

16. Find employees who joined after 2020
    - **Function Name**: `getEmployeesJoinedAfterYear`
    - **Input**: `employees, 2020`
    - **Output**: `[ { id: 13, firstName: "Julie", ... }, { id: 18, firstName: "Romain", ... }, ... ]`
    - **Expected Result**: Returns an array of employees who joined after 2020.

17. List employees who speak more than 2 languages
    - **Function Name**: `getMultilingualEmployees`
    - **Input**: `employees`
    - **Output**: `[ { id: 3, firstName: "Pierre", ... }, { id: 5, firstName: "Camille", ... }, ... ]`
    - **Expected Result**: Returns an array of employees who speak more than 2 languages.

18. Find the most common skill among all employees
    - **Function Name**: `getMostCommonSkill`
    - **Input**: `employees`
    - **Output**: `"JavaScript"`
    - **Expected Result**: Returns the most common skill among all employees.

19. List employees with a salary above 60000
    - **Function Name**: `getHighEarningEmployees`
    - **Input**: `employees, 60000`
    - **Output**: `[ { id: 3, firstName: "Pierre", ... }, { id: 8, firstName: "Nicolas", ... }, ... ]`
    - **Expected Result**: Returns an array of employees earning above 60000.

20. Find the longest-serving employee
    - **Function Name**: `getLongestServingEmployee`
    - **Input**: `employees`
    - **Output**: `{ id: 34, firstName: "Paul", ... }`
    - **Expected Result**: Returns the employee who has been with the company the longest.

## Medium - Department Operations
21. Count how many employees are in each department
    - **Function Name**: `countEmployeesByDepartment`
    - **Input**: `employees`
    - **Output**: `{ "Développement": 15, "Design": 10, "Marketing": 12, "Management": 13 }`
    - **Expected Result**: Returns an object with the count of employees in each department.

22. Find the department with the most employees
    - **Function Name**: `getLargestDepartment`
    - **Input**: `employees`
    - **Output**: `"Développement"`
    - **Expected Result**: Returns the name of the department with the most employees.

23. Calculate the total salary expenditure per department
    - **Function Name**: `calculateTotalSalaryByDepartment`
    - **Input**: `employees`
    - **Output**: `{ "Développement": 750000, "Design": 450000, "Marketing": 600000, "Management": 800000 }`
    - **Expected Result**: Returns an object with the total salary expenditure for each department.

24. List all positions in the "Marketing" department
    - **Function Name**: `getPositionsInDepartment`
    - **Input**: `employees, "Marketing"`
    - **Output**: `["Responsable SEO", "Chargée de communication", "Responsable marketing digital", ...]`
    - **Expected Result**: Returns an array of all unique positions in the "Marketing" department.

25. Find the average number of projects per employee by department
    - **Function Name**: `calculateAverageProjectsByDepartment`
    - **Input**: `employees`
    - **Output**: `{ "Développement": 3.2, "Design": 2.5, "Marketing": 1.8, "Management": 2.7 }`
    - **Expected Result**: Returns an object with the average number of projects per employee for each department.

## Medium - Project Operations
26. List all unique project names
    - **Function Name**: `getUniqueProjectNames`
    - **Input**: `employees`
    - **Output**: `["Project Alpha", "Project Beta", "Project Gamma", "Project Delta", "Project Epsilon"]`
    - **Expected Result**: Returns an array of all unique project names.

27. Count how many employees work on each project
    - **Function Name**: `countEmployeesByProject`
    - **Input**: `employees`
    - **Output**: `{ "Project Alpha": 20, "Project Beta": 18, "Project Gamma": 15, "Project Delta": 12, "Project Epsilon": 10 }`
    - **Expected Result**: Returns an object with the count of employees working on each project.

28. Find projects with only one employee assigned
    - **Function Name**: `getSoloProjects`
    - **Input**: `employees`
    - **Output**: `["Project Zeta"]`
    - **Expected Result**: Returns an array of project names with only one employee assigned.

29. List employees who work on multiple projects
    - **Function Name**: `getEmployeesWithMultipleProjects`
    - **Input**: `employees`
    - **Output**: `[ { id: 1, firstName: "Jean", ... }, { id: 3, firstName: "Pierre", ... }, ... ]`
    - **Expected Result**: Returns an array of employees who are assigned to multiple projects.

30. Find the most popular project (most employees)
    - **Function Name**: `getMostPopularProject`
    - **Input**: `employees`
    - **Output**: `"Project Alpha"`
    - **Expected Result**: Returns the name of the project with the most employees assigned.

---

# Advanced

## Advanced - Complex Data Transformations
31. Create a new array with full names (firstName + lastName)
    - **Function Name**: `getFullNames`
    - **Input**: `employees`
    - **Output**: `["Jean Dupont", "Marie Martin", "Pierre Bernard", ...]`
    - **Expected Result**: Returns an array of full names for all employees.

32. Normalize all names: capitalize first letter, lowercase rest
    - **Function Name**: `normalizeNames`
    - **Input**: `employees`
    - **Output**: `["Jean", "Marie", "Pierre", ...]`
    - **Expected Result**: Returns an array of normalized names.

33. Create initials for each employee (e.g., "JD" for Jean Dupont)
    - **Function Name**: `getEmployeeInitials`
    - **Input**: `employees`
    - **Output**: `["JD", "MM", "PB", ...]`
    - **Expected Result**: Returns an array of initials for all employees.

34. Add a new property 'yearsOfService' calculated from joinDate
    - **Function Name**: `addYearsOfService`
    - **Input**: `employees`
    - **Output**: `[ { id: 1, yearsOfService: 6, ... }, { id: 2, yearsOfService: 5, ... }, ... ]`
    - **Expected Result**: Returns the employees array with an added 'yearsOfService' property.

35. Create an object grouping employees by first letter of last name
    - **Function Name**: `groupEmployeesByLastNameInitial`
    - **Input**: `employees`
    - **Output**: `{ "D": [ { id: 1, ... }, { id: 10, ... } ], "M": [ { id: 2, ... }, { id: 9, ... } ], ... }`
    - **Expected Result**: Returns an object grouping employees by the first letter of their last name.

36. Build a dictionary of projects with assigned employee names
    - **Function Name**: `getProjectEmployeeDictionary`
    - **Input**: `employees`
    - **Output**: `{ "Project Alpha": ["Jean Dupont", "Pierre Bernard", ...], "Project Beta": ["Marie Martin", ...], ... }`
    - **Expected Result**: Returns a dictionary of projects with the names of assigned employees.

37. Create a nested structure: departments → projects → employees
    - **Function Name**: `getDepartmentProjectEmployeeStructure`
    - **Input**: `employees`
    - **Output**: `{ "Développement": { "Project Alpha": [ { id: 1, ... }, ... ], ... }, ... }`
    - **Expected Result**: Returns a nested structure grouping employees by department and project.

38. Reverse all employee names (firstName and lastName separately)
    - **Function Name**: `reverseEmployeeNames`
    - **Input**: `employees`
    - **Output**: `[ { id: 1, firstName: "naej", lastName: "tnopuD", ... }, ... ]`
    - **Expected Result**: Returns the employees array with reversed first and last names.

39. Replace all vowels in names with '*'
    - **Function Name**: `replaceVowelsInNames`
    - **Input**: `employees`
    - **Output**: `[ { id: 1, firstName: "J**n", lastName: "D*p*nt", ... }, ... ]`
    - **Expected Result**: Returns the employees array with vowels in names replaced by '*'.

40. Create a string of all employee emails separated by ';'
    - **Function Name**: `getAllEmployeeEmails`
    - **Input**: `employees`
    - **Output**: `"jean.dupont@company.com;marie.martin@company.com;..."`
    - **Expected Result**: Returns a single string of all employee emails separated by ';'.

## Advanced - Statistical Analysis
41. Calculate the median salary company-wide
    - **Function Name**: `calculateMedianSalary`
    - **Input**: `employees`
    - **Output**: `55000`
    - **Expected Result**: Returns the median salary of all employees.

42. Find the standard deviation of employee ages
    - **Function Name**: `calculateAgeStandardDeviation`
    - **Input**: `employees`
    - **Output**: `5.2`
    - **Expected Result**: Returns the standard deviation of employee ages.

43. Determine salary percentiles (25th, 50th, 75th)
    - **Function Name**: `calculateSalaryPercentiles`
    - **Input**: `employees`
    - **Output**: `{ "25th": 45000, "50th": 55000, "75th": 65000 }`
    - **Expected Result**: Returns an object with salary percentiles.

44. Find the correlation between age and salary
    - **Function Name**: `calculateAgeSalaryCorrelation`
    - **Input**: `employees`
    - **Output**: `0.85`
    - **Expected Result**: Returns the correlation coefficient between age and salary.

45. Calculate the average number of skills by department
    - **Function Name**: `calculateAverageSkillsByDepartment`
    - **Input**: `employees`
    - **Output**: `{ "Développement": 4.2, "Design": 3.5, ... }`
    - **Expected Result**: Returns an object with the average number of skills per department.

46. Find the most common language combination
    - **Function Name**: `getMostCommonLanguageCombination`
    - **Input**: `employees`
    - **Output**: `["French", "English"]`
    - **Expected Result**: Returns the most common combination of languages spoken by employees.

47. Calculate the average project participation by age group
    - **Function Name**: `calculateAverageProjectsByAgeGroup`
    - **Input**: `employees`
    - **Output**: `{ "20-29": 2.5, "30-39": 3.2, "40-49": 3.8 }`
    - **Expected Result**: Returns an object with the average number of projects per age group.

48. Determine the most frequent first name initial
    - **Function Name**: `getMostFrequentFirstNameInitial`
    - **Input**: `employees`
    - **Output**: `"J"`
    - **Expected Result**: Returns the most frequent first name initial among employees.

49. Find the average salary difference between active/inactive employees
    - **Function Name**: `calculateSalaryDifferenceByStatus`
    - **Input**: `employees`
    - **Output**: `{ "active": 58000, "inactive": 52000, "difference": 6000 }`
    - **Expected Result**: Returns an object with the average salary difference between active and inactive employees.

50. Calculate the retention rate by join year
    - **Function Name**: `calculateRetentionRateByYear`
    - **Input**: `employees`
    - **Output**: `{ "2019": 0.85, "2020": 0.90, ... }`
    - **Expected Result**: Returns an object with retention rates by join year.

## Advanced - Search and Grouping
51. Find employees whose skills include both "JavaScript" and "React"
    - **Function Name**: `findEmployeesWithSpecificSkills`
    - **Input**: `employees, ["JavaScript", "React"]`
    - **Output**: `[ { id: 1, firstName: "Jean", ... }, { id: 13, firstName: "Julie", ... } ]`
    - **Expected Result**: Returns an array of employees whose skills include both "JavaScript" and "React".

52. List employees with special characters in their last names
    - **Function Name**: `findEmployeesWithSpecialCharacters`
    - **Input**: `employees`
    - **Output**: `[ { id: 35, lastName: "Rivière", ... }, { id: 46, lastName: "Martínez", ... } ]`
    - **Expected Result**: Returns an array of employees whose last names contain special characters.

53. Find employees whose email domain is not "company.com"
    - **Function Name**: `findEmployeesWithDifferentEmailDomain`
    - **Input**: `employees`
    - **Output**: `[]`
    - **Expected Result**: Returns an array of employees whose email domain is not "company.com".

54. Group employees by number of projects (0, 1-2, 3+)
    - **Function Name**: `groupEmployeesByProjectCount`
    - **Input**: `employees`
    - **Output**: `{ "0": [ { id: 12, ... }, { id: 24, ... } ], "1-2": [ { id: 9, ... }, { id: 13, ... } ], "3+": [ { id: 8, ... }, { id: 34, ... } ] }`
    - **Expected Result**: Returns an object grouping employees by the number of projects they are assigned to.

55. Find employees with anagrams in their names (e.g., "Jean" and "Jane")
    - **Function Name**: `findEmployeesWithAnagramNames`
    - **Input**: `employees`
    - **Output**: `[ { id: 1, firstName: "Jean", ... }, { id: 13, firstName: "Jane", ... } ]`
    - **Expected Result**: Returns an array of employees whose names are anagrams of each other.

56. List employees whose full name contains all vowels
    - **Function Name**: `findEmployeesWithAllVowelsInName`
    - **Input**: `employees`
    - **Output**: `[ { id: 17, firstName: "Amandine", lastName: "Perrot", ... } ]`
    - **Expected Result**: Returns an array of employees whose full names contain all vowels (a, e, i, o, u).

57. Find employees with the same first name but different last names
    - **Function Name**: `findEmployeesWithSameFirstName`
    - **Input**: `employees`
    - **Output**: `{ "Hugo": [ { id: 8, lastName: "Laurent", ... }, { id: 48, lastName: "Martinez", ... } ] }`
    - **Expected Result**: Returns an object grouping employees with the same first name but different last names.

58. Group employees by the length of their first name
    - **Function Name**: `groupEmployeesByFirstNameLength`
    - **Input**: `employees`
    - **Output**: `{ "3": [ { id: 8, firstName: "Hugo", ... } ], "4": [ { id: 1, firstName: "Jean", ... }, { id: 2, firstName: "Marie", ... } ], ... }`
    - **Expected Result**: Returns an object grouping employees by the length of their first name.

59. Find employees whose last name is a palindrome
    - **Function Name**: `findEmployeesWithPalindromeLastName`
    - **Input**: `employees`
    - **Output**: `[ { id: 11, lastName: "Lefevre", ... } ]`
    - **Expected Result**: Returns an array of employees whose last names are palindromes.

60. Create a search function that finds employees by any property value
    - **Function Name**: `searchEmployeesByProperty`
    - **Input**: `employees, "department", "Développement"`
    - **Output**: `[ { id: 1, ... }, { id: 4, ... }, { id: 6, ... } ]`
    - **Expected Result**: Returns an array of employees matching the specified property value.

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
