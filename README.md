# vityarthi_project_todo
📝 My Python Project - Simple To-Do List Application

Overview

This is a simple, desktop-based To-Do List application built using Python and the standard tkinter library. It provides a clean graphical user interface (GUI) for users to manage their daily tasks. Tasks are saved automatically to a local file (tasks.txt) for data persistence, meaning your tasks will remain even after you close and reopen the application.

✨ Features

Add Tasks: Quickly add new tasks via an input field and dedicated "Add" button.

Delete Tasks: Remove selected tasks from the list.

Clear All: Delete all tasks in the list with a confirmation prompt.

Data Persistence: Automatically saves and loads tasks from a tasks.txt file in the same directory as the script.

Scrollable View: Includes a scrollbar for easy navigation of long task lists.

User Feedback: Provides pop-up warnings for input errors (e.g., trying to add an empty task) or selection errors (e.g., trying to delete without selection).

🛠️ Prerequisites

To run this application, you only need Python installed on your system.

Python 3.x

The tkinter module is included by default with most Python distributions, so no further installations should be necessary.

🚀 Installation and Setup

Clone the Repository (if applicable) or Save the File:
Save the provided Python code as a file named todo_app.py (or similar).

Run the Application:
Open your terminal or command prompt, navigate to the directory where you saved the file, and execute the script:

python todo_app.py


🖥️ Usage

Adding a Task:

Type your task description into the text entry box.

Click the Add button. The task will appear at the bottom of the list.

Deleting a Task:

Click on a task in the list to select it.

Click the Delete Task button.

Clearing All Tasks:

Click the Clear All button. You will be prompted with a confirmation dialog before all tasks are permanently removed.

Data Storage

The application creates and manages a file named tasks.txt in the same directory. This plain text file stores one task per line. If you need to manually edit or back up your tasks, you can interact directly with this file.

🤝 Contributing

If you wish to improve this simple application, feel free to fork the repository and submit pull requests. Any suggestions for improving the UI, adding features (like marking tasks as complete), or refining the code logic are welcome!