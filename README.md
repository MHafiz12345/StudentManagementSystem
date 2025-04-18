# 📚 Student Management System (SMS 2023)

A simple console-based Student Management System written in C++ for maintaining student data. It uses Binary Search Trees (BST) for organizing student records and a linked list for sorting operations. Designed with authentication, clean terminal output, and user interactivity in mind.

---

![Main Menu - Sign In/Register Screen](https://github.com/user-attachments/assets/8e13b9c7-78f7-4ec3-8077-d79e5df2baf8)

*Main Menu - Sign In/Register Screen*

---

## 🧠 Features

- 🔐 **User Authentication**  
  Supports basic sign-in and registration system.
- 📋 **Add, Edit, Search, Display, and Remove Students**  
  Students are stored in a BST for fast searching by ID.
- 📊 **Tabular Output**  
  Student details are shown in neat, column-aligned tables.
- 🔁 **Sorting by ID**  
  Supports sorting using a singly linked list and bubble sort.
- 🧼 **Memory Management**  
  Clean removal of all student data on exit.

---

## 🚦 How It Works

1. Upon launching the program, users can **register** or **sign in**.
2. Once signed in, users are presented with a menu:
   - Add new students
   - Edit existing student records
   - Search students by ID
   - Display all students in table format
   - Remove students by ID
3. Data is stored in a binary search tree and temporarily mirrored in a linked list for sorting purposes.

---

## ▶️ Build & Run

### ✅ Requirements
- C++ Compiler (e.g., `g++`)
- Terminal or Command Prompt

### 🔧 Build Instructions
```bash
git clone https://github.com/yourusername/student-management-system.git
cd student-management-system
g++ -o sms main.cpp Student.cpp StudentManagementSystem.cpp User.cpp
```

### ▶️ Run
```bash
./sms
```

## 🧪 Functional Menu Example

```
1. Add Student
2. Edit Student
3. Search Student
4. Display Student
5. Remove Student
6. Sign Out and Exit
```

![Functional Menu Screen](https://github.com/user-attachments/assets/a060a43e-086f-480b-98ac-9e668ec7839f)

## 📂 Folder Structure

```
├── main.cpp
├── Student.cpp
├── Student.h
├── StudentManagementSystem.cpp
├── StudentManagementSystem.h
├── User.cpp
├── User.h
└── assets/
    └── sms_home.png  
```

## 🛠️ Tech Stack

- **Language**: C++
- **Concepts Used**: 
  - Object-Oriented Programming
  - Binary Search Trees
  - Linked Lists
  - User Authentication
  - Formatted Console I/O
