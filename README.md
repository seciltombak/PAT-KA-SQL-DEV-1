# PATİKA- SQL- ÖDEV-1
Patika linkim https://github.com/ismetcanbyk/patikaSQL/blob/master/%C3%B6dev1.sql


 SELECT title , description FROM film ;  
 ![github](1..png)  
 SELECT * FROM film WHERE length > 60 AND length < 75 ;  
 ![github](2..png)  
 SELECT * FROM film  WHERE rental_rate = '0.99' AND replacement_cost= '12.99' OR replacement_cost= '28.99' ;  
 ![github](3..png) 
 SELECT * FROM customer WHERE first_name = 'Mary';  
 ![github](4..png) 
 SELECT * FROM film WHERE  length < 50 AND  NOT (rental_rate = '2.99' or rental_rate = '4.99');  
 ![github](5..png) 
