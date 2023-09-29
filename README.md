# Phone Book Management System

This C++ program is a simple Phone Book Management System that allows users to create, modify, search for, and delete contacts. It uses a doubly linked list to store contact information, and data is persisted in a file. The program provides a text-based user interface for interacting with the phone book.


## Features

- **Add New Contact**: Users can add new contacts by providing their first name, last name, phone number, and address. The program ensures that contacts are stored in sorted order by last name and then by first name.

- **Modify Contact**: Users can modify specific fields (last name, first name, phone number, or address) of an existing contact.

- **Delete Contact**: Users can delete a contact from the phone book.

- **List Contacts**: The program can list all contacts in alphabetical order.

- **Search Contacts**: Users can search for contacts by last name, first name, or phone number.

- **Persistence**: Contacts are saved to a file when the program exits and are loaded from the file when the program starts.

## Requirements

- C++ Compiler (e.g., g++)
- Windows OS (for `_getch()` function) or equivalent alternative for non-Windows systems
- Text Editor or Integrated Development Environment (IDE)

