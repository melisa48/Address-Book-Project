# Address Book Program
# Overview
This C++ Address Book program allows users to manage contacts by performing various operations such as adding, viewing, searching, editing, and deleting contacts.

# Features
Add Contact: Add a new contact to the address book.
View Contacts: Display all contacts in the address book.
Search Address Book: Search for a contact by first name, last name, address, or contact number.
Edit Contact: Modify the details of an existing contact.
Delete Contact: Remove a contact from the address book.

# How to Use
1) Compilation:
Compile the program using a C++ compiler (e.g., g++, Visual C++).
bash
g++ AddressBook.cpp -o AddressBook
2) Run the Program:
Execute the compiled program.
bash
Copy code
./AddressBook
3) Main Menu:
Choose an option from the main menu (1-6) using the provided prompts.
Options include adding a contact, editing, deleting, viewing all contacts, searching, and exiting the program.
4) Contact Entry:
When adding or editing a contact, follow the instructions to input the contact details.
5) View Contacts:
Displays a table of all contacts in the address book.
6) Search Address Book:
Choose a search criteria (first name, last name, address, or contact number) and enter the corresponding value to find a specific contact.
7) Edit Contact:
Specify the entry number of the contact you want to edit and follow the prompts to update the information.
8) Delete Contact:
Specify the entry number of the contact you want to delete and confirm the deletion.
9) Exit:
Choose option 6 to exit the program.
# File Management
Contact information is stored in the "AddressBook.txt" file.
The program uses temporary files ("Temp.txt") during editing and deleting operations.
 # Notes
Ensure that the program is compiled and executed in an environment with file write permissions.
