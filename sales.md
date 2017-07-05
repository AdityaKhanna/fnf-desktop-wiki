## Sales ##
There are two types of customers - farmers and dehaat coordinators. In order to use the desktop application to record sales transactions, here are the steps - 

1. [Create a new Sales Order](#create-a-new-sales-order)
2. [Confirm the Sales Order](#confirm-the-sales-order)
3. [Fulfil the Order](#fulfil-the-order)
4. [Generate and deliver invoice](#generate-and-deliver-invoice)
5. [Record payment information](#record-payment-information)


### Create a new sales order###
```Sales --> Sales Orders --> Create```

**Customer:** Start typing the name of the customer and the name would appear in the drop down. If there are multiple customers with the same name, it is possible to search using phone number (instructions for the same coming soon) If a customer doesn't exist, a new one can be created from the drop down itself. Please note that as of now, all users can [add a new Customer](access rights.md)
**Invoice Address** Gets auto-filled with the stored address of the customer, but can be modified
**Delivery Address** Can be selected or modified independently from the invoice address

Enter products in the **Order Lines** tab. 
No need to enter any information in the **Other Information** tab. This tab would be used later when fulfiling the order.

### Confirm the Sales Order###

```Sales --> Sales Orders --> Select Order```

Once the Order form opens click on ```Confirm Sale```

### Fulfil the Order###

As soon as you click on Confirm Order, you will see a Delivery button appears on the Order page. Click on the delivery button to enter information about fulfilment. 
	+ In the additional info section, select whether delivery is Partial or All at Once
	+ In the additional info section, select Picking type as Delivery Orders 
If you are not delivering the entire order in one go, then you go for Partial fulfilment. For instance, if the asked quantity is 10 units and you are delivering 4, then in the ```Operations``` tab, ```To Do``` column will say 10. Edit the ```Done``` section to say 4. The rest of the delivery information such as Source and destination location for the delivery can be edited by clicking on the edit (pencil shaped) button 

Once the transfer information has been added to the Sales Order, that information reflects in the Transfers section of the Inventory management portal. This portal can be used to track when the transfer is completed.

Once all the required transfers have been completed, the Order fulfilment can be recorded by clicking on the ```Validate``` button.

### Generate and deliver invoice###

You can see a list of all orders to be fulfilled by navigating as below
```Sales --> Confirmed Orders```
This page will also show whether the invoices have been sent for the orders or not in the Invoice Status column. Click on any order whose Invoice Status is *To Invoice*. Once the order page opens, click on ```Create Invoice``` followed by ```Create and view invoices```

Once the invoice looks final, click on *Validate* to generate the final invoice. THis can be printed or sent over email.  

### Record payment information###

In order to record that a payment has been made, you need to open an invoice corresponding to which the payment would be registered. 
```Sales --> Confirmed Orders --> Select Order --> Invoices --> Register Payment```
This way you can also record multiple partial payments. Once the entire invoice amount is paid, the invoice Order gets marked as Paid
