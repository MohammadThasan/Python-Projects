# ✅ Task Manager with User Authentication

A beginner-friendly Python application that lets users securely register, log in, and manage their personal tasks. Each user's tasks are stored separately, and passwords are hashed for basic security. Perfect for learning file handling, user authentication, and menu-driven programming in Python.

---

## ✨ Features

- **User Authentication**
  - Register with a unique username and password (password hashed with SHA‑256)
  - Login with existing credentials
- **Task Management** (per user)
  - ➕ Add a new task (auto‑assigned ID, default status “Pending”)
  - 📋 View all tasks with ID, description, and status
  - ✔️ Mark a task as completed
  - 🗑️ Delete a task
- **Persistent Storage**
  - User credentials saved in `users.txt`
  - Each user's tasks saved in a separate file (`<username>_tasks.txt`)
- **Interactive Menu**
  - Clean console menus for main actions and task operations
  - Loops until user chooses to log out or exit

---

## 🛠️ Technologies Used

- Python 3.x
- Standard libraries: `hashlib`, `os`

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/task-manager-auth.git
   cd task-manager-auth

2. **Run tge program**
   python task_manager.py

3. **How to use**
   1. Start the program – you'll see the main menu:
        1. Register
        2. Login
        3. Exit

2. Register a new account (username must be unique).

3. Login with your credentials.

4. Once logged in, you'll enter the task menu:
        1. Add a Task
        2. View Tasks
        3. Mark a Task as Completed
        4. Delete a Task
        5. Logout

5. Perform any task operations – all changes are saved immediately.

6. Choose Logout to return to the main menu, or Exit to quit.
   
```
task-manager-auth/
│
├── task_manager.py          # Main application code
├── users.txt                 # Stores usernames and hashed passwords
├── <username>_tasks.txt      # Task files created per user (e.g., alice_tasks.txt)
└── README.md                 # This file
```

**File formats:**

- users.txt – each line: username:hashed_password

- alice_tasks.txt – each line: task_id,description,status

Register:

```
--- Register ---
Enter username: alice
Enter password: secret
Registration successful! You can now log in.
```
**Login:**

```
--- Login ---
Username: alice
Password: secret
Welcome, alice!
```

**Adding Task:**
```
--- Add a Task ---
Enter task description: Buy groceries
Task added with ID 1.
```

**Viewing Tasks:**
```
--- Your Tasks ---
ID    Description                    Status
--------------------------------------------------
1     Buy groceries                   Pending
```

**Marking as completed:**
```
--- Mark Task as Completed ---
ID    Description                    Status
--------------------------------------------------
1     Buy groceries                   Pending
Enter the ID of the task to mark completed: 1
Task 1 marked as completed.
```


