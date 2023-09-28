**JOT-IT-DOWN**

Notes-taking is a method of jotting down important information for reminders, chores, and other purposes. This keeps us informed about what has to be done and prevents us from neglecting critical duties. I have created a basic Python version of the Pin Your Note project, integrating it with SQL to save the notes. 

It is a program that allows you to mimic regular desk sticky notes on your PC, which is like a TO-DO-LIST. It is designed so you can focus with no distractions, everytime you open up, you can save a new version of your notes to the current database. Sticky Notes works on all major platforms that support Python3 (E.g. Linux, macOS, Windows, etc.).

**1. Installing the Required Libraries:**
   	- In this step, you would typically install any required libraries. In my case, you mentioned that no other libraries are required apart from the built-in libraries Tkinter and SQLite3.

**2. Establishing a Database Connection and Constructing a Table:**
  	- You would connect to an SQLite3 database. SQLite3 is a lightweight, serverless, and self-contained database that can be easily used in Python without additional installation.
   	- Create a table in the database to store notes. The table might have columns such as note_id, title, content, timestamp, etc.

**3. Define Functions for Note Operations:**
     - Implement functions to interact with the database. These functions could include:
     - Adding a new note.
     - Editing an existing note.
     - Viewing all notes.
     - Deleting a note.
   - Each function would involve SQL queries to manipulate the data in the database.

**4. Creating a User Interface:**
   - Use Tkinter, a built-in Python library for creating graphical user interfaces, to build the user interface for your sticky notes application.
   - The interface might include components like text fields for note titles and contents, buttons for saving, editing, deleting, and viewing notes, and a display area to show the list of notes.
   - Implement event handlers for user interactions with the interface. For example, clicking the "Save" button could trigger the function to add a new note to the database.

Overall, this project serves as a basic introduction to working with databases (SQLite3) in Python and creating a graphical user interface (Tkinter).

Screenshot:

<img width="376" alt="image" src="https://github.com/anavisomi7/jotitdown/assets/94074307/a067dccb-89f9-4f00-92f0-a4daeaef069a">



 
