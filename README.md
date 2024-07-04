# CUSTOM_DICTIONARY-APPLICATION
Your custom dictionary application is a Java-based graphical user interface (GUI) tool that allows users to manage a collection of useful words without the need for a database. This lightweight dictionary application enables users to save, search, and add words efficiently. The application provides an intuitive interface with both menu and toolbar options for easy access to its functionalities.

Key Features:
Add Word:

Users can add new words to the dictionary for future reference. This feature is accessible through the "Add Word..." menu item or the corresponding toolbar button.
Delete Word:

Users can remove words from the dictionary when they are no longer needed. This feature is accessible through the "Delete Word..." menu item or the corresponding toolbar button.
Search Word:

Provides a search functionality that allows users to quickly find specific words within the dictionary. This feature is accessible through the "Search Word..." menu item or the corresponding toolbar button.
List Words:

Displays a list of all the words currently saved in the dictionary. This feature is accessible through the "List Words" menu item or the corresponding toolbar button.
Save Dictionary:

Saves the current state of the dictionary to disk, ensuring that users' entries are preserved between sessions. This feature is accessible through the "Save Dictionary" menu item in the "Storage" menu or the corresponding toolbar button.
Load Dictionary:

Loads the dictionary from disk, restoring the words saved in previous sessions. This feature is accessible through the "Load Dictionary" menu item in the "Storage" menu or the corresponding toolbar button.
Exit Application:

Allows users to exit the application safely. If there are unsaved changes, the user is prompted to save them before exiting.
Components:
JFrame:

The main window of the application, titled "Dictionary".
JMenuBar:

A menu bar that contains menus and menu items for dictionary operations.
JToolBar:

A toolbar providing quick access to dictionary operations through icon buttons.
JMenu:

Two main menus: "Dictionary" for word operations and "Storage" for save/load operations.
JMenuItem:

Menu items for various operations like adding, deleting, searching, listing words, and managing storage.
ImageIcon:

Icons associated with menu items and toolbar buttons to enhance the visual interface.
Methods:
getImage(String filename):

Returns an ImageIcon for the given filename located in the /images/ directory.
centerToParent(JFrame parent, JFrame child):

Centers a child window relative to its parent window.
addWord():

Opens the "Add Word" window.
deleteWord():

Opens the "Delete Word" window.
searchWord():

Opens the "Search Word" window.
listWords():

Opens the "List Words" window.
addToolbar():

Adds a toolbar with buttons for quick access to dictionary operations.
addStorageMenu(JMenuBar mb):

Adds the "Storage" menu to the menu bar with items for saving and loading the dictionary.
exit():

Handles the exit operation, prompting the user to save changes if necessary.
