# Bank of India Basic Banking System

## Overview
This Python script is a simple simulation of a basic banking system for Bank of India. It allows users to perform actions like checking their account balance, withdrawing and depositing funds, and changing their PIN. The script aims to provide a straightforward user experience with fundamental security measures.

## Key Features
1. **Welcome Screen:**
    - The system starts with a warm welcome message.

2. **Authentication:**
    - Users are required to enter their PIN to access banking features.
    - Account blocking occurs after three consecutive incorrect PIN entries for security.

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
    - Allows users to withdraw funds, ensuring there's enough balance.

6. **Deposit Funds:**
    - Enables users to deposit funds into their account.

7. **Change PIN:**
    - Users have the option to change their PIN for enhanced security.

8. **Object Factory:**
    - Implements an object factory pattern for creating instances of various components (Welcome, Authenticate, Menu, Balance, Withdraw, Deposit, Ledger).

## How to Use
1. **Run the Script:**
    - Execute the Python script to initiate the banking system.
    
2. **Follow Prompts:**
    - Enter the PIN when prompted.
    - Choose desired actions from the menu.
    - Complete transactions as needed.

3. **Exit:**
    - Choose the "Exit" option to close the banking system.

## Security Considerations
1. **PIN Authentication:**
    - Users must provide the correct PIN to access their account.
    - Account blocking occurs after three consecutive incorrect PIN entries.

2. **User Feedback:**
    - Clear and informative messages guide users through each step.

3. **Account Block:**
    - After too many incorrect PIN attempts, the account is blocked.
    - Additional measures, like contacting customer support, can be implemented.

## Dependencies
- Python 3.x

## Acknowledgments
This basic banking system script is designed for educational purposes and is not intended for use in actual banking operations. It serves as a simple example of a console-based banking application. Feel free to explore and modify the code to meet your learning and development needs.
