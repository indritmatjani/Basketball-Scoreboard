# 🏀 Interactive Scoreboard App

A simple, modern, and interactive web application designed to track real-time scores for two teams (Home and Guest). Perfect for basketball, futsal, friendly matches, or any two-sided competition.

---

## ✨ Key Features

* **Digital LED/LCD-style Display**
  Uses a custom font (*digital-7.ttf*) loaded via `@font-face` to recreate a classic 7-segment scoreboard look.

* **Real-Time Interactive Scoring**
  Dedicated buttons for **+1**, **+2**, and **+3** points update the score instantly through JavaScript.

* **Visual Leader Indicator**
  The leading team’s score display automatically scales up and glows using CSS transitions triggered by JavaScript logic.

* **New Game Button**
  Instantly resets both scores to zero.

* **Clean, Responsive Design**
  Dark theme, minimal layout, and Flexbox-based structure for smooth use on any device.

---

## 🛠️ Technologies Used

* **HTML5** – Semantic structure and layout
* **CSS3** – Styling, Flexbox layout, transitions, and digital font integration
* **Vanilla JavaScript** – Score logic, DOM manipulation, and leader-highlighting

---

## 🚀 How to Run the Project

1. **Clone the repository**

```bash
git clone [INSERT YOUR REPO URL HERE]
```

2. **Navigate into the project folder**

```bash
cd interactive-scoreboard
```

3. **Check fonts**
   Make sure the custom font file (`digital-7.ttf`) is inside the `font/` directory.

4. **Open the project**
   Simply open `index.html` in your browser.

---

## 🖼️ Project Structure

| File         | Purpose | Key Content                                                   |
| ------------ | ------- | ------------------------------------------------------------- |
| `index.html` | Markup  | Structure, scoreboard layout, and button `onclick` handlers   |
| `index.css`  | Styling | Dark theme, Flexbox, `@font-face`, transitions, leader styles |
| `index.js`   | Logic   | Score variables, update functions, `checkLeader()`, and reset |

---

## ⚙️ JavaScript Logic Overview

* **DOM references:**
  Stores references to the score elements (`scoreHomeEl`, `scoreGuestEl`) and their containers.

* **`checkLeader()` function:**
  Called after every score update. Removes the `.leader` class from both containers and applies it only to the team with the higher score.

* **`restart()` function:**
  Resets both scores to zero and removes the leader highlight.

---

## 👤 Author

Indrit

---


