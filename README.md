# Patient Information Management System

This Python program is designed to manage patient information using a MySQL database. It includes a graphical user interface (GUI) built with Tkinter.

## Features

- **Search Patients**: Search for patients by their ID and view their details.
- **Voice Search**: Utilize voice recognition to search for patient IDs.
- **Register Patients**: Register new patients and store their information in the database.
- **Update Patient Details**: Update existing patient information in the database.
- **Print Patient Details**: Print patient details using the built-in print functionality.
- **Security Features**: Includes login functionality with username and password, as well as a security key for password recovery.

## Prerequisites

Before running the program, ensure you have the following installed:

- Python (version 3.x)
- MySQL database server
- Required Python libraries: tkinter, pyttsx3, mysql.connector, speech_recognition

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/pratik-roshan/Minor-Project.git
    ```
2. Install the required Python libraries:
    ```bash
    pip install tkinter
    ```
    ```bash
    pip install pyttsx3
    ```
    ```bash
    pip install mysql-connector-python
    ```
    ```bash
    pip install speechrecognition
    ```
    
3. Set up your MySQL database and configure the connection details in the code.

## Usage

1. Run the program:
    ```bash
    python patientlog.py
    ```
2. Log in with your username and password.
3. Use the GUI to search, register, update patient details, etc.
