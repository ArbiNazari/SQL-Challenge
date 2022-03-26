# Challenge #12:  SQL-Challenge

 SQL Challenge 12: Employee Tracker 

  ## Table-of-Contents
  * [Description and Task](#description)
  * [Requirements and Installing](#require)
  * [License](#license)   
  * [Contributing](#contributing)
  * [Questions](#questions)


## [Description](#table-of-contents)
 
 Application Design and Function

 AS A business owner, I want to be able to view and manage the departments, roles, and 
 employees in my company so that I can organize and plan my business.

 # My Task and Application Requirments

   - Given a command-line application that accepts user input when user starts the APP. 

   - Useris presented with the following options: view all departments, view all roles, view all employees, 
     add a department, add a role, add an employee, and update an employee role.

   - User is presented with a formatted table showing department names and department ids when user selected view 
     all departments.

   - User is presented with a formatted table showing department names and department ids when user choose to view all roles.

   - User is also presented with the job title, role id, the department that role belongs to, and the 
     salary for that role when user chooses to view all employees.

   - When user chooses to add a department, they are presented with a formatted table showing employee data, including 
     employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to.
   
   - User is  prompted to enter the name, salary, and department for the role and that role is added to the database when user
      chooses to add an employee.

   - User prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
     when user decides to update an employee role.

   - User is then prompted to select an employee to update and their new role and this information is updated in the database.


   ## [Require](#table-of-contents)

   # Database Application Structuring:


   # Schema Tabling:

    As the image illustrates, your schema should contain the following three tables:

    department

        id: INT PRIMARY KEY

        name: VARCHAR(30) to hold department name

    role

        id: INT PRIMARY KEY

        title: VARCHAR(30) to hold role title

        salary: DECIMAL to hold role salary

        department_id: INT to hold reference to department role belongs to

    employee

        id: INT PRIMARY KEY

        first_name: VARCHAR(30) to hold employee first name

        last_name: VARCHAR(30) to hold employee last name

        role_id: INT to hold reference to employee role

        manager_id: INT to hold reference to another employee that is the manager of the current employee (null if the employee has no manager)


After installing the required applications (Node.js) - run: node index.js
 
   Video Guide - [video guide](https://www.awesomescreenshot.com/video/7497518?key=39b1b50897de8d6ae47e34774bafb4f6)
  
  ## [License](#table-of-contents)
  The application is covered under the following license:
  
  [apache](https://choosealicense.com/licenses/apache)
    
    
  ## [Contributing](#table-of-contents)
  
    Feel free to contact me if there are any issues or ideas to implement.
    
  ## [Questions](#table-of-contents)
  Contact Information Below:
  [GitHub](https://github.com/arbinazari)

  [Email: arbinazari@hotmail.com](mailto:arbinazari@hotmail.com)