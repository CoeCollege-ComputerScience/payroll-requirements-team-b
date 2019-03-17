## Final Requirements List

# MUST HAVE - These features are vital to a functional payroll system
* (Nonfunctional) The system must be able to be accessed by administrators/payroll dept.
* (Nonfunctional)Admins must be able to access employee information and modify any non-personal employee information.
* (Functional) Admins must be able to add and remove employees from the payroll system
* (Nonfunctional) Employee information must include hire date, pay rate, personal information, position, schedule, benefits and tax information
* (Functional) The system must be able to recieve input from a file containing employee information.
* Payroll must be calculated based upon inputted information. Calculations must deduct taxes, medical and any other extra fees.
* The system must be able to calculate taxes based on stored information unique to the employee.
* Payroll must be able to be returned in a simple to read format such as a chart.
* The print function must return employee names, salary, net pay, and bank. It must also print total payroll information.


# SHOULD HAVE - These features are not vital to a payroll system, but add convenient functionalities to the base system.
* Admins should be able to create and edit employee schedules and pay rates.
* The system should be able to print the schedule for the current pay cycle.
* The system should be able to handle paychecks based on employee payment information.
* Admin users should be able to access, read, & write to all files, both past and present.
* The system should be able to backup/archive and store records of previous employees and pay cycles.
* The system should be able to access bank routing information and pay electronically.
* The system should be able to generate payments according to employee preferences.
* The system should be able to access archived information in the database of company records.


# COULD HAVE - These features add multiple user types in order to expand functionality beyond that of a simple payroll system.
* The system could have multiple user types: including admins and employees. Usernames and passwords will be stored in a database accessed only by admins.
* The system could have an employee user type with alternate permissions, including restrictions on the employee information they are able to view and edit.
* The system could store login information for each user as well as whether or not they have administrative permissions.
* Employees could be able to view all information and edit personal information: including hours, pay rate, benefits, documents (insurance info, W2s, etc.), and previous and current checks
* The Employee could be able to access what taxes or extra fees are causing their earnings total to be less that what they may have initially predicted.
* The employee could have their own print function, which prints out their personal payroll information, including name, bank info, salary, and net pay.
* The employee could be able to request administrators through the system to do things such as alter the date of their paycheck, request various legal documents, change access password, or type their own request.
* Admins could be able to recieve requests from employees. Admins will then be able to approve or decline these requests.


# WON'T HAVE - These features are outside of the bounds of this project, but could be useful
* The system won't have a GUI. It will be run entirely from the command line.
* The system won't allow users to request things outside of the scope of payroll such as transfers and raises.