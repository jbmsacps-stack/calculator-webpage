# 📱 Calculator Web App

<p align="center">
  <b>Mobile-inspired calculator with 3D phone simulation built using HTML, CSS, and JavaScript</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-orange?style=for-the-badge&logo=html5" />
  <img src="https://img.shields.io/badge/CSS-3-blue?style=for-the-badge&logo=css3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript" />
</p>

---

## 🔗 Live Demo

👉 https://jbmsacps-stack.github.io/calculator-webpage/calculator.html

---

## 📸 Preview

![Calculator UI](screenshot.png)

---

## 🧾 Overview

A fully functional calculator web application designed to replicate a **modern mobile calculator interface**, enhanced with a **3D phone simulation effect**.

This project focuses on UI realism, interaction feedback, and structured frontend logic using core web technologies.

---

## ✨ Features

* Arithmetic operations: `+  −  ×  ÷`
* Input controls:

  * Clear (`AC`)
  * Delete (`DEL`)
* Real-time clock display (`HH:MM`)
* Interactive button feedback (hover & active states)
* Mobile-style calculator layout
* **3D phone container with perspective and hover interaction**
* Smooth shadow and depth transitions

---

## 🎮 Interaction Experience

* The calculator is wrapped inside a **simulated phone frame**
* On hover, the phone:

  * Adjusts its perspective
  * Enhances depth using shadows
  * Slightly scales for a realistic lift effect

This creates a more immersive, device-like experience rather than a flat UI.

---

## 🏗️ Architecture

| Layer     | Technology | Responsibility                 |
| --------- | ---------- | ------------------------------ |
| Structure | HTML       | Layout and UI components       |
| Styling   | CSS        | Design, 3D effects, animations |
| Logic     | JavaScript | Input handling & calculations  |

---

## 🎨 Design Approach

* Dark theme for visual comfort
* Circular buttons with inset glow effects
* Grid-based layout for consistency
* **3D perspective using CSS `transform` and `perspective`**
* Hover-triggered device interaction
* Minimal, focused UI

---

## ⚙️ Implementation Highlights

* Calculator logic handled via DOM manipulation
* Expression evaluation using:

```javascript
eval(expression)
```

* Real-time clock using:

```javascript
setInterval()
```

* 3D interaction implemented using:

```css
perspective + transform + hover state
```

---

## 📂 Project Structure

```
.
└── calculator.html
```

---

## ⚠️ Technical Consideration

The project uses `eval()` for simplicity.
For production-grade applications, this should be replaced with a **safe parsing approach or math library**.

---

## 🚀 Future Improvements

* Keyboard input support
* Replace `eval()` with safer logic
* Add calculation history
* Improve responsiveness
* Add dynamic lighting / reflection effects
* Multi-device simulation (tablet / desktop UI)

---

## 👤 Author

**JB**

---

## 📌 License

This project is intended for **learning and demonstration purposes only**.

---

<p align="center">
  ⭐ If you found this project useful, consider starring the repository.
</p>
