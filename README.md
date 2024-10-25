# User-Management-System
This Python script allows users to add and display user information, which is stored in an Excel file (data.xlsx). The script offers a simple menu-driven interface to perform the following operations:

Add User: Enter user details, including name, email, and phone number. These details are saved in an Excel file. If the file already exists, new entries are appended.
Display Users: Retrieve and display the user data from the Excel file.
Exit: Exit the application.

# Features
Excel-based Storage: Uses pandas to read and write user data in an Excel file (data.xlsx).
Simple Interface: Offers an easy-to-use menu to add users, display all stored users, or exit the application.

# Usage
Run the script:

python Users Data.ipynb

Follow the on-screen instructions:

Press 1 to add a user.

Press 2 to display all stored users.

Press 3 to exit the program.

# Code Explanation

add_user_info: Prompts the user for details (name, email, phone) and saves them to user_data.xlsx.

show_users: Reads and displays the data from data.xlsx if available.

display_menu: Provides a menu interface for the user to interact with the program.

handle_choice: Manages user choices and exits the program when required.
