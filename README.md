# Day-15
Coffee Machine Program ☕
This is a Python-based simulation of a coffee machine. Users can select from three types of drinks—espresso, latte, and cappuccino. The program handles resource management, accepts payments, calculates change, and tracks profits. It also provides a report of remaining resources and earnings upon request.

Features 🌟
Drink Options: Choose between espresso, latte, or cappuccino.
Resource Management: Checks if there are sufficient ingredients for the selected drink.
Payment System: Accepts coins (quarters, dimes, nickels, and pennies) and calculates change.
Profit Tracking: Keeps track of the total money earned.
Admin Features:
View a detailed report of available resources and profits.
Turn off the coffee machine simulation.
Prerequisites 📋
Python 3.x installed on your system.
Basic knowledge of running Python scripts.
How to Run the Program 🚀
Clone or download this repository.
Open the coffee_machine.py file in your preferred IDE or text editor.
Run the program using the command:
bash
Copy
Edit
python coffee_machine.py
Follow the on-screen prompts to interact with the coffee machine.
Program Flow 🔄
Start: The program welcomes the user and provides options to select a drink.
Choose a Drink:
User selects from espresso, latte, or cappuccino.
The program checks if there are enough ingredients.
Insert Coins:
User inserts coins, and the program calculates the total amount received.
If the amount is insufficient, it refunds the money and restarts.
Make Coffee:
If payment is sufficient, it deducts ingredients and serves the drink.
Displays the change (if any) and thanks the user.
Admin Options:
report: Displays the current resources and total profit.
off: Turns off the coffee machine simulation.
Code Structure 🛠️
Key Functions:
is_resource_sufficient(order_ingredients):

Checks if the machine has enough resources for the selected drink.
Returns True if resources are sufficient, otherwise False.
process_coins():

Calculates the total value of inserted coins.
Supports quarters, dimes, nickels, and pennies.
is_transaction_successful(money_received, drink_cost):

Verifies if the payment is sufficient for the drink.
Tracks profits and returns any change if necessary.
make_coffee(drink_name, order_ingredients):

Deducts the required ingredients from the resources.
Serves the selected drink.
