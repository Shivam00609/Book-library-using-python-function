# Book-library-using-python-function
📚 Library System (Python)

This is a simple command-line library system built using Python.
It allows users to choose between continuing or exiting, and if they continue, they can select a book from a predefined list to view its description.

🧠 Features

Displays a welcome message and main menu options.

Lets the user:

Continue to browse books.

Exit the program.

Offers a selection of 5 popular books, each with a short description:

To Kill a Mockingbird by Harper Lee

1984 by George Orwell

The Alchemist by Paulo Coelho

The Great Gatsby by F. Scott Fitzgerald

Harry Potter and the Sorcerer’s Stone by J.K. Rowling

Handles invalid inputs gracefully.

🧩 How It Works

The program starts by greeting the user.

The run() function is called, prompting the user to:

Press 1 to continue, or

Press 2 to exit.

If the user chooses to continue, the book() function runs, which:

Displays a numbered list of books.

Accepts user input for a book number.

Prints the book’s title and description.

Invalid inputs return an error message.

▶️ Usage
Run the Program
python "function in python for library.py"

Example Output
Welcome
press 1 For continue
press 2 For exit
Enter any no. as per given above : 1
press 1 for book1: To Kill a Mockingbird by Harper Lee
press 2 for book2: 1984 by George Orwell
press 3 for book3: The Alchemist by Paulo Coelho
press 4 for book4: The Great Gatsby by F. Scott Fitzgerald
press 5 for book5: Harry Potter and the Sorcerer’s Stone by J.K. Rowling
Enter a book for as shown above: 2
1984 by George Orwell ->
-------- Description --------
A dystopian novel about a totalitarian regime that controls truth, history, and thought...

⚙️ Requirements

Python 3.6+

No external libraries are required.

🧾 Notes

The program uses input() for user interaction — best run directly in a terminal.

You can modify the book() function to add or remove books.

The initial commented section (User_input()) appears unused and can be safely removed.

🧑‍💻 Author

Created as a simple Python demonstration for conditional logic and user input handling.
