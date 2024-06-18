# ClothEase

This project is a simple Clothing Management System implemented in C++ using object-oriented programming principles. It allows users to add, view, edit, remove, and find clothing items with details such as name, size, color, quantity, and price.

## Features

- **Add Clothing**: Add new clothing items to the inventory.
- **View All Clothes**: Display all clothing items in the inventory.
- **Edit Clothing**: Update details of existing clothing items.
- **Remove Clothing**: Remove clothing items from the inventory.
- **Find Clothing**: Search for clothing items by name.

## Getting Started

### Prerequisites

- C++ compiler
- Standard C++ library
- Basics of OOPS concepts

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/clothing-management-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd clothing-management-system
    ```

3. Compile the source code:

    ```bash
    g++ -o clothing_management_system main.cpp
    ```

4. Run the executable:

    ```bash
    ./clothing_management_system
    ```

## Usage

Upon running the program, you will be presented with a menu with the following options:

1. **View All Clothes**: Displays a list of all clothing items in the inventory.
2. **Add Clothing**: Prompts you to enter details for a new clothing item and adds it to the inventory.
3. **Edit Clothing**: Prompts you to enter the name of the clothing item you want to edit, then allows you to update its details.
4. **Remove Clothing**: Prompts you to enter the name of the clothing item you want to remove and deletes it from the inventory.
5. **Find Clothing**: Prompts you to enter the name of the clothing item you want to find and displays its details.
6. **Exit**: Exits the program.

### Example

Here is an example of how to use the program:

1. Choose option `2` to add a new clothing item.
2. Enter the details for the new clothing item (name, size, color, quantity, price).
3. Choose option `1` to view all clothes and see the new item added.
4. Choose option `3` to edit an existing clothing item.
5. Choose option `4` to remove a clothing item.
6. Choose option `5` to find a specific clothing item by name.
7. Choose option `6` to exit the program.

## Project Structure

- `main.cpp`: Contains the main logic and the `ClothesInfo` class definition.
- `CLOTH.dat`: Binary file used to store the clothing items data persistently.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was created as a part of learning object-oriented programming in C++.
- Special thanks to the contributors and the open-source community for their valuable input.

