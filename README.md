## React Task Manager
A simple, modern, and intuitive Task Management application built with React and styled with Tailwind CSS. This project allows users to organize their day by adding, viewing, and managing tasks with data persistence.

### Features

1. Add Task: Create new tasks with a title and a description.

2. List Task: View all current tasks in a clean list format.

3. Mark as Completed: Interactive toggle to mark tasks as done (visual feedback with strikethrough).

4. Delete Tasks: Remove unwanted tasks from the list.

5. Task Details: Navigate to a dedicated page to view full details of a specific task.

### Technologies Used

- React: Library for building the user interface.

- Tailwind CSS: Utility-first CSS framework for styling.

- Lucide React: For beautiful, consistent icons (Trash, Check, Chevron).

### Project Structure
Based on the core logic, the project structure is organized as follows:

```
src/
├── components/
│   ├── AddTask.jsx       # Form to input new tasks
│   ├── Button.jsx        # Reusable button component (Inferred)
│   ├── Input.jsx         # Reusable input field component (Inferred)
│   ├── Tasks.jsx         # List component that renders individual tasks
│   └── Title.jsx         # Header/Title component (Inferred)
├── pages/
│   └── TaskPage.jsx      # Page to display task details (Inferred from routing)
├── App.jsx               # Main application logic and state management
├── main.jsx              # Entry point (Router setup)
└── index.css             # Tailwind imports and global styles
```

### Installation & Setup
To run this project locally, follow these steps:

Clone the repository:
```Bash
git clone https://github.com/BLuiz/task-manager-react.git
```

Navigate to the project directory:
```Bash
cd task-manager-react
```

Install dependencies:
```Bash
npm install
```

Run the development server:
```Bash
npm run dev
```

_Open your browser: The project usually runs at http://localhost:5173 (or the port shown in your terminal)._

---
Developed for educational purposes to demonstrate React hooks, props, and routing. Inspired in the following videocourse: [Curso de React para Completos Iniciantes [2024]](https://youtu.be/2RWsLmu8yVc?si=eDjyP25lZst17Qsj)