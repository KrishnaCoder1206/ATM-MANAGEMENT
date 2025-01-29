ATM Management System

Overview
The ATM Management System is a simple C++ console-based program that simulates basic ATM functionalities. This project allows users to perform banking operations such as balance inquiry, money deposit, withdrawal, and account information management.

Features
- Create and store account details (Name, Account Number, Type, and Balance)
- Check account balance
- Deposit money into the account
- Withdraw money from the account
- Display account details
- Exit the program

Technologies Used
- Programming Language: C++
- Standard Libraries: `iostream`, `stdlib.h`, `string.h`

 How to Run the Program
1. Clone this repository or download the source file.
2. Compile the code using a C++ compiler (such as `g++`).
3. Run the executable file.

 Compilation and Execution (Using g++)
```sh
# Compile the code
g++ atm_management.cpp -o atm_management

# Run the executable
./atm_management
```

 Usage
1. Run the program.
2. Choose an option from the menu:
   - 1: Enter account details.
   - 2: Display account information.
   - 3: Deposit money.
   - 4: Show total balance.
   - 5: Withdraw money.
   - 6: Exit the program.
3. Follow the on-screen prompts to complete the transaction.

 Example Output
```
~~~~~~~~~~~~~~~~~~~~~~~~~~WELCOME~~~~~~~~~~~~~~~~~~~~~~~~~~
Enter Your Choice
    1. Enter name, Account number, Account type
    2. Balance Enquiry
    3. Deposit Money
    4. Show Total balance
    5. Withdraw Money
    6. Cancel
```

Improvements & Future Enhancements
- Implement file handling to store user data persistently.
- Add authentication with PIN verification.
- Improve error handling and input validation.
- Implement a GUI-based version using a graphical framework.

