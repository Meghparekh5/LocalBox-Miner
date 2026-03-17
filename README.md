# 📦 LocalBox Miner

## 📝 Project Description

LocalBox Miner is a simple React-based offline data management application. It helps in understanding core React concepts like state management, component structure, CRUD operations, and localStorage integration.

This project allows users to add, edit, delete, and view records in a table. All data is stored locally in the browser using localStorage, so no backend or API is required.

---

## 🎯 Features

* Add new records
* Edit existing records
* Delete individual records
* Clear all records
* Data stored in browser (localStorage)
* Instant UI updates using React state

---

## 🧩 Components Used

* **RecordForm**

  * Handles input fields
  * Used for adding and updating records
  * Includes basic validation

* **RecordList**

  * Displays all records in table format
  * Handles empty state (No Records Found)

* **RecordRow**

  * Renders each record row
  * Contains Edit and Delete buttons

---

## ⚙️ Concepts Covered

* React Hooks (useState, useEffect)
* Controlled Components
* Props and Component Communication
* Event Handling (onChange, onSubmit, onClick)
* Conditional Rendering
* Local Storage (CRUD operations)

---

## 📊 Application Flow

1. User enters data in the form
2. Data is added to state
3. State updates localStorage
4. Table re-renders automatically
5. User can edit or delete records
6. All changes sync with localStorage

---

## 💻 Project Structure


src/
 ├── components/
 │   ├── RecordForm.jsx
 │   ├── RecordList.jsx
 │   ├── RecordRow.jsx
 ├── App.jsx
 ├── main.jsx
 ├── App.css

---


## ⚠️ Requirements

* Must use React (no backend)
* Must use localStorage
* Data persists until manually cleared
* Clean component-based structure

---

## 🎓 Learning Outcome

This project helps in building a strong foundation in React by implementing real-world features like form handling, state updates, and persistent storage without using any backend.

---
<img width="1903" height="914" alt="Screenshot 2026-03-17 122002" src="https://github.com/user-attachments/assets/e61bcd5d-aa34-4f74-9a88-c61a16f0aac3" />

