# python-challenge-1

## Background:
Design an interactive ordering system from a food truck menu.
A main menu will be created along with a submenu with pricing.
The code will require user input and provide a detailed description of items ordered
such as the quantity, prices, and a total cost for a given order.
The code will use lists, a dictionary, conditional statements, for loops, and match case
statements.
This code is available at Github under (https://github.com/algjor/python-challenge-1/blob/main/menu.py)

## Description of Code:
This code was completed using the following steps.
(1) - A repository was created called python-challenge-1 in Git hub.
(2) - A starter file named menu.py was created on the local Git repository and pushed to GitHub.
(3) - An empty list was created to store the customer order. 
(4) - A line of code was created to prompt customer to select a menu option called <menu_selection>.
(5) - A validation of the menu_selection was performed to check if this input was an integer with a corresponding error message if not an integer.  The user was then prompted to enter a number from the menu_selection.
(6) - The customer is prompted to choose from the sub-menu called <menu_items> with a corresponding error message if a number is not correctly chosen from the sub-menu.
(7) - The customer is then prompted to choose the quantity of the items chosen called <quantity>.
(8) - A while loop was created to prompt the customer to keep ordering and a match case used to ensure customer responds correctly to a (Yes) and (No) question.
(9) - An order receipt was generated and formatted using a for loop that included the item name, price, and quantity.
(10) - A total cost for the customer order was calculate using list comprehension and displayed.
 

