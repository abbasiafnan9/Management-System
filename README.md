# Management-System

## Description
This project utilizes MySQL2 and Inquirer to provide an interactive database for companies looking to track their employees. The interactiveness is gained by being able to add departments, roles and employees through command line prompts. Employees will be automatically attached to certain departments and salaries once a role has been chosen for them and they can also be updated.

## Instalation and Usage
This project requires the use of a number of npms which are listed as dependencies so upon loading one must type "npm init" and then "npm i" and ensure that the Inquirer, MySQL2 and Console.Table npms are all downloaded for use through My Visual Studio Code.

The next thing that must be done is create the database. To do that a user must travel to the schema.sql file and enter into mysql via the integrated terminal and run the "source schema.sql" command. If the user wants to view the functionality of the program they can also seed the database by running "source seeds.sql"

To begin the application a user must enter into the command line and type "node index.js" this will bring up a friendly "Welcome to Our Company". If the User seeded the database they can go through and view departments, roles, employees and the like with the arrow key and enter button. If they didn't these options will simply come up with empty arrays.

The other options allow a user to add or delete Departments, Roles and Employees. When creating an employee they may or may not have a manager so a user can select "None" or one of the other employees. Once an employee has been created they can be updated to alter either their role or their manager. Some additional features of the app is to view employees by their manager and by their department.
