# Flask Todo List Application

A simple web-based todo list application built with Flask and SQLite.

## Features

- Create new tasks with priority levels (Low, Medium, High)
- View all tasks sorted by priority
- Delete completed tasks
- Clean and responsive user interface
- SQLite database for data persistence

## Project Structure

```
├── static/              # Static assets
│   ├── images/         # Image assets
│   └── style.css       # CSS styling
├── templates/          # HTML templates
│   ├── index.html     # Home page
│   └── tasks.html     # Task management page
└── app.py             # Main Flask application
```

## Setup

1. Install Flask. Flask is a web framework for Python. `pip install flask`
2. Run the application by typing `python3 app.py` in the terminal.

You can make changes to the app and they will automatically be reflected in the running version. To stop the app running press `CTRL-C`


## Usage

1. Navigate to the home page
2. Click "Go to Task Manager" to manage your tasks
3. Add new tasks by entering task description and selecting priority
4. Delete tasks by clicking the "Delete" button

## Technologies Used

- Flask (Python web framework)
- SQLite (Database)
- HTML/CSS (Frontend)
