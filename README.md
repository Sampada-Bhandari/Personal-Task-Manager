## 📝 Personal Task Manager – Java Console App

A simple yet functional **Task Manager** built in Java. You can add tasks with due dates and priorities, view your tasks, mark them as done, and delete them — all via the console!

---

### 📌 Features
- ✅ Add tasks with description, due date, and priority
- 📋 View all tasks
- ✏️ Mark tasks as done
- 🗑️ Delete tasks
- 💾 Tasks are saved to a local file (`tasks.txt`) and reloaded on startup

---

### ⚙️ Tech Stack
- Java (Core)
- File Handling (for saving/loading tasks)
- IntelliJ IDEA (recommended for development)

---

### 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/personal-task-manager.git
   ```
2. Open the project in IntelliJ IDEA (or any Java IDE).
3. Make sure all 3 files are in the `src/` folder:
   - `TaskManager.java`
   - `Task.java`
   - `Priority.java`
4. Click the green run arrow (`▶`) next to `TaskManager.java`.

---

### 🖼️ Sample Output
```
📋 Welcome to Your Personal Task Manager!

Choose an option:
1. Add Task
2. View Tasks
3. Mark Task as Done
4. Delete Task
5. Exit
```

---

### 📁 File Storage
All tasks are saved in a simple text file called `tasks.txt` in the root directory. Each task stores:
- Description
- Completion status
- Due date
- Priority (HIGH / MEDIUM / LOW)

---
