# CNL_OrderProcessProject
	                                ORDER PROCESS MANAGEMENT
Product Controller
1.	Create Operation
 

Input
http://localhost:8080/Products/saveproducts

 
Output:
 

2.	Retrieve Operation
 



Input: 
http://localhost:8080/Products/showproducts

Output:
 

3.	Retrieve Product By Id

 

Input:
http://localhost:8080/Products/showbyid/{p_Id}

http://localhost:8080/Products/showbyid/2
Output:
 
4.	Update Products by id:
 

Input:
http://localhost:8080/Products/Updatebyid/2

 

Output:
 

5.	Delete Product by Id:
 


Input:
http://localhost:8080/Products/dltbyid/12




Output:

 

Order Controller
1.	Create operations :
 
Input: 
http://localhost:8080/orders/saveorrders

 
	





Output:
 

2.	Retrieve Operation:

 
Input:
http://localhost:8080/orders/showorders

Output:
 
3.	Retrieve by Id:
 

Input:

http://localhost:8080/orders/showbyid/{orderID}
http://localhost:8080/orders/showbyid/33

 






4.	Update by Id:
 

Input:
http://localhost:8080/orders/Updatebyid/55

 

Output:
 

5.	Delete by Id:
 
Input:
http://localhost:8080/orders/dltbyid/{orderId}

http://localhost:8080/orders/dltbyid/55

Output:
 

Batch configuration :
Product.csv file
 

MySQL Database:
1.	ProductDto table

 

2.	OrderDto Table:


 
