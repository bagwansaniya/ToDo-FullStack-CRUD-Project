# ✅ Full Stack To-Do List Application

A **modern, responsive To-Do List app** built with the Full Stack approach, featuring secure user authentication and intuitive task management. This project showcases practical implementation of RESTful APIs, JWT-based authentication, MySQL integration, and clean UI with Angular (or any frontend of your choice).

---

## 🚀 Features

### 🔐 Authentication
- **Register** new users securely with bcrypt hashing.
- **Login** using email and password.
- **JWT Token**-based user authentication for secure routes.
- **Protected profile route** for verifying login sessions.

### 📋 Task Management (CRUD)
- **Add** new tasks.
- **View** all tasks (sorted by position).
- **Update** task content.
- **Delete** existing tasks.
- **Mark as complete/incomplete**.
- **Search** tasks by name.
- **Reorder** tasks (drag-drop supported on frontend).

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | Angular (Recommended) |
| **Backend** | Node.js, Express |
| **Database** | MySQL |
| **Authentication** | JWT + bcryptjs |
| **Testing** | Mocha, Chai (for backend) |
| **UI** | Responsive CSS + SLDS or Angular Material |
| **Version Control** | GitLab (with proper commit history) |

---

## 🔧 API Endpoints

### 👥 Auth Routes
| Method | Endpoint        | Description             |
|--------|-----------------|-------------------------|
| POST   | `/register`     | Register new user       |
| POST   | `/login`        | Login existing user     |
| POST   | `/profile`      | Verify JWT token (protected) |

### 📝 Task Routes
| Method | Endpoint             | Description                      |
|--------|----------------------|----------------------------------|
| GET    | `/tasks`             | Get all tasks                    |
| POST   | `/tasks`             | Create a new task                |
| PUT    | `/tasks/:id`         | Update a task by ID              |
| DELETE | `/tasks/:id`         | Delete a task by ID              |
| PUT    | `/tasks/completed/:id` | Toggle task completion        |
| GET    | `/tasks/search/:task` | Search task by keyword         |
| PUT    | `/tasks/reorder`     | Update order/position of tasks  |

---
