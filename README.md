# Password Manager

This repository contains a Python-based password manager application with a graphical user interface (GUI) built using Tkinter. The application allows users to generate, store, and retrieve secure passwords for different websites. All data is saved in a JSON file for persistent storage.

## Features

- **Password Generation:**
  - The application can generate strong, random passwords that include letters, numbers, and symbols.
  - Generated passwords are automatically copied to the clipboard for easy pasting.

- **Data Storage:**
  - User credentials (website, email/username, and password) are stored in a `data.json` file.
  - If the JSON file doesn't exist, it will be created automatically.

- **Search Functionality:**
  - Users can search for stored credentials by entering the website name.
  - If the website is found, the stored email/username and password are displayed.

- **User-Friendly Interface:**
  - The GUI is designed with ease of use in mind, featuring clear labels, buttons, and input fields.

## How It Works

### 1. Password Generation
The password generator creates a password with a random combination of letters, numbers, and symbols. The password is then inserted into the password field and copied to the clipboard.

### 2. Adding New Entries
When the user clicks the "Add" button, the application saves the website, email/username, and password in the JSON file. If the JSON file doesn't exist, it creates a new one.

### 3. Searching for Stored Credentials
Users can retrieve stored credentials by entering the website name and clicking the "Search" button. The application checks the JSON file and displays the email/username and password if the website is found.

### Example

#### Generated Password:
