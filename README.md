# SQLServer_PizzaRunner_Metrics project 
This project showcases
1 how to work with NULL values
2 working with dates (DATETRUNC, DATENAME, DATEPART)
3 group by
4 joins
5 conditional statements

The Entrepreneur decided to start a business about combining pizza delivery with running so it has a team of runners out there going to deliver pizza for him. He has prepared an entity relationship diagram of his database design but requires further assistance to clean his data and apply some basic calculations so he can better direct his runners and optimise Pizza Runner’s operations.
The SQL schema is made of 6 tables.
Customer pizza orders are captured in the customer_orders table. One single order may contain more than 1 pizza. The pizza_id relates to the type of pizza which was ordered whilst the exclusions are the ingredient_id values which should be removed from the pizza and the extras are the ingredient_id values which need to be added to the pizza. Customers can order multiple pizzas in a single order with varying exclusions and extras values even if the pizza is the same type! The exclusions and extras columns will need to be cleaned up before using them in the queries.
After each orders are received through the system - they are assigned to a runner - however not all orders are fully completed and can be cancelled by the restaurant or the customer. The pickup_time is the datetime at which the runner arrives at the Pizza Runner headquarters to pick up the freshly cooked pizzas. The distance and duration fields are related to how far and long the runner had to travel to deliver the order to the respective customer. There are some known data issues with this table so I need to be careful and make sure to check the data types for each column in the schema SQL!
At the moment - Pizza Runner only has 2 pizzas available the Meat Lovers or Vegetarian! Each pizza_id has a standard set of toppings which are used as part of the pizza recipe.
The Pizza_toppings table contains all of the topping
