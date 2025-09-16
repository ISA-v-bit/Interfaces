# Algocoins Prototype

Prototype of the **Algocoins missions editor and shop**.  
This project demonstrates how missions (events) can be edited and how rewards can be managed in the shop.

---

## 📂 Project structure
/project-root
├── index.html        # Entry point with two buttons: “Open modal” and “Open algocoins in branch”
├── modal.html        # Standalone page with event modal (validation, error/success alerts)
├── branch.html       # Missions editor + shop prototype
└── /images           # Folder for icons
├── timing.jpg
└── (other icons for missions and shop items)
---

## 🚀 How to run

1. Clone or copy the project files.  
2. Open `index.html` in any browser.  
3. Use the navigation:
   - **Open modal** → opens the event editing modal (validation included).
   - **Open algocoins in branch** → opens the missions editor with integrated shop section.

No build step is required — this is a pure **HTML + CSS + JavaScript** prototype.

---

## 🎯 Features

### 1. Missions editor
- Displays missions in a table (icon, title, description, algocoins, status).
- All fields are **read-only** in the table.
- Editing is possible only via modal window:
  - Upload/change icon.
  - Edit title, description, algocoins.
  - Change status.
  - Validation: algocoins **must be greater than 0**.
  - Alerts: red error and green success messages.

### 2. Shop
- Second block below the editor.
- Displays shop rewards with columns:
  - **Code**
  - **Price (coins)**
  - **Available**
  - **Purchased**
- Includes **Import** button (UI only for now).

### 3. Modal
- Consistent design with error/success alerts.
- Opens when clicking on ✏️ (edit) button.
- Closes by **Cancel**, clicking outside modal, or after saving successfully.

---

## 🖼️ Assets
- All icons should be stored in `/images/` folder.
- Example: `timing.jpg` used for a mission icon.

---

## 📌 Notes
- This is a **UI prototype** (no backend integration yet).
- All data (missions and shop items) is static and can be extended manually.
- The project is structured for easy extension — you can add new missions, shop items, or connect a backend in the future.

---

## ✅ Next steps (optional improvements)
- Add dynamic row creation for new missions.
- Enable editing/deleting shop items.
- Connect with backend API for persistent storage.
- Animate alerts (fade in/out).

---
