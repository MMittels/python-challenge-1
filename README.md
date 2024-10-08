# Python Challenge 1

## Overview
Python Challenge 1 was developed as an assignment from the University of Denver's Artificial Intelligence Bootcamp. The assignment specifically was to design an interactive ordering system from a food truck.

## Description
The python code, menu.py, can be utilized by food trucks as an interactive ordering systm. When the code is run it will first present main menu categories that can be selected by the user by typing in the corresponding number. Typing in a correponding number to the main menu categories will then present the detailed menu items that can be selected by the user. The code will then prompt for the quantity and ask if the user would like to order more items. Menu.py will either close out the order or continue to loop the ordering process as long as the user selects to continue to order. Once ordering is complete a copy of the receipt is displayed with each item ordered, the price, and quantity. All ordered items are summed to give a total price for the order.

## Demonstration

### First Menu
The first menu below prompts the user to select the menu they would like to order from: snacks, meals, drinks, dessert.

![Alt text](/First_Menu.png?raw=true "First Menu")

### Detailed Menu
The detailed menu shows specific items from the menu to be odered. The user can select a specific item and then will be prompted for the quantity they want.

![Alt text](/SubMenu.png?raw=true "Detailed Menu")

The user will then be asked if they want to continue ordering. If yes, the user will be presented with the first menu again.  It will continue to loop until the user indicates they want to stop ordering.  The user will then see a receipt of the items they ordered with a total (below).

![Alt text](/Receipt.png?raw=true "Receipt")
