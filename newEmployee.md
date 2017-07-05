## Employee ##
As a matter of best practices, a new employee should not be created before knowing the exact details of his work address, job title, manager and other information. In fact, all such pre-requisite information should to be fed into the system before actually creating a new employee. Such information can be entered on the fly, but is usually a more confusing process. 

### Pre-requisities ###

In order to go step by step towards adding a new employee, we need to answer the following questions

* Which node(or head office) is the employee associated with?
* What is the role of the employee within that node's organization hierarchy?
* What is the personal information we have about the employee?
* What is the capacity in which the employee can use the desktop application?

In order to associate the employee to a node, we first need to know how to [create a new node](nodalOffice.md), if that doesn't exist already. We then need to [create a desktop user](#desktop-user) corresponding to the new employee being added. Finally, create the employee's [personal profile](#personal-profile). At this point we have answers to all the questions above. After this, the steps are straightforward. 

##### Desktop User #####

Navigate to ```Settings --> Users --> Create```
Enter name, email and create a new password and save. In order to provide access to the user to use the functionality, navigate to ```Settings --> Groups``` and search for ```Uncategorized```. From the search results, select the right option. Lets say you select ```Head Office Executive```. When the form opens, select ```Edit``` and then ```Add an Item``` within the Users tab. When the popup window opens, search for the user and add to the group.  

##### Personal Profile#####

Adding a new system user automatically makes him a customer as well. So we navigate to ```Sales --> Customers``` and select the newly created Customer, followed by ```Edit```. We markt the company as Farms and Farmers. Change the ```Address Type``` from **Contact** to **Other Address** and then fill in all the personal details of the employee. Lastly, it is important that in the ```Sales and Purchases``` tab, we untick ```Is A Customer```

### Putting it all together ###

Log in as an **administrator** and in the top left menu click on ```Employees``` and then the ```Create``` button. 

**Employee's Name** is mandatory, picture is not.
In the **working address** field, as well as in the **Department** field, search for the name of the Node and it will appear in the drop down. The rest of the work information (mobile, location, email and phone) should get autofilled. **Job Title** should ideally be one between *Executive* or *Manager*, unless otherwise required.

In the **Personal Information** tab, search for the Employee's name in the Home Address field and hence select the personal address.

Finally, in the **HR Settings** tab, search for the Employee's name and select his/her *desktop user* profile.

**Note** *We need to make several configurations while adding each employee. It is important that a very small group of users should be able to add information on new employees, because this process gives access to sensitive information.*


