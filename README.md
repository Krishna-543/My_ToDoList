# ✅ To-Do List App — Organize Your Day with Elegance & Efficiency

> A sleek, responsive full-stack To-Do List application built with **React**, **Node.js**, and **MySQL**. Track your tasks, stay productive, and enjoy a seamless user experience with a beautiful UI and powerful backend integration.

---

## 🌟 Features

🔸 **Add Tasks Easily** – Capture tasks with a smooth input system.  
🔸 **View Tasks Instantly** – See your entire task list load instantly on the dashboard.  
🔸 **Delete with a Click** – Remove completed or unnecessary tasks with a single icon tap.  
🔸 **Edit Functionality** – *(Coming Soon)* – Inline task editing to enhance productivity.  
🔸 **Attractive UI** – Fully styled with modern CSS, gradients, and subtle animations.  
🔸 **Real-Time MySQL Integration** – All tasks are stored and retrieved from a live database.

---

## 🛠️ Tech Stack

| Frontend     | Backend     | Database   |
|--------------|-------------|------------|
| React JS     | Node.js     | MySQL      |
| Bootstrap 5  | Express.js  | SQL Query  |
| HTML/CSS     | CORS        |            |

---


## 🚀 Getting Started

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/Krishna-543/To_Do_List.git
cd To_Do_List
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

🔌 **Database Setup:**
- Use MySQL Workbench or XAMPP
- Create a database named `todo`
- Run this query to create the table:

```sql
CREATE TABLE task (
  TaskID INT AUTO_INCREMENT PRIMARY KEY,
  Task VARCHAR(255) NOT NULL
);
```

🟢 Start Backend Server:

```bash
node index.js
```

### 3️⃣ Frontend Setup

```bash
cd ../frontend/react-todo
npm install
npm start
```

App will run at: `http://localhost:3000`  
API server will be on: `http://localhost:5000`

---

## 💡 Project Structure

```
To_Do_List/
├── backend/
│   ├── index.js
│   ├── db.sql
│   ├── package.json
├── frontend/
│   └── react-todo/
│       ├── App.js
│       ├── App.css
│       ├── index.js
│       └── ...
```

---

## 🎯 Future Enhancements

- ✅ **Task Editing Functionality**
- 🎨 **Dark Mode Support**
- 📱 **Responsive Mobile Design**
- 🗓️ **Due Date & Reminder Alerts**
- 🧠 **User Authentication (Login/Register)**

---

## 🙌 Acknowledgements

Special thanks to:
- Open-source community
- React & Node.js contributors
- You, the user, for trying this out 💖

---

## 🧑‍💻 Author
🔗 [GitHub Profile](https://github.com/Krishna-543)

---
