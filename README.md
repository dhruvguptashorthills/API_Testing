# QA Task 2

This project demonstrates the usage of the [Fake Store API](https://fakestoreapi.com/) to perform CRUD operations on products, carts, and users. The script is implemented in a Jupyter Notebook (`script.ipynb`) using Python and the `requests` library.

## Features

1. **Products**:
   - Fetch all products.
   - Fetch a single product by ID.
   - Add a new product.
   - Update an existing product.
   - Delete a product.

2. **Carts**:
   - Fetch all carts.
   - Fetch a single cart by ID.
   - Add a new cart.
   - Update an existing cart.
   - Delete a cart.

3. **Users**:
   - Fetch all users.
   - Fetch a single user by ID.
   - Add a new user.
   - Update an existing user.
   - Delete a user.

## Requirements

- Python 3.10 or later
- `requests` library
- Jupyter Notebook

## Setup

1. Clone this repository or download the files.
2. Install the required Python packages:
   ```bash
   pip install requests
   ```
3. Open the `script.ipynb` file in Jupyter Notebook.

## Usage

1. Run the cells in the notebook sequentially to interact with the Fake Store API.
2. Modify the payloads in the cells to test different scenarios.

## API Reference

- Base URL: `https://fakestoreapi.com/`
- Refer to the [Fake Store API documentation](https://fakestoreapi.com/docs) for more details.

## Notes

- The API is a mock service, so changes made (e.g., adding or updating data) may not persist.
- Ensure you have an active internet connection to interact with the API.

## License

This project is for educational purposes and does not include any proprietary code.
