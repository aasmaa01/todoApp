# Todo List App

A simple **To-Do List** application built using **HTML**, **CSS**, and **JavaScript**. This app allows users to add tasks, mark them as completed, and delete them. It stores tasks in **localStorage**, so they persist even after refreshing the page.

## Features

- **Add** tasks to your to-do list.
- **Mark** tasks as completed by clicking on them.
- **Delete** tasks by clicking the "×" icon next to each task.
- Tasks are stored in **localStorage**, so they persist across page reloads.

## How to Use

1. Type your task in the input box.
2. Click the **Add** button or press Enter to add the task to the list.
3. Click on a task to mark it as completed.
4. Click the **×** icon next to any task to delete it.

## Local Storage

Tasks are saved in **localStorage** so that they persist even after you refresh the page.

## Files

- `index.html`: The main HTML structure of the Todo List.
- `style.css`: The CSS file used to style the Todo List.
- `app.js`: The JavaScript file responsible for the app's functionality.

## Demo

You can view the live demo at:  
[https://aasmaa01.github.io/todoApp/](https://aasmaa01.github.io/todoApp/)

## Example Code

### HTML (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple and user-friendly To-Do List application.">
    <title>To do App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="content">
        <div class="todo-app">
            <h2>To-Do List <img src="images/icons8-a-faire-50.png" alt=""></h2>
            <div class="row">
                <input type="text" id="input-box" placeholder="add your task">
                <button onclick="addTask()">Add</button>
            </div>
            <ul id="list-container"><!--
                <li class="checked">Task</li>
                <li>Task</li>
                <li>Task</li>-->
            </ul>
        </div>
        <footer class="site-footer">
            <div class="footer-content">
              <p>&copy; 2025 To do List. All rights reserved.</p>
              <nav>
                <a href="https://github.com/aasmaa01" target="_blank" rel="noopener noreferrer">GitHub</a>
              </nav>
            </div>
          </footer>
    </div>
    <script src="app.js"></script>
</body>
</html>
