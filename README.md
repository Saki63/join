# Join – Kanban Project Management App

## 📌 Overview

**Join** is a web-based Kanban project management application that allows users to organize tasks, manage contacts, and track project progress visually.

The application provides an intuitive interface for managing tasks across different workflow stages using a Kanban board. Users can create tasks, assign contacts, add subtasks, and monitor progress through an interactive dashboard.

The project was developed as part of a web development training program and follows specific technical, UX, and clean code guidelines.

---

## 🚀 Features

### User Account & Authentication

* User registration with **name, email, and password**
* Acceptance of **privacy policy required before registration**
* Login with email and password
* **Guest login** for testing all features
* Secure logout functionality
* Protected pages redirect unauthenticated users to the login page

### Dashboard

* Overview of tasks and progress
* Shows:

  * Number of tasks with the **next deadline**
  * Task counts by status:

    * To Do
    * In Progress
    * Awaiting Feedback
    * Done
* Displays a **dynamic greeting based on time of day**

---

### Kanban Board & Task Management

* Visual Kanban board with four columns:

  * **To Do**
  * **In Progress**
  * **Awaiting Feedback**
  * **Done**
* Tasks display:

  * Category
  * Title
  * Description preview
  * Assigned contacts
  * Priority
* Click a task to open a **detailed task view**
* Add tasks via:

  * Main navigation
  * "+" icon in each column
  * Add button near search bar

#### Task Creation

Tasks can include:

* Title (required)
* Description
* Due date (required)
* Priority: **Urgent, Medium, Low** (Medium by default)
* Assigned contacts
* Category:

  * Technical Tasks
  * User Story

---

### Subtasks

* Add subtasks directly in the task form
* Press **Enter** to create a subtask
* Edit or delete subtasks
* Automatic clearing of input field
* Progress indicator on tasks with subtasks

---

### Task Editing & Deletion

* Edit tasks in the detail view
* Editable fields include:

  * Title
  * Description
  * Due date
  * Priority
  * Assigned contacts
  * Subtasks
* **Category cannot be edited**
* Tasks can be permanently deleted

---

### Drag & Drop Task Management

* Move tasks between board columns via **drag & drop**
* Visual feedback while dragging
* Columns highlight when they can receive a task
* Smooth updates without delays
* Mobile support via:

  * **Long press**
  * Alternative menu for moving tasks

---

### Search Functionality

* Search bar on the Kanban board
* Filters tasks **in real time**
* Searches in:

  * Task title
  * Description
* Shows a message when **no results are found**

---

### Contact Management

* Dedicated **Contacts page**
* Contacts sorted **alphabetically**
* Grouped by starting letter
* Displays:

  * Name
  * Email
  * Phone number

Users can:

* Add new contacts
* Edit existing contacts
* Delete contacts
* View contact details

When deleting a contact, they are **automatically removed from all assigned tasks**.

Users can also **edit their own contact information** from the contact list.

---

### Legal Pages

Join includes the following legal pages:

* **Legal Notice**
* **Privacy Policy**

Both pages are accessible from within the application and contain information about data usage and legal details.

---

## 💻 Technical Requirements

### Architecture

* **Multi-Page Application (MPA)**
* Structured file naming and project organization
* `index.html` used as the entry page

### JavaScript Standards

* One responsibility per function
* Functions max **14 lines**
* Clear and descriptive function names
* **camelCase naming convention**
* JSDoc documentation
* Maximum **400 lines of code per file**

### Code Organization

* Separate JavaScript file per page
* Shared global JavaScript file
* Separate folders for:

  * templates
  * images (`img`)

Static HTML content is **not generated via JavaScript**.

---

### Forms

* Custom form validation (no default HTML5 validation)
* Disabled buttons during loading
* New content appears immediately after creation
* Dropdown menus close automatically when clicking outside

---

### User Experience

* Interactive feedback for user actions
* Hover effects and toast messages
* Smooth transitions (75–125 ms)
* Pointer cursor on clickable elements

---

### Responsive Design

The application works on:

* Desktop devices
* Tablets
* Mobile devices (minimum **320px width**)

Additional responsiveness features:

* Vertical column layout on mobile
* No horizontal scrolling
* Content width limitation for large screens
* Landscape mode disabled by default on mobile


---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript

---

## ⚙️ Setup & Installation

1. Clone the repository

```bash
git clone https://github.com/Saki63/join.git
```

2. Open the project folder

3. Start the application by opening:

```
index.html
```

in your browser.
