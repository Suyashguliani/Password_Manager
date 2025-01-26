# Password_Manager
A simple app to manage all your password - keep them safe in your local host

A secure Password Manager application built with Python and Tkinter. This project allows users to store, search, and generate strong passwords efficiently. All data is stored in a local JSON file for easy access and portability.

Features

Password Generator

  Generates strong, random passwords containing letters, numbers, and symbols.

  Automatically copies the generated password to the clipboard for convenience.

Save Passwords

  Stores website login details, including website name, email/username, and password.

  Saves data in a JSON file for persistent storage.

Search Functionality

  Quickly retrieves saved login details for a specific website.

  Displays the email/username and password associated with the website.

Error Handling

  Alerts users when required fields are empty or if the data file is missing.

Technologies Used

  Python: Core programming language.

  Tkinter: For building the graphical user interface (GUI).

  Pyperclip: For clipboard functionality.

  JSON: For storing data locally.

File Structure

password-manager/
├── password_manager.py  # Main application script
├── logo.png             # Logo image for the GUI
├── data.json            # File where passwords are stored (created automatically)
└── README.md            # Project documentation

Usage Instructions

Open the application.

Enter the website name, email/username, and password (or generate one using the "Generate Password" button).

Click "Add" to save the details.

Use the "Search" button to retrieve saved credentials by entering the website name.

Notes

  If the data.json file does not exist, it will be created automatically when you save your first password.

  Always keep the data.json file secure, as it contains all your saved passwords.

License

  This project is licensed under the MIT License. You are free to use, modify, and distribute this software as per the terms of the license.

Contributions

  Contributions are welcome! Feel free to submit a pull request or open an issue if you have     suggestions or encounter any problems.

Acknowledgments

  Inspired by Angela Yu's 100 Days of Code Python course.


