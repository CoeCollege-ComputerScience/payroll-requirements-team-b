## Final Requirements List

# MUST HAVE - These features are vital to a functional payroll system
* (Nonfunctional) The system must be able to be accessed by administrators/payroll dept. - This is the whole purpose of the program, so in order to work, it has to be accessed by employees/admins.
* (User) Admins must be able to access employee information and modify any non-personal employee information. - Vital to a payroll system because of the addition of new emmployees or changes in current employees information.
* (User) Admins must be able to add and remove employees from the payroll system
* (Nonfunctional) Employee information must include hire date, pay rate, personal information, position, schedule, benefits and tax information
* (Functional) The system must be able to recieve input from a file containing employee information.
 - If the system could not read in a file, then the user would have to input every piece of information manually every time the program runs. This would get very tedious and would defeat the primary purpose of having a program to do calculations.
* (Non-Functional) Payroll must be calculated based upon inputted information. 
 - The entire point of a payroll program is to make calculations so the administration does not have to do them manually. Therefore, this is a very important requirement.
* (Functional) Calculations must deduct taxes, medical and any other extra fees.
* (Functional) The system must be able to calculate taxes based on stored information unique to the employee.
* (Functional) The print function must return employee names, salary, and net pay. - Employee name, salary, and net pay are the core information needed to operate a basic payroll system, and thus, are the ones we print as output.
* (Non-Functional) Payroll must be able to be returned in a simple to read format such as a chart. - The data returned must be returned in an easily readable way in order to make the output efficient to read.


# SHOULD HAVE - These features are not vital to a payroll system, but add convenient functionalities to the base system.
* (Business) The system should allow the business to access a wider range of functions, allowing them more flexible use of the data stored for each employee.
* (Functional) The system should be able to create, alter, and print employee schedules.
* (User) Admins should be able to create, edit, and print employee schedules.
* (Non-Functional) The system should use employee information and admin user input to create employee schedules.
* (Non-Functional) The system should be able to handle paychecks based on employee payment information.
* (User) Admin users should be able to access, read, & write to all files, both past and present.
* (Implementation) The system should be able to backup/archive and store records of previous employees and pay cycles.
* (Non-Functional) The system should be able to access bank routing information and pay electronically.
* (Non-Functional) The system should be able to generate payments according to employee preferences.
* (Implementation) The system should be able to access archived information in the database of company records.


# COULD HAVE - These features add multiple user types in order to expand functionality beyond that of a simple payroll system.
* (Business) These features could allow the employees of the business to have more access to their own personl data.
* (Functional) The system could have multiple user types: including admins and employees. Usernames and passwords will be stored in a database accessed only by admins.
* (Functional) The system could have an employee user type with alternate permissions, including restrictions on the employee information they are able to view and edit.
* (Functional) The system could store login information for each user as well as whether or not they have administrative permissions.
* (User) Employees could be able to view all information and edit personal information: including hours, pay rate, benefits, documents (insurance info, W2s, etc.), and previous and current checks
* (User) The Employee could be able to access what taxes or extra fees are causing their earnings total to be less than what they may have initially predicted.
* (User) The employee could have their own print function, which prints out their personal payroll information, including name, bank info, salary, and net pay.
* (User) The employee could be able to request administrators through the system to do things such as alter the date of their paycheck, request various legal documents, change access password, or type their own request.
* (User) Admins could be able to recieve requests from employees. Admins will then be able to approve or decline these requests.


# WON'T HAVE - These features are outside of the bounds of this project, but could be useful
* (Business) The business won't be able to employee techniques like an app for easy access to payroll functions.
* (Functional) The system won't have a GUI. It will be run entirely from the command line.
* (Non-functional) The system won't allow users to request things outside of the scope of payroll such as transfers and raises.
