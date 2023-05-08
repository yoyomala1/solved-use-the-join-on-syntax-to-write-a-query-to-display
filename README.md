Download Link: https://assignmentchef.com/product/solved-use-the-join-on-syntax-to-write-a-query-to-display
<br>
<ol>

 <li>Use the JOIN ON syntax to write a query to display the order id, order date, customer name formatted as a single field (i.e. “Tom Jones”) with a heading of Customer, and customer_city for customers residing in the state of OHIO. Sort the output to display the newest orders first.</li>

</ol>




<ol start="2">

 <li>Use the JOIN USING syntax to display the order_id, order date, and shipdate for orders to Karina Lacy that have shipped.</li>

</ol>




<ol start="3">

 <li>Use the implicit join syntax (the WHERE clause) to display the last name, city, order date and ship date for all orders shipped in 2012.</li>

</ol>




<ol start="4">

 <li>Use any join syntax EXCEPT NATURAL JOIN to list the customer_first_name and customer_last_name concatenated with an intervening space as Customer, customer city and state formatted as a single column in the format of “city, ST” with a heading of Location, order_id and order date for orders that have not shipped.</li>

 <li>List the customer name, order date, zipcode for any customer(s) placing an order for the item titled ‘Etcetera”.</li>

</ol>




<ol start="6">

 <li>Write a query to list the title and artist of ONLY the items that have been ordered. Only list each title once.</li>

</ol>




<ol start="7">

 <li>Write a query to list the title and price of all items that have been ordered by customer Millerton.</li>

</ol>




<ol start="8">

 <li>Write a query to list the last name and order id of customers that ordered any items by the artist Burt Ruggles?</li>

</ol>




<ol start="9">

 <li>Write a query to display a list of titles along with the artist name., sorted by artist name.</li>

</ol>




<ol start="10">

 <li>Write a query to display an invoice for order 693 including the title, quanty, price, and a calculated column to display the line item subtotal (quantity times price) with a heading of Subtotal.</li>

</ol>




<ol start="11">

 <li>Display the order id, last name, title , and quantity for any items where customers have ordered 2 or more of a particular item in an order.</li>

</ol>




<ol start="12">

 <li>The employees table contains a list of employees of a company. An employee may be managed by another employee. To denote an employee’s manager, the employee_id of the manager is entered into the manager_id field of the employee reporting to that manager. In order to produce a list of which managers supervise which employees, the table may be joined to itself using these two attributes (employee_id, manager_id). This is known as a SELF-JOIN. Use a SELF-JOIN on the employees table to produce a result containing two columns: the concatenated last_name and first_name of the manager, and the concatenated last_name and first_name of the employee. Label the first-column supervisor, and the second-column employee. Order the output by the supervisor’s last_name and first_name.</li>

</ol>




<ol start="13">

 <li>Write a query to display the order id, order date, ship date, and customer last name for all SHIPPED orders placed on the internet (no employee id). Show the most recently shipped orders first.</li>

 <li>Write a query that displays the order id, order date, and employee name as a single field labeled Employee for each order that an employee assisted with.</li>

</ol>




<ol start="15">

 <li>Write a query that displays the order id, order date, customer name as a single field labeled Customer for all orders for the sales rep Thomas Hardy, sorted by customer last name.</li>

</ol>