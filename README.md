Bank of Java 💰

A simple Bank Account Simulation program written in Java.
This console-based application allows users to check their balance, deposit money, withdraw money, and exit.


---

Features ✨

✅ Check account balance

✅ Deposit money into the account

✅ Withdraw money (with insufficient funds check)

✅ Exit the application safely



---

How It Works ⚙️

1. When the program runs, the user is presented with a menu:

Welcome to the Bank of Java
1. Check Balance
2. Deposit
3. Withdraw
4. Exit


2. The user enters an option (1–4).


3. Based on the option, the corresponding action is executed.




---

Code Flow 📜

Main Menu: Runs in a loop until the user selects Exit (4).

checkBalance(): Displays the current balance.

deposit(): Takes input and adds money to the balance.

withdraw(): Takes input and deducts money (if sufficient balance).

exit(): Ends the program with a goodbye message.



---

Example Run 🖥️

Welcome to the Bank of Java
1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Enter an option: 2
Enter the amount to deposit: $100
$100.0 has been deposited to your account.
Your current balance is $100.0


---

Requirements 📦

Java 8 or higher

Any IDE (IntelliJ, Eclipse, VS Code) or terminal with javac



---

How to Run ▶️

1. Save the code as Bank.java


2. Open terminal in the file location and run:

javac Bank.java
java Bank


3. Use the menu to interact with your bank account.

