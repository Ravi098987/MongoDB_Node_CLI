# 📘 Student Management CLI App (Node.js + MongoDB)

A simple Command-Line Interface (CLI) application for managing student records using **Node.js**, **MongoDB**, and **Mongoose**.

---

## 🔧 Features

- ➕ Insert a new student
- 📋 View all students
- ✏️ Update an existing student's details
- 🗑️ Delete a student by ID
- ❌ Exit the app safely

---

## 🗂️ Tech Stack

- Node.js
- MongoDB (local instance)
- Mongoose ODM
- Readline module for CLI interface

---

## 📦 Installation

1. **Clone this repository**

```bash
git clone https://github.com/your-username/student-cli-app.git
cd student-cli-app
Install dependencies

bash
Copy
Edit
npm install
Start MongoDB

Make sure MongoDB is running locally on your system. If not, start the MongoDB service:

bash
Copy
Edit
# For Linux/macOS
sudo service mongod start

# For Windows (via MongoDB Compass or terminal)
net start MongoDB
Default MongoDB URI: mongodb://localhost:27017/toPushGitdb

🚀 Run the Application
bash
Copy
Edit
node index.js
You'll see a CLI menu like this:

mathematica
Copy
Edit
📘 Student Management Menu
1. ➕ Insert Student
2. 📋 View All Students
3. ✏️ Update Student
4. 🗑️ Delete Student
5. ❌ Exit
📂 Project Structure
bash
Copy
Edit
student-cli-app/
├── index.js         # Main CLI application
├── package.json     # NPM configuration
└── README.md        # Project documentation