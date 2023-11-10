# python-challenge-1


## Overview

This Python script provides a simple command-line interface for customers to place food orders from a variety food truck. The menu is organized into categories of Snacks, Meals, Drinks, and Desserts. Customers can browse the menu, select items, specify quantities, and view their order summary, including the total cost.

## Usage

    1. Run the script.
    2. Follow the on-screen prompts to navigate the menu and place your order.
    3. Review your order and confirm or make changes.
    4. Once you're finished, the script will display a summary of your order, including the total cost.

## Menu Structure

The menu is structured as a nested dictionary, with categories such as Snacks, Meals, Drinks, and Desserts. Each category contains various food and beverage items with associated prices. Some items, like Pizza and Cheesecake, have additional nested options.

## How to Place an Order

    1. The script initializes an empty order list to store selected items.
    2. Customers choose a menu category by entering the corresponding number.
    3. The script displays the selected category's items and prices.
    4. Customers choose a specific item by entering its number.
    5. Customers enter the quantity of the selected item.
    6. The script adds the item, price, and quantity to the order list.
    7. Customers can choose to keep ordering or complete their order.
    8. The script displays the order summary, including the total cost.