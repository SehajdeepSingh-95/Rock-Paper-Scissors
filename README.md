# ✊✋✌️ Rock-Paper-Scissors Game

A simple **vanilla JavaScript** implementation of the classic **Rock-Paper-Scissors** game where a player competes against the computer.

---

## 🚀 Features
- 🎮 Choose between **Rock**, **Paper**, or **Scissors**
- 🤖 Computer randomly selects a choice
- 🏆 Displays the result: **Win / Lose / Draw**
- 🔄 Play unlimited rounds without refreshing the page
- ⚡ Lightweight and fast — built using pure JavaScript

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3** (for styling)
- **Vanilla JavaScript (ES6+)**

---

---

## 🖥️ Setup & Usage
1. Clone or download the project.
2. Include this basic HTML structure in `index.html`:
```html
<h1>Rock-Paper-Scissors</h1>

<div id="choices">
  <button onclick="play('rock')">Rock</button>
  <button onclick="play('paper')">Paper</button>
  <button onclick="play('scissors')">Scissors</button>
</div>

<p id="playerChoice">You chose: </p>
<p id="computerChoice">Computer chose: </p>
<p id="result">Result: </p>

<script src="script.js"></script>
