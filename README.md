# 📱 Calculator Web App

<p align="center">
  <b>Mobile-inspired calculator built with HTML, CSS, and JavaScript</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-structure-orange?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-styling-blue?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-logic-yellow?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

---

## 🔗 Live Demo

👉 https://jbmsacps-stack.github.io/calculator-webpage/code/index.html

---

## 📸 Preview

![Calculator UI](screenshot.png)

---

## 🧾 Overview

A functional calculator web application designed to replicate a **modern mobile calculator interface**.
The project focuses on layout precision, clean UI design, and interactive behavior using core frontend technologies.

---

## ✨ Features

* Arithmetic operations: `+  −  ×  ÷`
* Input controls:

  * Clear (`AC`)
  * Delete (`DEL`)
* Live clock display (`HH:MM`)
* Interactive button feedback (hover & active states)
* Mobile-style layout with rounded edges
* Smooth UI transitions

---

## 🏗️ Architecture

| Layer     | Technology | Responsibility              |
| --------- | ---------- | --------------------------- |
| Structure | HTML       | Layout and elements         |
| Styling   | CSS        | Visual design and layout    |
| Logic     | JavaScript | Input handling & evaluation |

---

## 🎨 Design Approach

* Dark theme for reduced eye strain
* Circular button layout with inset glow
* Grid-based structure for alignment
* Minimal UI focused on usability
* Smooth interaction feedback

---

## ⚙️ Implementation Highlights

* DOM-based button interaction
* Expression evaluation using:

```javascript
eval(expression)
```

* Real-time clock using:

```javascript
setInterval()
```

---

## 📂 Project Structure

```
.
└── index.html
```

---

## ⚠️ Technical Note

This project uses `eval()` for simplicity.
In production environments, this should be replaced with a **custom parser or math library** for better security.

---

## 🚀 Future Improvements

* Keyboard input support
* Replace `eval()` with safer logic
* Add scientific calculator features
* Improve responsiveness
* Enhance animations

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
