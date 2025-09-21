# java-assignment
 Banking Application for Account Management
Name -Krishna sobti
class- Btech cse (cybersecurity)
roll no :- 2401410034

Project Title: Banking Application for Account Management
Problem Statement:
Design and implement a banking application that allows users to manage their bank accounts through various operations such as creating accounts, depositing money, withdrawing money, and viewing account details. The application should incorporate the concepts of Java features, control structures, arrays, and strings as per the syllabus.
Project Objectives:
• Apply the basics of Java programming including data types, operators, control structures, and type casting.
Utilize Java's control structures for decision making and
looping.
Implement basic 1/O operations using the Scanner class.
• Handle single and multi-dimensional arrays.
• Manipulate strings using Java's String class and methods.
Learning Outcomes:
COs
CO1
Develop a foundational understanding of Java programming.
Gain practical experience with Java control structures and data
handling.
Implement real-world applications using Java arrays and
strings.
Learn to manage and share code using GitHub.
Project Instructions:
1. Account Class Design:
• Attributes:
accountNumber: Integer, Unique account
number.
accountHolderName: String, Name of the
account holder.
balance: Double, Current balance in the account.
• email: String, Email address of the account holder.
phoneNumber: String, Contact number of the
account holder.
• Methods:
deposit(double amount): Method to deposit money into the account. It should validate the amount to be positive.
• withdraw(double amount): Method to withdraw money from the account. It should validate the amount to be positive and ensure sufficient balance.
• displayAccountDetails): Method to display the current account details.
• updateContactDetails(String email, String phoneNumber): Method to update the contact details of the account holder.
2. User Interface Class:
• Attributes:
• Array to store multiple Account objects.
• Scanner object for input.
• Methods:
• createAccount): Method to create a new account. Collects account details from the user and stores them in the array.
• performDeposit): Method to handle deposit operations. Prompts for account number and amount
performWithdrawal): Method to handle withdrawal operations. Prompts for account number and amount to withdraw.
• showAccountDetails): Method to display account details. Prompts for account number.
update Contact): Method to update contact details. Prompts for account number and new
Create the UserInterface class to interact with users and manage multiple accounts.
mplement the methods to handle different operation uch as account creation, deposit, withdrawal, and displa details.
Stilize Java control structures for decision making al ps to navigate through the menu and handle various us
inputs.
• Use arrays to manage multiple accounts dynamically.
• Employ string handling techniques for managing account holder names and contact details.
4. Sample Interaction:
Welcome to the Banking Application!
1. Create a new account
2. Deposit money
3. Withdraw money
1. View account details
5. Update contact details
6. Exit
