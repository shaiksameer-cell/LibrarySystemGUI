📚 Library System GUI

A simple Java Swing desktop application that simulates a basic Library Management System, allowing users to issue, return, and unissue books interactively through a graphical interface.

🕹️ Features

📖 View all available books in a clean list view

🟢 Issue a book (mark as issued)

🔵 Return / Unissue a book (mark as available again)

🔄 Refresh the list to view current status

🪶 Minimal, lightweight, and written in pure Java (no external dependencies)

🧠 How It Works

The application maintains a list of Book objects, each with:

A title

An issued status flag (true/false)

The GUI provides buttons to:

Issue → Marks a book as issued

Return / Unissue → Marks it as returned

Refresh → Updates the book list display

When an action is taken, the system shows a pop-up message confirming the result.

💻 Requirements

Java 17 or later

Any IDE or terminal that supports compiling and running Java code
