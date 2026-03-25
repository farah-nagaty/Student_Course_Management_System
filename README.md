# 🎓 Student Course Management System (C++)

## 📌 Overview

This project is a **Student Course Management System** implemented in C++.
It allows managing students, courses, and administrative operations through a console-based interface.

The system is designed using **Object-Oriented Programming (OOP)** concepts such as:

* Classes and objects
* Inheritance (`Person → Student`)
* Encapsulation
* Modular design using header (`.h`) and source (`.cpp`) files

---

## ⚙️ Requirements

To run this project, you need:

### 🧰 Software

* C++ Compiler (e.g., **g++** or MSVC)
* Visual Studio (recommended)

### 💻 Environment

* Windows / Linux / macOS
* C++17 or later

---

## ▶️ How to Compile and Run

### ✅ Using Visual Studio

1. Open Visual Studio
2. Click **Open a project or solution**
3. Select your project folder
4. Press:

   * **Ctrl + F5** → Run without debugging
     OR
   * Click **Local Windows Debugger**

---

### ✅ Using g++ (Command Line)

1. Open terminal in the project folder
2. Compile:

```bash
g++ Main.cpp Manager.cpp Person.cpp Student.cpp -o system
```

3. Run:

```bash
./system
```

---

## 📂 Project Structure

```
Student_Course_Management_System/
│
├── Main.cpp        # Entry point of the program
├── Manager.h/cpp   # Admin/manager operations
├── Student.h/cpp   # Student-related logic
├── Person.h/cpp    # Base class
```

---

## 🚀 Features

* Add and manage students
* Menu-driven interface
* Object-oriented design
* Separation of logic across multiple files

---

## 📝 Notes

* Make sure all `.cpp` and `.h` files are in the same directory when compiling manually
* Avoid including build folders like `Debug/` or `.vs` when uploading to GitHub

---

## 👤 Author

* Farah Nagaty

---
