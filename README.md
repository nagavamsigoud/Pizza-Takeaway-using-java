# Pizza-Takeaway-using-java

**Pizza Bill Generator Application**
**Description**
This is a Java-based console application designed to automate the billing process for a pizza shop. It handles different pizza types, including standard and deluxe versions, and calculates costs based on user customizations

**FeaturesPizza Selection: **
Choose between Veg (Rs.300) and Non-Veg (Rs.400) base pizzas.
Deluxe Options: Premium Veg (Rs.550) and Non-Veg (Rs.650) pizzas that come with extra cheese and toppings pre-included.
Custom Add-ons: Options to add extra cheese (Rs.100) or extra toppings (Rs.150) to standard pizzas.
Takeaway Service: Optional takeaway charge of Rs.20.
Detailed Billing: Generates a receipt showing the base price, individual add-on costs, and the final total.

**Project StructureMain.java:**
Contains the entry point and the user interface logic using a Scanner for menu navigation.
Pizza.java: The base class that handles core pricing logic, add-on selections, and bill generation.
Deluxpizza.java: A subclass that inherits from Pizza and overrides methods to automatically include deluxe features.

**How to Run**
Ensure you have the Java Development Kit (JDK) installed on your system.
Clone this repository to your local machine.
Compile the Java files:javac bill/*.java
Run the application:java bill.

**MainUsage Example**
Select a pizza from the menu (Options 1-4).
If selecting a standard pizza, type 'y' or 'n' when prompted for extra cheese or toppings.
Choose whether you want a takeaway ('y'/'n').
The final bill will be printed to the console.

**Technologies Used Language: **
Java Concepts: Object-Oriented Programming (Inheritance, Method Overriding, Encapsulation) Tools: Scanner for console input 
