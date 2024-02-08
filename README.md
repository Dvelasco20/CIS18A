# CIS18A
Final Project for CIS18A

Title: David's Sushi House Delivery

Date Published:

[02/08/2024]

Description:
The provided code represents a simple sushi ordering system implemented in Java using Swing for the graphical user interface. Here's an overview of its functionality and structure:

1. **User Interaction**: The program interacts with the user through JOptionPane dialogs to input customer details such as name, pickup date, pickup time, and menu selections.

2. **Selection Class**: There is a Selection class representing the user's selection, including the item name, cost, extra options, and their associated costs.

3. **Main Class (Sushi)**: The main class orchestrates the ordering process. It prompts the user for their details, presents the menu, processes user selections, calculates costs, and writes the order summary to a file named "checkout_list.txt".

4. **Validation Methods**: There are methods to validate user inputs for the customer name, pickup date, and pickup time.

5. **Menu Handling**: The program displays a menu of options for sushi, bento box, salad, milk tea, and a checkout option. Each selection prompts the user for any additional extras they may want with their order.

6. **File Writing**: The program writes the order summary, including the customer's name, selected items, total cost, pickup date, and pickup time, to the checkout_list.txt file.

Programming Approaches:
- The code uses object-oriented programming (OOP) principles, defining classes like Selection to encapsulate related data and behavior.
- It utilizes exception handling for parsing date inputs and file operations.
- It employs a switch-case statement to handle menu selections efficiently.
- The code adheres to best practices by validating user inputs and providing clear error messages.

Basic Instructions:
1. When you run the program, it prompts you to enter your name, pickup date, and pickup time.
2. After entering your details, you'll be presented with a menu of options: Sushi, Bento Box, Salad, Milk Tea, and Checkout.
3. Choose items from the menu by clicking the corresponding buttons.
4. For each selected item, you'll be prompted to select any extra options.
5. Once you're done selecting items, choose "Checkout" to finalize your order.
6. The program calculates the total cost, displays a summary with the pickup details, and writes the order details to the checkout_list.txt file.

In summary, the program provides a simple and interactive way for users to order sushi and related items, while also maintaining an order summary for record-keeping purposes.
