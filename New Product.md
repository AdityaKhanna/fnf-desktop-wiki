# How to add a new Product
In order to add a new product, we need to enter the following information for each product - 
Category --> Manufacturer --> Brand name --> SKU unit
From the portal, go to ```Inventory --> Inventory Controls --> Products --> Create```

Enter the following information

In the General Information tab:
+ **Product Name** *Enter the manufacturer's name*
+ **Internal Reference** *Enter the brand's name*
+ **Internal Category** *Search for items such as wheat, tomato, pesticide, etc and then select from dropdown*
+ **Sales Price** *This is the default price that appears during transactions. The final price to be charged can be edited during transaction*
+ **Cost** *per unit Quantity*
+ **Unit of Measure** *Select from dropdown or create new*

In the Variants tab:

Use this tab to enter SKU level information such as weight/size as different attributes. For instance, if you want to specify that a particular product comes in two variants - 5kg and 15kg, then in the variants tab, select Attribute as Size and variant as 25. New attributes and values can be created as required.

## Categories
Products are arranged by category in the database. For instance, if we need to add a new fertilizer, 
we would select the category as Input and then Fertilizer

The current categories defined in the system are 
1. Input	
	+ Seeds
		+ Wheat
		+ Corn
	+ Fertilizers
	+ Pesticides
2. Output
	+ Fruits

## Product Variants
Variants help distinguish between different SKUs. To see all variants of products go to ```Sales --> Product Variants``` 
Different variants can be seen as having different attributes

Product variants, categories and unit of measurements can be edited by the admin from the Configuration menu in the Sales section