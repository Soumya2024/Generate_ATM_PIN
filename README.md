# Generate_ATM_PIN

ATMs are Automated Teller Machines that are used to carry day-to-day financial transactions. ATMs can be used to withdraw money or to deposit money or even to know the information of an account like the balance amount, etc. They are convenient and easy to use,and  it allows consumers to perform quick self-service transactions.

In this article, we will discuss the ATM Management System in C++ which is an application that provides users with every aspect that an actual Automated Teller Machine i.e., ATM should have. It is a menu-driven program having ATM functions which include:

Enter Name, Account number, Account type to be shown during transactions.
Shows the information about the person who is doing the transaction.
Enter amount to deposited in the account.
Shows the Balance in the account.
Enter amount to be withdrawn from the account, and then it shows available balance.
Cancel the transaction.
Approach: This program uses basic concepts of class, Access Modifiers in C++, data types, variables, Switch Case, etc. Below are the functionalities that are to be implemented:

setvalue(): This function is used here to set the data using basic input and output method in C++ i.e., cout and cin statements which display and take input from the keyboard i.e., from the user respectively.
showvalue(): This function is used to print the data.
deposit(): This function helps to deposit money in a particular account.
showbal(): This function shows the total balance available after deposition.
withdrawl(): This function helps to withdraw money from the account.
main(): In this function, there is a simple switch case (to make choices) inside an infinite while loop so that every time user gets to select choices.
Below is the C++ program using the above approach:
