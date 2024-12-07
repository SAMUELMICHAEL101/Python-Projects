# CraveCart - Food Ordering Application

## Overview
CraveCart is a command-line interface (CLI) food ordering application built in Python. It simulates a restaurant ordering system where users can browse a menu, add items to their cart, modify quantities, and complete purchases.

## Features
- Interactive menu display with prices
- Shopping cart management:
  - Add items with custom quantities
  - Remove items
  - Modify item quantities
- Real-time cart viewing with subtotal, tax, and final total calculations
- Checkout process
- Input validation and error handling
- Clean exit functionality

## Technical Implementation
### Data Structures
- Dictionary-based menu system using SKUs as unique identifiers
- Shopping cart implementation using dictionary for efficient item tracking
- Structured action mapping for user interface options

### Key Components
1. **Menu Management**
   - Centralized menu dictionary with SKU, name, and price mapping
   - Formatted display function for easy reading

2. **Cart Operations**
   - Add to cart functionality with quantity support
   - Remove from cart with validation
   - Quantity modification system
   - Real-time total calculation

3. **User Interface**
   - Clear command-line interface
   - Intuitive action selection system
   - Organized display of information
   - Interactive prompts for user input

### Core Functions
- `display_menu()`: Shows available items and prices
- `add_to_cart()`: Handles item addition with quantity
- `remove_from_cart()`: Manages item removal
- `modify_cart()`: Updates item quantities
- `view_cart()`: Displays current order with calculations
- `checkout()`: Processes final order
- `get_sku_and_quantity()`: Handles user input with validation
- `order_loop()`: Main application loop

## Technical Details
- **Language**: Python 3.x
- **Data Types Used**: 
  - Dictionaries
  - Strings
  - Integers
  - Floating-point numbers
- **Error Handling**: Try-except blocks for input validation
- **Constants**: Predefined tax rate and restaurant name
- **Input Validation**: Numeric input checking and boundary validation

## Development Highlights
- Modular code structure for easy maintenance
- Robust error handling for user inputs
- Clear separation of concerns between different functionalities
- Efficient data structure usage for cart management
- Scalable menu system using SKUs

## Running the Application
1. Ensure Python 3.x is installed
2. Download the project files
3. Run the script using Python:
   ```bash
   python food_ordering_app.py
   ```

## Future Enhancements
- Database integration for menu items
- User authentication system
- Order history tracking
- Payment processing integration
- GUI implementation
- Receipt generation
- Multiple restaurant support

## Skills Demonstrated
- Python programming
- Data structure implementation
- User interface design
- Input validation and error handling
- Mathematical calculations
- System design
- Code organization and modularity
