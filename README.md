  This is a Java program that simulates a restaurant management system. It has an admin login that allows adding and deleting restaurants from the system, and a customer login that allows placing orders and viewing the order history. The program uses classes to represent restaurants, menus, and orders, and stores the data in lists and maps.

The program uses the following classes:

Main: the main class that contains the main method and the admin and customer menu methods.
Restaurant: a class that represents a restaurant and contains the name, address, and menu of the restaurant.
Menu: a class that represents a menu and contains maps of foods and drinks with their prices.
Order: a class that represents an order and contains the restaurant ID, menu ID, quantity, distance, and delivery fee.

The program uses lists and maps to store the data:

restaurantList: a list of all restaurants in the system.
orderList: a list of all orders placed by customers.
foods: a map of all foods in a menu.
drinks: a map of all drinks in a menu.
The program uses a Scanner object to read input from the user. The program is designed to be used in the console.

Here,s the output of this program 

![image](https://user-images.githubusercontent.com/115135900/232648643-a91c03d2-f3c1-46bd-a271-c18876792ae4.png)

The program has a main method that displays a menu with two options: login as admin or login as customer. When the admin option is selected, the program prompts for a username and password, and if the correct credentials are entered, displays an admin menu with three options: view restaurants, add restaurant, and delete restaurant. and aso when the admin add restaurant they can add menu (food/drink) in to the restaurant

here's the ouput of program when admin add restaurant:

![image](https://user-images.githubusercontent.com/115135900/232648821-218b1432-5639-45c7-8338-d2b8518ea06b.png)

here's the ouput of program when admin delete restaurant:
![image](https://user-images.githubusercontent.com/115135900/232650016-8e7952d8-c7b9-4789-a33b-ebf7994a99ff.png)
admin will delete restaurant number 2

![image](https://user-images.githubusercontent.com/115135900/232649953-095fda5f-6df9-4f21-8125-acf05d39e5d4.png)




in the Login menu When the customer option is selected, the program displays a customer menu with three options: view restaurants, place order, and view order history.

![image](https://user-images.githubusercontent.com/115135900/232650425-de168389-c94a-423e-bbc7-55a87893aff7.png)

Customers can place an order by choosing which restaurant they want

![image](https://user-images.githubusercontent.com/115135900/232650515-13cfe2ee-80f2-41bb-8eb3-fb83a222e3f1.png)

And next, the menu available at the chosen restaurant will be displayed

![image](https://user-images.githubusercontent.com/115135900/232650882-979d58d9-c3d7-4730-8b77-43a008461cc6.png)

Customers can also see their order history.

![image](https://user-images.githubusercontent.com/115135900/232651056-72fbaa8b-6ae4-4d41-b27c-be7ea603dd76.png)

Unfortunately, in this program, customers are not able to place recurring orders, so customers can only order one menu at a time when placing an order.



 
