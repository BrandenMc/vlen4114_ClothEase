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
    git clone https://github.com/vlen4114/ClothEase.git
    ```

2. Navigate to the project directory:

    ```bash
    cd ClothEase
    ```

3. Compile the source code:

    ```bash
    g++ -o ClothEase main.cpp
    ```

4. Run the executable:

    ```bash
    ./ClothEase
    ```

## Usage

Upon running the program, you will be presented with a menu with the following options:

1. **View All Clothes**: Displays a list of all clothing items in the inventory.
2. **Add Clothing**: Prompts you to enter details for a new clothing item and adds it to the inventory.
3. **Edit Clothing**: Prompts you to enter the name of the clothing item you want to edit, then allows you to update its details.
4. **Remove Clothing**: Prompts you to enter the name of the clothing item you want to remove and deletes it from the inventory.
5. **Find Clothing**: Prompts you to enter the name of the clothing item you want to find and displays its details.
6. **Exit**: Exits the program.


## Project Structure

- `main.cpp`: Contains the main logic and the `ClothesInfo` class definition.
- `CLOTH.dat`: Binary file used to store the clothing items data persistently.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was created as a part of learning the course 21CSC101T(Object Oriented Design and Programming) of SRM Institute of Science and Technology.
- Special thanks to the open-source community for their valuable input.

