# TaskNest
# Simple Todo List App (React + Python)

This is a **basic Todo List app** built using **React for the frontend** and **Python (http.server)** for the backend. It allows users to:

- ✅ Add tasks
- 📋 View the list of tasks
- ✔️ Mark tasks as completed
- 🗑️ Delete tasks

---

##  Features

- **React Frontend**: Provides an interactive user interface.
- **Python Backend**: Uses Python's built-in `http.server`—no external libraries or databases required.
- **In-Memory Storage**: Todos are stored temporarily in memory.

---

##  Project Structure
project-folder/
├── backend/
│ └── app.py
├── frontend/
│ ├── src/
│ │ ├── App.js
│ │ └── App.css
│ └── package.json


---

## ⚙️ How to Run the App

### 1️⃣ Start the Backend Server

Open a terminal and:

```bash
cd backend      # Navigate to the folder with app.py
python app.py   # Start the Python HTTP server (runs on port 5000)

### 2️⃣ Start the Frontend (React)
cd frontend     # Navigate to the folder with src/App.js and App.css
npm install     # Run this only once to install dependencies
npm start       # Start the React app


