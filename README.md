# 🌌 ProjectFlow - Project Management System

ProjectFlow is a high-fidelity, fully responsive frontend SaaS dashboard designed to streamline team collaboration, task management, and project analytics. Built with a modern "glassmorphism" deep-space aesthetic, it features dynamic routing, persistent local storage, and complex state management to simulate a real-world enterprise application.

## 🚀 Key Features

* **Role-Based Access Control (RBAC):** Dynamic UI rendering based on user roles (Team Lead vs. Standard Member). Team Leads can add/delete tasks, remove members, and approve work. Members can only update task statuses to "Pending Review".
* **Interactive Kanban Board:** Drag-and-drop style workflow management moving tasks through *To Do*, *In Progress*, *Pending Review*, and *Done*.
* **Live Analytics Dashboard:** Utilizes `recharts` to generate dynamic Pie Charts (Status Distribution) and Bar Charts (Task Workload) that update in real-time as tasks are manipulated.
* **Persistent Data Simulation:** Uses browser `localStorage` and a seed `data.js` file to mimic a live backend, ensuring projects, tasks, and team member additions persist across page refreshes.
* **Reviewer Testing Portal:** A custom login dropdown allowing code reviewers to instantly swap between user profiles to test varying permission levels without needing multiple accounts.
* **Responsive Design:** Mobile-first architecture using Tailwind CSS, featuring a sliding hamburger menu and adaptable grid layouts.

## 🛠️ Tech Stack

* **Framework:** React.js (Vite)
* **Styling:** Tailwind CSS (v3)
* **Icons:** Lucide-React
* **Data Visualization:** Recharts
* **State Management:** React Hooks (`useState`, `useEffect`)

## 📦 Installation & Setup

To run this project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/project-flow.git](https://github.com/yourusername/project-flow.git)
   cd project-flow
