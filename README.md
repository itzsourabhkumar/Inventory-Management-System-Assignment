# Inventory-Management-System-Assignment
JSON_Based Inventory Management System Assignment
<h1>Five File listed in program name as follows:</h1>
<h3>1.BUYING_PRODUCTS{Main program}.ipynb</h3>
<h3>2.DATA_OF_EMPLOYEE'S.ipynb</h3>
<h3>3.DATA_OF_PRODUCTS.ipynb</h3>
<h3>4.Employees_record.json</h3>
<h3>5.products.json</h3>
Here JSON file is used to store data of Employees and products
<br/>
and for taking the data in JSON file we used to another file name as <b>DATA_OF_EMPLOYEE'S.ipynb</b> and <b>DATA_OF_PRODUCTS.ipynb</b>
<h1>OBJECTIVE: </h1>
Take data from json file after that login through you name ,Make your order,Print Bill and last update Both JSON file.
<br/>
<h4>Detail Explanation of BUYING_PRODUCTS{Main program} file Step by Step</h4>
step 1: import json and open Employees_record and read it.
<img src="Screenshot (162).png" /> 
<br/>
step 2: print NAME OF EMPLOYEES WITH THEIR OCCUPATION AND EMAIL_ID
<img src="Screenshot (163).png" />
<br/>
step 3: In this step take the name of the user and check. If the user found then print Successfullly login and if user not found print NAME NOT MATCH PLEASE TRY AGAIN and take user name again.
<img src="Screenshot (164).png" />
<br/>
step 4: open file of products.json in read mode and store all data of products.json in a variable name -> all_product
<img src="Screenshot (165).png" />
<br/>
step 5: Make a menu bar by using all_product and display item name , cost and discount
<img src="Screenshot (166).png" />
<br/>
step 6: In this step make your order by entering  Item Number , quantity of that item ,and if you want to order more item then you can do that by entering 1.
<img src="Screenshot (167).png" />
<br/>
step 7: import time
<br/>
step 8: Enter Detail of Bill with Date and Time of Billing , print total amount and Employee Balance left
<img src="Screenshot (168).png" />
<img src="Screenshot (169).png" />
<br/>
step 9: Update Balance and Last transation date and time
<br/>
step 10: Update Employees_record.json file 
<br/>
step 11: Update total_number_of_items
<br/>
step 12: Update products.json file
<br/>
