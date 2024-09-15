# To Do List App

## Overview

The To Do List App is a user-friendly web application designed to help you efficiently create and manage your tasks. With a sleek and intuitive interface, you can easily track your to-dos, mark them as completed, and keep your lists organized.

## Key Features

* **Add Tasks**: Enter tasks into the input box and click the "Add Task" button to add them to your list.
* **Task Management**: View your tasks in a clean, organized list format.
* **Mark as Completed**: Click on a task to mark it as completed, visually distinguishing it from incomplete tasks.
* **Delete Tasks**: Remove tasks from your list by clicking the "×" icon next to each task.
* **Persistent Storage**: Your tasks are saved to local storage, so they remain available even if you refresh the page.

## Files Overview

### `index.html`

* **Purpose**: The core HTML structure of the application.
* **Contents**:
  * Header with title and stylesheet link.
  * Input area with a heading, input box, and "Add Task" button.
  * An unordered list to display tasks.
  * Link to the external JavaScript file (`app.js`) for interactive functionality.

### `style.css`

* **Purpose**: Styles the application to provide an aesthetically pleasing user experience.
* **Features**:
  * Global styles including box-sizing, padding, margin, and font-family.
  * Custom styles for the todo-app container, heading, input box, button, and task list.
  * Distinct styles for completed and incomplete tasks for clear visual differentiation.

### `app.js`

* **Purpose**: Manages the interactive features of the application.
* **Functions**:
  * `addTask()`: Adds new tasks to the list and updates local storage.
  * `savedata()`: Saves the current list state to local storage.
  * `showdata()`: Retrieves and displays saved tasks from local storage.

## Usage Instructions

1. Open `index.html` in a web browser to start using the app.
2. Use the input box and "Add Task" button to create new tasks.
3. Click on a task to mark it as completed.
4. Click the "×" icon next to a task to delete it.

## Future Enhancements

* **Task Editing**: Allow users to edit existing tasks.
* **Task Reordering**: Implement functionality to reorder tasks.
* **Enhanced Features**: Add more features to improve user experience, such as task categories or due dates.
