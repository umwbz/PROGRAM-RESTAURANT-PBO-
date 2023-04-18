  This is a Java program that simulates a restaurant management system. It has an admin login that allows adding and deleting restaurants from the system, and a customer login that allows placing orders and viewing the order history. The program uses classes to represent restaurants, menus, and orders, and stores the data in lists and maps.

The program has a main method that displays a menu with two options: login as admin or login as customer. When the admin option is selected, the program prompts for a username and password, and if the correct credentials are entered, displays an admin menu with three options: view restaurants, add restaurant, and delete restaurant. When the customer option is selected, the program displays a customer menu with three options: view restaurants, place order, and view order history.

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
 
