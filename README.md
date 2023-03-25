# Login-Page
*By Bamboothesecond
*This code is a Python script for a simple login page with a GUI built with the tkinter module. It also uses the Pygame and shelve modules.
*At the beginning of the script, several modules are imported, including random, tkinter, PIL, pygame, and shelve. These are used to add various functionalities to the *application, such as creating graphical user interfaces, playing sound effects, and storing user credentials.
*The code defines two classes, User and Login. The User class is a simple class with two attributes, username, and password, which are used to store the user's *credentials. The Login class is the main class that creates the login page window and implements the login functionality.
*When an instance of the Login class is created, the constructor is called, and it initializes various attributes, including the window's size and position, the user *list, the music file to be played, and the GUI elements such as labels, buttons, and text fields.
*The load_credentials method loads the saved user credentials from a shelve database, which is a simple persistent storage system provided by Python. If no credentials *are found, an empty list is created.
*The login method is called when the user clicks the login button, it retrieves the username and password entered by the user and checks whether they match with the *credentials in the user list. If they match, a success message is shown, and the text fields are cleared. Otherwise, an error message is displayed.
*The register method is called when the user clicks the register link, it creates a new window for registration, and hides the current login window.
*Overall, this code creates a simple GUI login page with login and registration functionality.
