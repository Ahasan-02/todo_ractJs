<h3>📝 Todo List App (React + LocalStorage)</h3>

This is a simple and clean To-Do List application built using React.
It allows users to add tasks, mark them as complete, delete tasks, and automatically saves all todos in localStorage so the data remains even after refreshing the page.

<h3>🚀 Features</h3>

➕ Add new tasks </br>
✔️ Mark tasks as complete / incomplete </br>
❌ Delete tasks </br>
💾 Auto-save todos in browser localStorage </br>
🎨 Minimal and responsive UI </br>
⚡ Fast rendering using reusable components </br>

<h3>🛠️ Tech Stack</h3>

React.js </br>
JavaScript </br>
Tailwind CSS </br>
LocalStorage API </br>

<h3>📂 Project Structure</h3>

/src </br>
    ├── components </br>
    │    ├── Todo.jsx </br>
    │    ├── TodoItem.jsx </br>
    │├── assets </br>
    │    └── todo_icon.png </br>
    │ </br>
    ├── App.jsx </br>
    ├── index.js </br>
    └── index.css </br>


<h3>🧠 How It Works</h3>

1. Add Todo </br>
The user types a task → clicks ADD → a new todo object is created and added to the todoList state.

2. Toggle Todo </br>
When the user clicks the tick button, the isComplete property flips between true and false.

3. Delete Todo </br>
Removes the item from the todoList using .filter().

4. Save to LocalStorage </br>
Using useEffect, todoList is saved automatically whenever it changes.
