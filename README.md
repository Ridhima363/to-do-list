# 📝 Simple Todo List App (TO-DOIT)

A simple and clean Todo List web application to manage daily tasks easily.  
You can add, edit, delete, filter tasks, and also switch themes for a better experience.

---

## 📌 Table of Contents

1. [Introduction](#1-introduction)  
2. [Project Overview](#2-project-overview)  
3. [Getting Started](#3-getting-started)  
4. [Code Structure](#4-code-structure)  
5. [Dependencies](#5-dependencies)  
6. [Code Refactoring](#6-code-refactoring)  
7. [Deployment](#7-deployment)  
8. [Usage](#8-usage)  
9. [License](#9-license)  

---

## 1. Introduction

Welcome to the **TO-DOIT App** documentation.  
This is a simple Todo List project made to manage tasks in an easy and organized way.

This documentation explains:
- Project details  
- Code structure  
- Refactoring details  
- Deployment  
- How to use the app  

---

## 2. Project Overview

The **TO-DOIT App** is a web-based Todo application that helps users manage tasks.

### ✨ Features:
- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as Completed / Pending
- Filter tasks (All / Pending / Completed)
- Theme switcher (Light/Dark themes)

---

## 3. Getting Started

Follow these steps to run the project on your system.

### ✅ Prerequisites
Make sure you have:
- A modern browser (Chrome / Firefox / Edge)
- Internet connection (for CDN dependencies)

### 🔽 Installation Steps

1. Clone the repository:
   ```bash
  git clone <your-repo-link>

2. Go inside the project folder:
cd todo-list

3. Open index.html in your browser.
That’s it! Your app will run successfully.

4. Code Structure
The project files are organized in a clean way:
index.html → Main structure of the webpage
style.css → Styling and design
main.js → Application logic (add/edit/delete/filter/theme)
Google Fonts (Poppins) → Used for better typography

5. Dependencies
This project uses some external libraries:
Tailwind CSS → For fast and modern UI styling
DaisyUI → Pre-built UI components for Tailwind
Boxicons → Icons (edit, delete, check buttons)
Google Fonts (Poppins) → Clean and modern font
All dependencies are used through CDN.

6. Code Refactoring
This project was improved by refactoring the code to make it clean and easy to maintain.
🔥 Improvements Done:
✅ 1. Removed Monolithic Code
Earlier, the code was written in one big block.
Now, it is divided into different classes for better structure.
✅ 2. Removed Global Functions
Earlier, many functions were global.
Now, event handling is properly managed inside classes.
✅ 3. Organized HTML Manipulation
Earlier, HTML updates were happening in many places.
Now, UI updates are handled in a single place (UIManager class).
✅ 4. Added Error Handling
Now the app handles invalid inputs properly and shows alerts/messages.

📌 SOLID Principles Followed
SRP (Single Responsibility Principle):
Each class has its own responsibility (UI, logic, theme etc.)
OCP (Open/Closed Principle):
Easy to add new features without changing existing code.
DIP (Dependency Inversion Principle):
Reduced coupling between classes for flexibility.


📌 Design Patterns Used
.Observer Pattern:
For handling UI events properly.
.Strategy Pattern:
Used for formatting todo items in a consistent way.
.Singleton Pattern:
Used in ThemeSwitcher to manage theme in one place.

7.Usage
➕ Add a Task
.Type the task in input box
.Select date (optional)
.Press Enter or click "+" button
✏️ Edit a Task
.Click edit button
.Update the task
.Click check button to save
✅ Mark Task Completed
.Click check button to toggle completed/pending status
🗑 Delete a Task
.Click trash icon to delete the task
🔍 Filter Tasks
.Select filter option:
.All
.Pending
.Completed
❌ Clear All Tasks
.Click "Delete All" button to remove all tasks
🎨 Theme Switch
.Click palette icon
.Select any theme

👨‍💻 Author
Developed by: Ridhima Agarwal
