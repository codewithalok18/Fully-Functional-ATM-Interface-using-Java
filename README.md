This is a simple console-based **ATM Interface** implemented in Java. It simulates basic banking operations like:

- User Authentication
- Balance Inquiry
- Deposit
- Withdrawal
- Transaction History

---
## 📂 Project Structure

ATMProject/
├── ATM.java # Model class with balance and transactions
├── ATMInterface.java # Interface defining ATM operations
├── ATMImpl.java # Implementation of ATM functionalities
├── Main.java # Entry point of the application
└── README.md # Project documentation

## 🚀 Features

- Secure login system (with hardcoded credentials)
- Check balance
- Deposit money
- Withdraw money with balance check
- View transaction history
- Simple and interactive CLI interface

---

## 🛠️ How to Run

1. **Clone the project or download the files**
2. **Navigate to the project directory**
3. **Compile the code**  
   ```bash
   javac *.java

    Login Credentials (Demo)
User ID: user1

PIN: 1234

Output Example
plaintext
Copy
Edit
Enter User ID: user1
Enter PIN: 1234
Login successful.

--- ATM Menu ---
1. View Balance
2. Deposit Amount
3. Withdraw Amount
4. Transaction History
5. Exit
Choose option: 2
Enter amount to deposit: ₹5000
₹5000.0 deposited successfully.

--- ATM Menu ---
1. View Balance
2. Deposit Amount
3. Withdraw Amount
4. Transaction History
5. Exit
Choose option: 1
Current Balance: ₹5000.0

--- ATM Menu ---
1. View Balance
2. Deposit Amount
3. Withdraw Amount
4. Transaction History
5. Exit
Choose option: 4
Transaction History:
Deposited: ₹5000.0

--- ATM Menu ---
Choose option: 5
Thank you for using the ATM!

Author
Made with ❤️ by codewithalok18.
