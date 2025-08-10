Text-Based Notes Manager
📌 Overview
The Text-Based Notes Manager is a simple Java console application that allows users to:

Add notes to a text file

View all saved notes from the file

It uses:

FileWriter for writing notes (append mode)

FileReader and BufferedReader for reading notes

⚙️ How It Works
When you add a note, it is appended to notes.txt (created automatically if not present).

When you view notes, the program reads each line from notes.txt and displays it.

The application keeps running until you choose Exit.

Choose from the menu:

1 → Add a new note

2 → View all saved notes

3 → Exit

📂 File Details
notes.txt – Stores all notes (one note per line).

NotesManager.java – Main program file.

📝 Example
pgsql
Copy
Edit
=== Text-Based Notes Manager ===

1. Add a note
2. View all notes
3. Exit
Enter your choice: 1
Enter your note: Buy groceries
Note saved successfully!
💡 Future Improvements
Add delete note option
