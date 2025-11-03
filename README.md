# Algocoins Prototype

Prototype of the **Algocoins missions editor and shop**.  
This project demonstrates how missions (events) can be edited and how rewards can be managed in the shop.

---

## 📂 Project structure
/project-root
├── index.html        # Алгокоины: редактор миссий и магазин на Vue 2.6.14
├── modal.html        # Страница с отдельной модалкой редактирования события
└── /images           # Folder for icons
├── timing.jpg
└── (other icons for missions and shop items)
---

## 🚀 How to run

1. Clone or copy the project files.  
2. Open `index.html` in any browser — это редактор миссий и магазин.
3. При необходимости отдельно посмотреть модальное окно можно открыть `modal.html`.

No build step is required — this is a pure **HTML + CSS + JavaScript** prototype.

---

## 🎯 Features

### 1. Missions editor
- Позволяет редактировать миссии прямо в таблице (иконка, название, описание, награда).
- Каждая строка имеет кнопку «Сохранить» и локальные уведомления об успехе/ошибках.
- Валидация: количество Алгокоинов должно быть больше 0 и все поля обязательны.

### 2. Shop
- Second block below the editor.
- Displays shop rewards with columns:
  - **Code**
  - **Price (coins)**
  - **Available**
  - **Purchased**
- Includes **Import** button (UI only for now).

### 3. Modal
- Отдельная демонстрация модального окна редактирования события.
- Открывается кнопкой на `modal.html`, содержит ту же логику валидации.

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
