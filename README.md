# mybank![242240578-55c3c0ce-15a6-457d-9cf7-b7f2dca0eadd](https://github.com/Edafeemmanuel/mybank/assets/96774741/9ac25e4e-1d49-428e-8d49-7e07ef87428c)
MyBank is a simple banking application implemented in C. It provides basic banking functionalities such as creating an account, transferring money, depositing money, checking the account balance, and generating transaction receipts.

Prerequisites
To compile and run MyBank, ensure that you have the following:

C compiler (e.g., GCC) installed on your system.
Getting Started
Follow the steps below to get started with MyBank:

Clone the repository or download the source code:
git clone https://github.com/your-username/mybank.git
Compile the code using a C compiler:
gcc -o mybank mybank.c
Run the executable:
./mybank
Usage
Upon running the program, you will be prompted to create an account by entering your first and last names.

Enter your password. The program will validate the password by asking you to re-enter it. You have three attempts to enter the correct password.

Once your password is validated, you will be welcomed to MyBank, and your initial account balance of 50,000 will be displayed.

The following options are available in the menu:

a. Transfer Money: Transfer a specified amount from your account to another recipient's account. Enter the recipient's account name, account number, bank name, and the transfer amount. If the transfer amount exceeds your account balance, an insufficient balance message will be displayed.

b. Deposit Money: Deposit a specified amount into your account. Enter the deposit amount. If the deposit amount is invalid (less than or equal to zero), an error message will be displayed.

c. Check Balance: Check the current balance of your account.

d. Quit the Program: Exit the program.

After each transaction, a transaction receipt will be generated and saved in a file named "receipt.txt". The receipt contains details such as the transaction type, account name, account number, bank name, transaction amount, previous balance, current balance, and the date and time of the transaction.

Collaboration
Contributions to MyBank are welcome! If you would like to collaborate on this project, please follow these steps:

Fork the repository on GitHub.
Create a new branch with a descriptive name:
git checkout -b feature/my-new-feature
Make your modifications and write tests if necessary.
Commit your changes:
git commit -am 'Add some feature'
Push the branch to your forked repository:
git push origin feature/my-new-feature
Submit a pull request detailing the changes you made.
Author
MyBank is developed and maintained by Bwave ICT.

License
This project is licensed under the MIT License.

Acknowledgments
The implementation of MyBank was inspired by the need for a simple banking application to demonstrate basic programming concepts.

Support
If you have any questions, suggestions, or encounter any issues while using MyBank, please feel free to open an issue. Your feedback is highly appreciated!
