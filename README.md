# Meesho sql assignment

Q1) For the Given Data - order_details, orders & products. The Data are linked as follows
       Id in orders is OrderId in order_details.
       Id in products is productId in order_details.

For this Data 
Find out the GMV(Order Total) per Product
Plot a graph of No. of Orders v/s Product Price 


Q2) Given an Order Table with the schema(id, user_id, total, created). Write a SQL Query to create a retention plot. The format for the raw data and output are given. 

Week Start Date is the 1st Week in which the User_Id Placed the order, Week 0 is Unique User ids who placed their 1st Order in this week. Out of those ids, Week 1 is unique users who placed an order in 1st Week + 1, Then Week 2 is 1st Week + 2 and so on till Week 10.

Q3) Given the tables Order_Timeline(schema id,order_id,  message, created) & Order_Shipment  Table(schema id, order_id,actual_dispatch_date,created) , write a SQL Query to find
% orders shipped before first message date(OTIF)
% orders shipped on first message date+1(OTIF+1)
% orders shipped on first message date+2(OTIF+2)
%orders shipped after that(OTIF+>2)

Order_Timeline contains the message for expected dispatch date, Order_shipment gives you the real dispatch date. They are combined using order_id.
