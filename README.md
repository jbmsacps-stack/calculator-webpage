# calculator-webpage

# 📱 Calculator Web App

<p align="center">
  <b>Mobile-inspired calculator built with HTML, CSS, and JavaScript</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-orange?style=for-the-badge&logo=html5" />
  <img src="https://img.shields.io/badge/CSS-3-blue?style=for-the-badge&logo=css3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript" />
</p>

https://jbmsacps-stack.github.io/calculator-webpage/code/index.html

---

## 🧾 Overview

This project is a **functional calculator web application** designed to replicate a **modern mobile calculator interface**.
It focuses on clean UI structure, responsive layout, and interactive user experience using core frontend technologies.

---

## ✨ Key Features

* Arithmetic operations: `+  −  ×  ÷`
* Input editing:

  * Clear (`AC`)
  * Delete (`DEL`)
* Live clock display (`HH:MM` format)
* Smooth UI interactions (hover & active states)
* Mobile-style layout with rounded frame

---

## 🏗️ Architecture

| Layer     | Technology | Responsibility              |
| --------- | ---------- | --------------------------- |
| Structure | HTML       | Layout and elements         |
| Styling   | CSS        | UI design and positioning   |
| Logic     | JavaScript | Input handling & evaluation |

---

## 🎨 UI & Design Principles

* Dark theme for reduced visual strain
* Circular buttons with **inset glow effects**
* Grid-based layout for consistent spacing
* Subtle transitions for interaction feedback
* Minimal, focused interface

---

## ⚙️ Implementation Details

* Button inputs are handled via DOM manipulation
* Expressions are evaluated using:

  ```javascript
  eval(expression)
  ```
* Clock updates dynamically using:

  ```javascript
  setInterval()
  ```

---

## 📂 Project Structure

```id="u5r9cl"
.
└── index.html   # Contains HTML, CSS (internal), and JavaScript
```

---

## ⚠️ Technical Note

The project uses `eval()` for expression evaluation due to its simplicity.
For production-grade applications, it is recommended to replace it with a **custom parser or math library** to avoid security risks.

---

## 🚀 Future Enhancements

* Keyboard input support
* Improved calculation engine (without `eval`)
* Scientific calculator functions
* Responsive scaling for different screen sizes
* UI refinements (animations, haptics simulation)

---

## 👤 Author

**JB**
---

## 📌 License

This project is intended for **learning and demonstration purposes**.

---

<p align="center">
  ⭐ If you found this useful, consider starring the repository.
</p>
