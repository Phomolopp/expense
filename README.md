# Project Description: Expense Tracker
Project Name: Expense Tracker

Objective:
The objective of the Expense Tracker project is to create a simple yet functional application to help users manage their personal finances by tracking their expenses. The application allows users to add, list, and filter expenses based on categories, as well as calculate the total expenses.

# Features:

# Add Expense:

Users can add an expense by entering the amount and category.
Each expense is stored as a dictionary with 'amount' and 'category' keys in a list.
# List All Expenses:

Users can view all the expenses they have added.
The expenses are displayed with the amount and category.
# Show Total Expenses:

The application calculates and displays the total amount of all expenses added.
# Filter Expenses by Category:

Users can filter expenses by a specific category.
The filtered expenses are displayed with the amount and category.
# Exit:

Users can exit the application.
# Technical Details:

The application is written in Python.
It uses basic data structures like lists and dictionaries to store and manage expenses.
The program runs in a loop, allowing users to continuously interact with the application until they choose to exit.
Functions:

add_expense(expenses, amount, category):

Adds a new expense to the list of expenses.
Parameters:
expenses: List to store the expenses.
amount: The amount of the expense.
category: The category of the expense.
print_expenses(expenses):

Prints all the expenses in the list.
Parameters:
expenses: List of expenses to be printed.
total_expenses(expenses):

Calculates the total amount of all expenses.
Parameters:
expenses: List of expenses.
Returns:
The total amount of all expenses.
filter_expenses_by_category(expenses, category):

Filters the expenses by a specific category.
Parameters:
expenses: List of expenses.
category: Category to filter by.
Returns:
A filtered list of expenses belonging to the specified category.
main():

The main function that runs the application.
Provides a menu for users to choose actions.
Handles user input and calls the appropriate functions based on the user's choice.
# User Interaction:

The application runs in a command-line interface.
Users interact with the application through a menu-driven interface.
Input is taken from the user for actions like adding an expense, filtering expenses, and exiting the application.
# Usage:

Run the program.
Choose an action from the menu:
Add an expense by entering the amount and category.
List all expenses to view the expenses added so far.
Show total expenses to see the total amount spent.
Filter expenses by category to view expenses in a specific category.
Exit the application to end the session.
