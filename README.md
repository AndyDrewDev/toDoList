# ToDo List

A simple and convenient application for managing daily tasks, created using HTML, CSS, and JavaScript.

## Functionality

- Adding new tasks
- Marking tasks as completed
- Deleting tasks
- Automatic saving of tasks in the browser's local storage
- Responsive design (works on various devices)

## Technologies

- HTML5
- CSS3
- JavaScript (ES6+)
- Local Storage API
- Bootstrap 4 (basic design)

## Usage

1. Enter the task text in the "Task text" field
2. Click the "Add" button or press Enter
3. To mark a task as completed, click the button with a checkmark
4. To delete a task, click the button with an X

## Project Structure

```
.
├── css/                # Styles
│   └── main.css        # Main application styles
├── img/                # Images
│   ├── leaf.svg        # Icon for empty list
│   ├── tick.svg        # Icon for completing a task
│   └── cross.svg       # Icon for deleting a task
├── js/                 # JavaScript files
│   └── main.js         # Main application logic
├── index.html          # Main page
└── README.md           # This file
```

## Features

- Tasks are stored in the browser's local storage, so they will be available even after closing the browser
- Minimalistic and user-friendly interface
- No server-side requirements - works completely on the client side
