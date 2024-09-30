# A-Simple-Banking-System-Using-Python

This is a simple banking system implemented in Python, allowing users to perform basic banking operations such as balance inquiry, withdrawal, and deposit. The system utilizes a basic PIN-based authentication for user access. Using ATM.

## Features

- **PIN Authentication**: Users can access their account by entering a valid PIN.
- **Balance Inquiry**: Users can check their current account balance.
- **Withdraw Funds**: Users can withdraw money from their account (if sufficient funds are available).
- **Deposit Funds**: Users can deposit money into their account.

## Code Explanation

The code initializes three lists:
- `pin`: Contains the PINs for the users.
- `balance`: Contains the corresponding account balances for each user.
- `name`: Contains the names of the users.

### Main Functionality

1. **User Input**: The program prompts the user to enter their PIN.
2. **Menu Options**: Upon successful authentication, users are presented with a menu of options:
   - Balance Inquiry
   - Withdraw Funds
   - Deposit Funds
   - Exit the program
3. **Operations**:
   - **Balance Inquiry**: Displays the current balance of the user.
   - **Withdraw**: Allows users to withdraw an amount, checking for sufficient funds before processing.
   - **Deposit**: Users can deposit an amount, updating their balance accordingly.
4. **Exit**: Users can exit the program at any time by selecting the exit option.

## Usage

To run the program, ensure you have Python installed on your machine. Then execute the script in your terminal or command prompt:

```bash
python Atm.py
