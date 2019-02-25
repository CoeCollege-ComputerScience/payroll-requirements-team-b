## Categorized Requirements

# Business Requirements
* The system will allow the business to avoid handling the payroll manually.
* The system will allow the business to handle paying their employees automatically.
* The system will allow the business to create, store and modify records of current and past employees.
* The system will allow business employees a structured way of contacting admins to alter information or allow special cases such as advanced payment, raises, or days off.
* The system will allow business admins to check company records such as employee info, and respond to employee requests.

# User Requirements
* The system will have two types of users: employees and admins.

**Employees**
* Employees should be able to view information: including hours, pay rate, benefits, documents (insurance info, W2s, etc.), and previous and current checks
* Employees should be able to alter their passwords.
* Employees should be able to edit their personal information.
* Employees should be able to submit requests which will be visible to admins. Employees will be able to request advance payment, hours, days off, transferrals, and other pay alterations.
* Employees should be able to logout of the system.
* Employees should be able to select method of payment, be it physical or direct deposit.

**Admins**
* Admins should be able to access employee information and modify any non-personal employee information.
* Admins should be able to edit employee schedules and pay rates.
* Admins should be able to add and remove employees from the payroll system.
* Admins should be able to recieve requests from employees. Admins will then be able to approve or decline these requests.
* Admins should be able to access company records including previous employees and pay cycles.
* Admins should be able to logout of the system.

# Functional Requirements
* The system shall be able to store employee information.
* The system shall be able to backup and store records of previous employees and pay cycles.
* The system shall store login information for each user as well as whether or not they have administrative permissions.
* The system shall be able to send requests between employees and admins.
* The system shall be able to handle paychecks based on employee payment information.
* The system shall be able to generate paychecks according to employee preferences.
* The system shall be able to move information between records and current information.


# Nonfunctional Requirements

# Implementation Requirements
* Admin user can access, read, & write all files, both past and present. 
* Employee user can only open their own file and can only write certain fields of information (such as address and bank routing info).
* "File" contents for each employee include their basic info (name, base salary, etc), followed by all clock in/clock out times for the current pay cycle.
* A database of all usernames and passwords is used for the login system. This file database is not visible to anyone but admins.
* The username/password database is read only unless an admin approves a password change or is adding/removing a user from the database.
* Employees cannot view other people's records or earning per current or past pay cycle.
* Wages per cycle are calculated by the clock in/out times and the base wage contained in an employee's record/file. 
* Any taxes/extra fees applicable will be calculated and deducted from the employees wage before displaying the final result to them.
* The user will be informed of what taxes or extra fees are causing their earnings total to be less that what they may have initially predicted.
* Different commands are available for each user. They are as follows.

**Employees**
*print --> prints out all info, including name, contact info, bank routing info, base wage, and earnings per current pay cycle.
	*name --> prints only the name of the employee
	*bank --> prints bank routing info
	*phone --> prints phone number
	*email --> prints email.
	*position --> prints position (job name)
	*salary --> prints the base salary for the employee
	*earnings --> prints earnings per current pay cycle
*change --> Allows user to change certain info. Note that only certain fields can be changed.
	*bank --> changes bank routing info
	*phone --> changes phone number
	*email --> changes email
	*password --> changes password associated with account. Requires the employee to input their old password again before they are allowed to change it.
*request --> Allows user to submit a request for something, such as:
	*paycheck --> If user needs their paycheck earlier than pay day
	*transfer --> If user wants to be transferred to another department/branch of the company
	*raise --> If user wishes to have a raise
	*other --> If user has something to tell the admin that does not fit into the above choices
*logout --> logs out the current employee, thus allowing a different username & password to be entered.
*exit --> quits the command line loop.

**Admin**
*Admin has access to all of the same commands as an Employee, and more. Commands available only to them are as follows:
*print all employees --> prints out every employees' info in a table-like format
*print schedule --> prints the current schedule for the current pay cycle. If none has been specified, the system informs the admin & nothing is printed.
*create schedule --> allows the admin to assign employees to certain shifts during the current pay cycle. 
*print requests --> Begins printing requests to admin can read and accept/reject them.
 
