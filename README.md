# Customer Management System

This Python project allows you to manage customer data through a CSV file. You can add, delete, find, and view all customers using a simple command-line interface.

## Features

- **Add Customer**: Add a new customer with their details.
- **Delete Customer**: Delete a customer based on their Order ID.
- **Find Customer**: Find and display a customer based on their Order ID.
- **View All Customers**: Display all customers stored in the CSV file.

## Requirements

- Python 3.x
- pandas library

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/mohAhmadRaza/customer-management-system.git
    cd customer-management-system
    ```

2. **Install the required libraries:**
    ```bash
    pip install pandas
    ```

3. **Prepare the CSV file:**
    - Create a CSV file named `Book1.csv` in the specified path `C:\Users\LENOVO\Desktop\Book1.csv`.
    - Ensure the CSV file has the following headers:
      ```
      Name,Order ID,Order Name,Order Date,City
      ```

## Usage

1. **Run the script:**
    ```bash
    python customer_management.py
    ```

2. **Follow the on-screen menu:**
    - Enter `1` to add a new customer.
    - Enter `2` to delete an existing customer.
    - Enter `3` to find a customer by Order ID.
    - Enter `4` to view all customers.
    - Enter `5` to exit the program.

## Code Explanation

### `add_new_customer()`
This function reads the existing customer data from the CSV file, prompts the user for new customer details, adds the new customer to the DataFrame, and writes the updated DataFrame back to the CSV file.

### `delete_any_customer()`
This function reads the customer data from the CSV file, prompts the user for an Order ID, finds and deletes the corresponding customer from the DataFrame, and writes the updated DataFrame back to the CSV file.

### `find_any_customer()`
This function reads the customer data from the CSV file, prompts the user for an Order ID, finds and displays the corresponding customer details.

### `view_all_customers()`
This function reads and displays all the customer data from the CSV file.

### Menu Loop
A loop presents the user with a menu of options to add, delete, find, view customers, or exit the program. The user's choice determines which function is called.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Please ensure your contributions adhere to the coding standards and practices used in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact:

- Name: AhmadRaza
- Email: sktfscm21557034@gmail.com
- GitHub: [mohAhmadRaza](https://github.com/mohAhmadRaza)

