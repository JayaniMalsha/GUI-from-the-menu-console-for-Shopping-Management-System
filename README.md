# Shopping-Management-System (GUI-from-the-menu-console)
Java/ Java Swing/ OOP

In order to follow inheritance and encapsulation principles, a super-class Product and subclasses Electronics and Clothing must be designed and implemented. Each class should have at least one constructor for each class, including information about the product ID, product name, number of available items, and price. The Electronics subclass should hold specific information and methods, such as brand and warranty period, while the Clothing subclass should have specific information and methods.

A class User should represent the user account, holding information about username and password, constructors, and related get/set methods. A class ShoppingCart should represent the user's cart, containing a list of products as instance variables and methods to add, remove, and calculate the total cost. A class called WestminsterShoppingManager should be designed and implemented, which maintains the list of products in the system and provides all the methods for the system manager defined in the console menu.

In Phase 2, the WestminsterShoppingManager should display a menu in the console containing management actions from which the manager can select one. This includes adding a new product, deleting a product, printing the list of products, saving the list in a file, and continuing to use the system.

In Phase 3, the client will interact with the system through a graphical user interface (GUI). The GUI should look like the mock-up provided below, and the user can select from a drop-down menu which type of product can be visualized. The user can sort the list alphabetically and add items to the shopping cart.

When implementing these functions, the items with reduced availability should be in red on the table, product details should appear in a panel below the table, the user can add items to the shopping cart by clicking the "Shopping Cart" button, and the shopping cart will show the list of products and the final price. To calculate the final price, the system will apply discounts: 20% discount when the user buys at least three products of the same category, and 10% discount for the first purchase.

To implement this functionality, the history of the purchases made by each client can be maintained, and if the discount is applied, a message will appear on the GUI showing the final cost.
