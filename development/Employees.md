The first step obviously is to install the Employees app from the administrator account. 

## Adding a new employee ##
A new employee gets stored in the database as an object of type 
```
#!python

res.partner
```
 The predefined fields have one called Working Address, and this is not that straight forward. 

#### Filling in the Working Address ####
Odoo offers you to create a new working address or select from a drop down. But the weird part is that in the drop down you'd see not addresses but names of people and companies.
This is because Odoo fills the working address field with an object of type 'partner'. If you activate the developer mode, click on the pop out button and then hover over the Name field, it would say res.partner

So adding a new address is like adding a new object of type partner. Ideally you would not want that while filling in an address you are given a dropdown of all kinds of people and companies. So I'm creating an issue for this so that in the future we can restrict this to list of addresses of company offices.

#### From Departments to Offices ####
The default Odoo model of department seems not very useful to the current organization hierarchy. So I'm changing only the name of the department to Office. Made this change in two places - 

##### Side Menu #####
Admin login --> Settings --> User Interface --> Menu Items --> Searched for Deparments --> Edit --> Change Departments to Offices

##### Action Name #####
This happened after the above edit, so that Offices is in the list already when you search for it
Admin login --> Settings --> User Interface --> Menu Items --> Searched for Offices --> Action| Departments --> Edit --> Change Action name from Departments to Offices

#### Removing Employee tags ####
Admin login --> Settings --> User Interface --> Menu Items --> Searched for Employees/Configuration --> Edit --> Changed Access rights from Employee/Manager to Administration/Access Rights.
This way, no one gets to assign tags to employees. In fact, the employee configuration menu item is not even visible unless you activate the developer mode in an admin account

#### More changes to the employee form #### 
Remove Coach and Home address
Ask the user to enter home address in the notes section
Remove tags section that used to say Part Time, etc