# Login-Page
*By Bamboothesecond
#!/usr/bin/env python3

"""
MIT License Header
-------------------

This code is for personal use only and should not be distributed without my permission.
"""

# Add your code here

This code provides a simple login page with a graphical user interface (GUI) built with the tkinter module. Additionally, it uses the Pygame and shelve modules to implement features like playing sound effects and storing user credentials.

The script imports several modules at the beginning, including random, tkinter, PIL, pygame, and shelve, to add various functionalities to the application.

The code defines two classes: User and Login. The User class is a simple class with two attributes, username and password, which are used to store the user's credentials. The Login class is the main class that creates the login page window and implements the login functionality.

When an instance of the Login class is created, the constructor is called, which initializes various attributes like the window's size and position, the user list, the music file to be played, and the GUI elements such as labels, buttons, and text fields.

The load_credentials method loads the saved user credentials from a shelve database, which is a simple persistent storage system provided by Python. If no credentials are found, an empty list is created.

The login method is called when the user clicks the login button. It retrieves the username and password entered by the user and checks whether they match with the credentials in the user list. If they match, a success message is shown, and the text fields are cleared. Otherwise, an error message is displayed.

The register method is called when the user clicks the register link. It creates a new window for registration and hides the current login window.

Overall, this code creates a simple GUI login page with login and registration functionality. Please note that this script is not intended for distribution, especially without permission from the author.
