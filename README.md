# React Learning Journey

A simple React learning repository that includes installation steps, introduction to hooks, and a basic Todo application — all built using Vite.

---

## 🚀 Installation & Setup

### 📦 Prerequisites

Before starting, make sure you have the following installed:

```bash
node --version     # Should be 14.0 or higher
npm --version      # Should be 6.0 or higher
```

### 🛠 Recommended VS Code Extensions

To enhance your React development experience in VS Code, consider installing the following extensions:

1. **ES7+ React/Redux/React-Native snippets** - Provides useful code snippets
2. **Material Icon Theme** - Beautiful file icons for better project navigation

### ⚡ Getting Started

Follow these steps to set up the project:

```bash
# Scaffold a new project using Vite
npm create vite@latest react-todo-application -- --template react

# Move into the project directory
cd react-todo-application

# Install dependencies
npm install

# Start the development server
npm run dev
```

Once the development server starts, you'll see:
```
➜  Local:   http://localhost:5173/
```

---



**✅ Concept: Components in React**

A **component** is a reusable UI block. We use components to separate different parts of the UI, making our code more organized and maintainable.

**🧱 Components used in this project:**

- `Sidebar.jsx` – Navigation section (Today, Upcoming, Sticky Notes)
- `TaskItem.jsx` – Displays a single task
- `AddTaskModal.jsx` – A popup modal to add a new task
- `AddProjectModal.jsx` – A popup modal to add a new project

### 🔄 Chapter 2: Managing State with useState

**✅ Concept: useState Hook**

`useState` allows components to hold data that changes over time. It's React's way of making components dynamic and interactive.

**🧠 Used in this project to:**

- Store the list of projects
- Manage the state of modals (Add Project, Add Task)
- Track selected project and its tasks
- Handle form inputs and user interactions

### 📨 Passing Data with Props

**✅ Concept: Props = Component Inputs**

Props allow us to pass data or functions from a parent component to a child component, enabling communication between components.

**🔗 Examples in this app:**

- `projects` passed to `Sidebar` component
- `addTaskToProject` function passed to `AddTaskModal`
- `tasks` array passed to `TaskList` component

### 🎛️ Conditional Rendering

**✅ Concept: Show UI only when needed**

We use conditional rendering to show or hide components based on certain conditions, making our app more dynamic and user-friendly.

**Examples in this project:**
- Show/hide modals based on user actions
- Display task lists only when a project is selected
- Show empty state when no tasks exist

---

