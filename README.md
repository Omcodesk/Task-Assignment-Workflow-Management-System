# Task Assignment & Workflow Management System

A role-based task assignment and workflow management system built using React.js.  
The application allows administrators to assign tasks through a centralized dashboard, while employees manage and track assigned tasks via a dedicated interface.

This project focuses on frontend architecture, state management, and role-based UI flows commonly used in real-world enterprise applications.

---

## 🚀 Features

### Admin Dashboard
- Create and assign tasks to employees
- View all tasks and their current status
- Monitor task progress across the organization

### Employee Dashboard
- View assigned tasks
- Accept assigned tasks
- Mark tasks as completed or failed

### Authentication & State
- Role-based login (Admin / Employee)
- Persistent login using browser localStorage
- Centralized state management using React Context API

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5
- CSS3

### State Management
- React Context API
- React Hooks (`useState`, `useContext`, `useEffect`)

### Styling
- Tailwind CSS

### Data Persistence
- Browser localStorage

### Tooling & Development
- Vite
- Git & GitHub
- npm
- React DevTools

---

## 🧠 Architecture Overview

- Component-based frontend architecture
- Role-based access control (RBAC)
- Separation of concerns between UI, state, and logic
- Frontend-focused design with no backend dependency

---

## 📦 Installation & Setup

Clone the repository:

```bash
git clone https://github.com/Omcodesk/Task-Assignment-Workflow-Management-System.git

Install dependencies:

npm install


Start the development server:

npm run dev


Open in browser:

http://localhost:5173

## Demo Credentials

### Admin
- Email: admin@me.com
- Password: 123

### Employee
- Email: employee1@example.com
- Password: 123

> Note: This project uses browser localStorage for authentication and data persistence. Credentials are for demo purposes only.
