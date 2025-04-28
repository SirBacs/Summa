The **SUMMA** project is a **Smart Student tracker app **

Perfect! Since it's a **mobile app** with a **tab bar** interface, here's a revised UI structure tailored for small screens, touch input, and a streamlined user experience.

---

### 📱 MOBILE UI DESIGN (Tab-Based)

You'll have a **bottom tab bar with 5 main tabs**, and use **modals, collapsible sections**, and **side drawers** to handle deeper functionality.

---

### 🔻 Bottom Tab Bar (Primary Navigation)

| Icon | Tab Name      | Function |
|------|---------------|----------|
| 📁   | Files         | View, analyze, and manage uploaded files |
| 🧩   | Topics        | View topic breakdown and roadmap |
| ✅   | Tasks         | Task management, deadlines, and priorities |
| 📝   | Notes         | Write, edit, and attach notes |
| 🔔   | Alerts        | Notifications & upcoming deadlines |

---

### 🧭 Tab Breakdown

---

#### **📁 Files Tab**
- Top: “Add File” button (FAB or + icon)
- List of uploaded files
  - Show filename, type, tags, and deadline
- Tap to view analysis:
  - Auto-topic detection
  - Summary
  - Linked notes/tasks
- Long-press: edit, delete, link to topic/task

---

#### **🧩 Topics Tab**
- Visual roadmap or vertical list view
  - Each topic shows: name, linked files, tasks, notes
- Tap to expand topic details
- “Add Topic” (top-right or floating button)
- Option to drag & reorder topics

---

#### **✅ Tasks Tab**
- Toggle: List View ↔️ Priority View
- Each task card shows:
  - Title, due date, priority tag
  - Expand to see subtasks, notes, file links
- Filters: All, Today, Upcoming, Done
- “+ Add Task” with option to link:
  - Topic, File, Note

---

#### **📝 Notes Tab**
- List of notes sorted by date/topic
- Rich text editor (bold, bullets, highlight)
- “Add Note” (+ button)
- Link note to:
  - File
  - Task
  - Topic

---

#### **🔔 Alerts Tab**
- Upcoming & overdue notifications
- Tap for detail: linked task/topic
- Settings icon to manage:
  - Notification timing (e.g., 1 day before)
  - Types (in-app, push, email)
- “Snooze” or “Mark as done”

---

### ➕ Global Floating Button (FAB)

Appears on most tabs. Opens modal:
- Add Task
- Add Note
- Add File
- Add Topic

---

### 🔧 Other UX Enhancements

- **Swipe gestures**:
  - Swipe file/task for quick actions (e.g., delete, set priority)
- **Pull-to-refresh**
- **Dark mode support**
- **Tag filter chips** at top of lists for filtering (e.g., “Urgent”, “Linked Notes”)
- **Progress indicator** for tasks/roadmap
