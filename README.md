# 📝 To-Do App (Vanilla JavaScript)

A simple and interactive To-Do application built using **HTML, CSS, and Vanilla JavaScript**.  
This project focuses on understanding **DOM manipulation, state management, and UI rendering** without using any frameworks.

---

## 🚀 Features

- ➕ Add new tasks  
- ❌ Delete tasks  
- ✏️ Edit existing tasks  
- ✅ Mark tasks as completed (checkbox with strike-through)  
- 🧠 State-driven UI using a `todos` array  
- 🔄 Automatic UI updates using a custom `render()` function  
- 🚫 Prevents empty tasks from being added  

---

## 🧠 Key Concepts Learned

- DOM Manipulation (`createElement`, `appendChild`)
- Event Handling (`addEventListener`)
- State Management using arrays
- Re-rendering UI on state change
- Input validation using `.trim()`
- Separation of logic (state) and UI (rendering)

---

## 🏗️ Project Structure
📁 project-folder
├── index.html
├── styles.css
└── script.js


---

## ⚙️ How It Works

1. User enters a task
2. Task is stored in the `todos` array (state)
3. `render()` function updates the UI
4. Any action (add/edit/delete/toggle) updates state → triggers re-render

---

## 💡 Core Idea

> Instead of directly manipulating the DOM, the UI is rebuilt from the current state every time it changes.

This is similar to how modern frameworks like React work internally.

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- JavaScript (ES6)

---

## 🚀 Future Improvements

- 💾 Save tasks using localStorage  
- 🔍 Filter tasks (All / Completed / Active)  
- 🎨 Improve UI/UX with animations  
- 🌙 Dark/Light mode toggle  
- ⚛️ Convert to React  

---

## 📚 Learning Journey

This project is part of my **#LearnInPublic** journey where I am building real projects to strengthen my frontend fundamentals.

---

## 🤝 Contributing

Feel free to fork this repo and improve it!

---

⭐ If you like this project, consider giving it a star!
