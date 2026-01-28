# Team Collaboration & Project Backlog System

A lightweight, professional, and client-facing **Web Task Management System**. This tool is designed for teams to receive client requests, manage active tasks with priority sorting, and maintain a historical archive of completed work.

---

## 🚀 Core Features

* **Client-to-Team Workflow**: Clients can easily submit tasks or requirements, which are instantly categorized and prioritized.
* **Active Task Management**: 
    * **Priority Sorting**: Tasks are automatically sorted by High, Medium, and Low priorities.
    * **Multi-Select Actions**: Batch archive or batch delete multiple tasks to save time.
* **Project Backlog (Archive)**: 
    * A dedicated section for completed tasks.
    * Records **Completion Date** for easy auditing and history tracking.
    * Supports **Task Restoration** (moving items back to active status).
* **Multiple Boards**: Create separate boards for different projects or clients within the same interface.
* **Data Persistence**: Integrated with `localStorage`. Your data remains safe even after refreshing the page or closing the browser.
* **Modern UI**: Professional English interface built with Tailwind CSS for a clean, responsive experience.

---

## 🛠️ Tech Stack

* **Frontend Framework**: [Vue.js 3](https://vuejs.org/) (Composition API)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Utility-first CSS framework)
* **Storage**: Browser `localStorage` API
* **Icons**: Heroicons (SVG)

---

## 📖 How to Use

1.  **Launch**: Save the provided code as `index.html` and open it in any modern web browser.
2.  **Create a Board**: Click the **"+ New Board"** button at the top right to start a specific project or client view.
3.  **Add Tasks**: 
    * Enter the task title in the input field.
    * Select the priority level (**High / Medium / Low**).
    * Press **Enter** or click **"Add to Active"**.
4.  **Manage Tasks**:
    * Use the **Checkboxes** to select one or multiple items.
    * Click **"Complete & Archive"** to move finished work into the history section.
5.  **Review History**: Scroll down to the **Archive / History** section to see completed tasks. You can **Restore** them to active status or **Delete** them permanently.

---

## 📂 Project Structure

```text
├── index.html          # Single Page Application (Logic, Style, and Template)
└── README.md           # Documentation
```


A lightweight, professional, and client-facing **Web Task Management System**. This tool is designed for teams to receive client requests, manage active tasks with priority sorting, and maintain a historical archive of completed work.

---

## 🚀 Core Features

* **Client-to-Team Workflow**: Clients can easily submit tasks or requirements, which are instantly categorized and prioritized.
* **Active Task Management**: 
    * **Priority Sorting**: Tasks are automatically sorted by High, Medium, and Low priorities.
    * **Multi-Select Actions**: Batch archive or batch delete multiple tasks to save time.
* **Project Backlog (Archive)**: 
    * A dedicated section for completed tasks.
    * Records **Completion Date** for easy auditing and history tracking.
    * Supports **Task Restoration** (moving items back to active status).
* **Multiple Boards**: Create separate boards for different projects or clients within the same interface.
* **Data Persistence**: Integrated with `localStorage`. Your data remains safe even after refreshing the page or closing the browser.
* **Modern UI**: Professional English interface built with Tailwind CSS for a clean, responsive experience.

---

## 🛠️ Tech Stack

* **Frontend Framework**: [Vue.js 3](https://vuejs.org/) (Composition API)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Utility-first CSS framework)
* **Storage**: Browser `localStorage` API
* **Icons**: Heroicons (SVG)

---

## 📖 How to Use

1.  **Launch**: Save the provided code as `index.html` and open it in any modern web browser.
2.  **Create a Board**: Click the **"+ New Board"** button at the top right to start a specific project or client view.
3.  **Add Tasks**: 
    * Enter the task title in the input field.
    * Select the priority level (**High / Medium / Low**).
    * Press **Enter** or click **"Add to Active"**.
4.  **Manage Tasks**:
    * Use the **Checkboxes** to select one or multiple items.
    * Click **"Complete & Archive"** to move finished work into the history section.
5.  **Review History**: Scroll down to the **Archive / History** section to see completed tasks. You can **Restore** them to active status or **Delete** them permanently.

---

## 📂 Project Structure

```text
├── index.html          # Single Page Application (Logic, Style, and Template)
└── README.md           # Documentation
```
---

## 🤝 Roadmap & Future Improvements
To take this project to a production level, consider:

Integrating a backend like Firebase or Supabase for real-time team syncing.

Adding User Authentication to distinguish between Client and Admin roles.

Adding Search & Filter functionality for large backlogs.

Export to CSV: Capability to download the archive for reporting.

## License
MIT License - Feel free to use and modify for your own team or clients!
