Sales Forecasting

Below is the data descritption - 

1. Time series data with timeframe of 4 years
2. Data for 200 distinct Customers
3. Lowest level is Invoice level
4. Data for 40 distinct Products are present
5. Below is the relationship of data 
	many2one(<Invoice>,<Customer_ID>)
	one customer can have multiple invoices
	one2many(<Customer_ID>,<Invoice>)
	Each invoice will have its own InvoiceDate
	one2one(<Invoice>,<InvoiceDate>)
6. 	Below is the column Structure - 
	"Invoice",
	"Product_Code",
	"Quantity",
	"InvoiceDate",
	"Price",
	"Customer_ID",
	"Country",
	"Pack_Size_Code",
	"In_Store_Promotion_Flag",
	"Online_Promotion_Flag",
	"Shelf_Space_Code"
	
			   		
8. In Store promotions is the flag where promotions of that product is done or not inside the store. 0 = No promotions done, 1 = Promotions done
9. Online Promotions is the flag where promotions of that product is done or not online. 0 = No promotions done, 1 = Promotions done	
10. Shelf Space code is the placement of prodcut inside the store. Some shelf spaces are highly visible and attractive to customers and there is high posibillity that the product is purchased when placed on this space 				