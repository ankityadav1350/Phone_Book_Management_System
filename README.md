# Phone Book Management System

## Overview

This project is a **Phone Book Management System** implemented in C++. It provides a simple command-line interface for managing contacts, allowing users to add and search for phone numbers and addresses. The data is stored in a text file, ensuring persistent storage across sessions.

## Features

- **Add Contact**: Users can add a new contact by providing a name, phone number, and address.
- **Search Contact**: Users can search for a contact by name to retrieve the associated phone number and address.
- **Persistent Storage**: All contact information is saved in a text file (`PhoneBook.txt`) for future use.

## Installation

1. **Clone the repository** (if applicable) or download the project files to your local machine.
2. **Ensure you have a C++ compiler** installed (e.g., GCC, MSVC).
3. **Compile the source code** using your preferred IDE or command line.

   Example command for compiling using `g++`:
   ```bash
   g++ -o phonebook PhoneBook.cpp
   ```

4. **Run the executable** generated after compilation.

## Usage

1. **Run the program**:
   ```bash
   ./phonebook
   ```

2. **Choose an option** from the main menu:
   - `1. Add Number`: Add a new contact to the phone book.
   - `2. Search Number`: Search for a contact by name.
   - `3. Exit`: Exit the program.

3. **Follow the prompts** to input contact information or search queries.

## File Structure

- **PhoneBook.cpp**: The main source file containing the implementation of the Phone Book Management System.
- **PhoneBook.txt**: The file where contact information is stored.

## Dependencies

- **C++ Standard Library**: Utilized for file handling, string manipulation, and input/output operations.
- **Windows.h**: Used for system-specific functions like `system("cls")` and `Sleep()`.

## Notes

- This program is designed to run on Windows systems due to the use of `windows.h`. 
- Modify the file paths and system-specific commands if running on a different OS.

## License

This project is open-source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests with improvements or bug fixes.
