The first step obviously is to install the Employees app from the administrator account. 

## Adding a new employee ##
A new employee gets stored in the database as an object of type 
```
#!python

res.partner
```
 The predefined fields have one called Working Address, and this is not that straight forward. 

### Filling in the Working Address ###
Odoo offers you to create a new working address or select from a drop down. But the weird part is that in the drop down you'd see not addresses but names of people and companies.
This is because Odoo fills the working address field with an object of type 'partner'. If you activate the developer mode, click on the pop out button and then hover over the Name field, it would say res.partner

So adding a new address is like adding a new object of type partner. Ideally you would not want that while filling in an address you are given a dropdown of all kinds of people and companies. So I'm creating an issue for this so that in the future we can restrict this to list of addresses of company offices