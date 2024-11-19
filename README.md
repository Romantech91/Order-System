# Order-System

This project is a simple order system for a generic take-out restaurant. It allows customers to view a menu, place orders, and receive an itemized receipt with the total price.

## Features

- Display a menu with various food categories and items
- Allow customers to place multiple orders
- Validate customer input for menu selection and quantity
- Calculate the total price of the order
- Print an itemized receipt with the total price

## Functions

### `place_order(menu)`

Displays the restaurant menu, asks customers for their order, and returns their receipt and total price.

**Parameters:**
- `menu` (dictionary): A nested dictionary containing the menu items and their prices.

**Returns:**
- `order` (list): A list of dictionaries containing the menu item name, price, and quantity ordered.
- `order_total` (float): The total price of the order.

### `update_order(order, menu_selection, menu_items)`

Checks if the customer menu selection is valid, then updates the order.

**Parameters:**
- `order` (list): A list of dictionaries containing the menu item name, price, and quantity ordered.
- `menu_selection` (str): The customer's menu selection.
- `menu_items` (dictionary): A dictionary containing the menu items and their prices.

**Returns:**
- `order` (list): A list of dictionaries containing the menu item name, price, and quantity ordered (updated as needed).

### `print_itemized_receipt(receipt)`

Prints an itemized receipt for the customer.

**Parameters:**
- `receipt` (list): A list of dictionaries containing the menu item name, price, and quantity ordered.

### `print_receipt_line(item_name, price, quantity)`

Prints a line of the receipt.

**Parameters:**
- `item_name` (str): The name of the meal item.
- `price` (float): The price of the meal item.
- `quantity` (int): The quantity of the meal item.

### `print_receipt_heading()`

Prints the receipt heading.

### `print_receipt_footer(total_price)`

Prints the receipt footer with the total price of the order.

**Parameters:**
- `total_price` (float): The total price of the order.

### `print_menu_heading()`

Prints the menu heading.

### `print_menu_line(index, food_category, meal, price)`

Prints a line of the menu.

**Parameters:**
- `index` (int): The menu item number.
- `food_category` (str): The category of the food item.
- `meal` (str): The name of the meal item.
- `price` (float): The price of the meal item.

### `get_menu_items_dict(menu)`

Creates a dictionary of menu items and their prices mapped to their menu number.

**Parameters:**
- `menu` (dictionary): A nested dictionary containing the menu items and their prices.

**Returns:**
- `menu_items` (dictionary): A dictionary containing the menu items and their prices.

### `get_menu_dictionary()`

Returns a dictionary of menu items and their prices.

**Returns:**
- `meals` (dictionary): A nested dictionary containing the menu items and their prices.

## Running the Program

To run the program, execute the `order_system.py` script. The program will display the menu, allow customers to place orders, and print an itemized receipt with the total price.

```sh
python [order_system.py](http://_vscodecontentref_/1)