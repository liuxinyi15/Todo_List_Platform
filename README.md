# TO DO CREATOR PRO 🚀

**TO DO CREATOR PRO** is an intelligent, dynamic project management tool designed for teams and individuals. More than just a simple to-do list, it is a smart workspace that automatically adapts to your existing document structures and workflows.

---

## 🌟 Key Features

* **Adaptive CSV Engine**: 
    * **Auto-Detection**: Upload any CSV file, and the system instantly recognizes the structure to generate matching table headers.
    * **Dynamic Mapping**: Whether your file has 5 columns or 15, the interface refines itself to display your data perfectly.
* **Full Inline Editing**: 
    * No more pop-ups! Click directly on any cell to edit text or values. Changes are saved instantly as you type.
* **Advanced Dynamic Sorting**: 
    * **Custom Sort Basis**: Choose any column (Task, Owner, Sprint, etc.) as the sorting anchor.
    * **Smart Numeric Logic**: Automatically detects numbers (like Effort/Story Points) to sort numerically (e.g., 2 comes before 10) rather than alphabetically.
* **Dual-State Management (Active & Archive)**:
    * **Active View**: Stay focused on current high-priority tasks.
    * **History / Archive**: Completed tasks move to a dedicated archive section where they can be restored or permanently deleted.
* **Robust Data Handling**:
    * **Fixed Parser**: A state-machine-based CSV parser that handles complex cells containing commas and quotes without breaking the layout.
    * **One-Click Export**: Export your updated workspace back to a standard CSV file for use in Excel or Google Sheets.
* **Zero-Loss Persistence**: 
    * All boards, tasks, and sorting preferences are saved via Browser `localStorage`. Your data stays safe even after refreshing or closing the browser.

---

## 🛠️ Tech Stack

* **Framework**: [Vue.js 3](https://vuejs.org/) (Composition API)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Responsive Utility-First Design)
* **Parsing**: Custom State-Machine CSV Parser
* **Storage**: Browser Web Storage API

---

## 📖 How to Use

### 1. Launch
Simply open `index.html` in any modern web browser. No installation or server required.

### 2. Manage Boards
* **Create**: Click **"+ New Board"** to start a new project.
* **Rename**: Double-click any Board tab to enter rename mode. Press **Enter** to save.

### 3. Handling Data
* **Import**: Click **"Choose CSV"** in the sidebar to upload your project data.
* **Sort**: Use the **"Sort By"** dropdown above the table to change the order. Toggle the arrow to switch between Ascending and Descending.
* **Edit**: Click any cell to modify the content.

### 4. Task Lifecycle
* **Done**: Click the green "Done" button to move a task to the **Archive**.
* **Restore**: Find archived tasks in the bottom section and click "Restore" to move them back to the active list.
* **Delete**: Use the **Red Trash Icon** to permanently remove a task.

---

## 📂 CSV Formatting Tips

The system is column-agnostic, but to enable **Smart Color Badges**, ensure your CSV includes headers with these keywords:
* `Priority`
* `Urgency`
* `Effort`
* `Status`

The UI automatically renders `3 / High / Urgent` as **Red**, `2 / Medium` as **Orange**, and `1 / Low` as **Blue**.

---

## 📄 License
Open-sourced under the **MIT License**. Feel free to customize and use it for your professional needs!