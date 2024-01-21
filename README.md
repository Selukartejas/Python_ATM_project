# README

## Overview
This Python script simulates a basic banking system for Bank of India. It provides functionalities such as checking balance, withdrawing funds, depositing funds, and changing the PIN. The system is designed with a simple user interface and basic security measures.

## Features
1. **Welcome Screen:**
    - Displays a welcoming message upon initiating the banking system.

2. **Authentication:**
    - Users need to enter their PIN to access banking functionalities.
    - Three incorrect attempts lead to an account block for security.

3. **Menu:**
    - Users can choose from the following options:
        - Check Balance
        - Withdraw Funds
        - Deposit Funds
        - Change PIN
        - Exit

4. **Check Balance:**
    - Displays the current account balance.

5. **Withdraw Funds:**
    - Allows users to withdraw funds from their account.
    - Checks for sufficient balance before processing the withdrawal.

6. **Deposit Funds:**
    - Enables users to deposit funds into their account.

7. **Change PIN:**
    - Users can change their PIN for added security.

8. **Object Factory:**
    - Implements an object factory pattern for creating instances of different components (Welcome, Authenticate, Menu, Balance, Withdraw, Deposit, Ledger).

## Usage
1. **Run the script:**
    - Execute the Python script to start the banking system.
    
2. **Follow the prompts:**
    - Enter the PIN as prompted.
    - Choose from the menu options.
    - Perform transactions as needed.

3. **Exit:**
    - Choose the "Exit" option to terminate the banking system.

## Security Considerations
1. **PIN Authentication:**
    - Users must enter the correct PIN to access their account.
    - Account block after three consecutive incorrect PIN entries.

2. **User Feedback:**
    - Informative messages guide users through each step of the process.

3. **Account Block:**
    - In case of too many incorrect PIN attempts, the account is blocked.
    - Additional measures can be implemented, such as contacting customer support.

## Dependencies
- Python 3.x

## Acknowledgments
This basic banking system script is designed for educational purposes and is not intended for use in actual banking operations. It serves as a simple example of a console-based banking application.

Feel free to explore and modify the code to suit your learning and development needs.

**Disclaimer:** This script is not suitable for use in a production environment and is solely intended for educational purposes.
