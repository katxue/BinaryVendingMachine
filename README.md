# BinaryVendingMachine
Problem Statement
You are asked to build a binary vending machine program in C++. This machine is called “binary” since
it sells only two items of user's choice. The names, prices, and initial amount of these items will be
defined by the user. Additionally, the vending machine will only accept dollars ($1) and quarters ($0.25)
as payment. Thus, the price of each item must be a multiple of 0.25.
Detailed Requirements:
1. Item definition
The program should start by asking the user to enter the names and prices of two items, and the
initial amount of each item available in the machine. The amount of each item should be greater than
0. The price of each item must be a multiple of 0.25. Re-prompt the user until a valid input is given.
2. Item purchase
The user can then choose to buy an item or quit. When the user chooses to buy an item, the
program should check if the item is available. If the item is not available, the program should then
ask the user to choose a different item or quit, until a valid input is given. Otherwise, the program
should prompt the user to insert coins, one at a time. The user can insert either a dollar or a quarter,
or they can stop inserting coins. The program should keep track of the total amount inserted by the
user and stop prompting as soon as the user has inserted enough money.
3. Payment calculation
Once the user has finished inserting coins or decides to stop, the program should determine if the
inserted coins are enough to buy the item. If it is, the program should dispense the item and return
the change (if any), otherwise return all the inserted coins back to the user.
4. Update Item availability
After a successful purchase, the program should update the available amount of the item in the
machine.
5. Buy it again
The user can repeat the process of buying an item or quit the program. Remember, if the chosen
item is out of stock, the program should inform the user and prompt them to choose another item or
quit.
6. Display Requirements
Before each purchase, the program should display the items, their prices, and amounts available.
After each coin insertion, the program should print the cost of the item and the total inserted coin
amount.
