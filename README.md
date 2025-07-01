# 📝 Java Swing To-Do List App

A simple, responsive desktop **To-Do List application** built using **Java Swing**. This app allows users to add and delete tasks in a clean, resizable GUI.

---

## 📌 Features

- ✅ Add new tasks using a text field and "Add" button or **Enter key**
- 🗑️ Remove selected tasks with a single click
- 🖥️ Responsive and resizable layout
- 🧭 Scrollable task list area
- 🎯 Keyboard and mouse interaction

---

## 🚀 Getting Started

### Prerequisites

- **Java JDK** (8 or later)
- IDE like **IntelliJ IDEA** or **Eclipse** (or use a terminal)

---

### 📂 File Structure

ToDoApp/
├── ToDoApp.java # Main Java Swing source file
├── README.md # Documentation


---

### 🔧 How to Compile and Run

#### 🔸 Using Terminal

```bash
javac ToDoApp.java
java ToDoApp
```

## 🧠 Code Breakdown

Below is a detailed breakdown of how the code works:

---

### 🖼️ 1. GUI Components

```java
JFrame frame = new JFrame("To-Do List");
JTextField taskInput = new JTextField();
JList<String> taskList = new JList<>(taskListModel);
JButton addButton = new JButton("Add");
JButton deleteButton = new JButton("Delete");
```

![Screenshot 2025-07-01 213852](https://github.com/user-attachments/assets/704f5597-2b72-4e7d-a895-4e2331fe179c)
![Screenshot 2025-07-01 213842](https://github.com/user-attachments/assets/020e88e7-c34d-4489-a83c-d1f123df6b43)
![Screenshot 2025-07-01 213831](https://github.com/user-attachments/assets/86dc2110-6c1c-4067-9c4e-96e6b728489c)
![Screenshot 2025-07-01 213809](https://github.com/user-attachments/assets/8c0c6817-0ba9-47f1-b14e-7e2e6ab07884)










