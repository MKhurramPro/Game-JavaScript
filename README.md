<!-- ======================= -->

<!-- 🎮 ROCK PAPER SCISSORS – ULTRA PREMIUM README -->

<!-- ======================= -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=36&pause=1000&color=00C3FF&center=true&vCenter=true&width=700&lines=Rock+Paper+Scissors+Game;Ultra-Premium+JS+Project;Interactive+%7C+Responsive+%7C+Fun" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/UI-UltraPremium-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge" />
</p>

---

## 🎨 Ultra-Premium Features

* 🌟 Animated glowing buttons
* ⚡ Instant real-time results
* 🖐 Player vs Computer logic
* 🧠 Randomized balanced AI
* 📱 Fully responsive & mobile-friendly
* 🔊 Optional sound effects
* 🌙 Dark/Light mode ready
* 🎯 Scoreboard with live updates

---

## 📸 Demo GIF

<p align="center">
  <img src="https://github.com/MKhurramPro/rock-paper-scissors/raw/main/demo.gif" width="600" alt="Rock Paper Scissors Demo"/>
</p>

> *(Replace with your own animated GIF screenshot)*

---

## 🛠️ Tech Stack

| Technology            | Purpose                          |
| --------------------- | -------------------------------- |
| **HTML5**             | Game structure                   |
| **CSS3**              | Styling + animations + gradients |
| **JavaScript (ES6+)** | Game logic + DOM interactivity   |

---

## 📂 Project Structure

```
Game-JavaScript/
│── index.html
│── style.css
│── app.js
└── images/
     ├── paper.png/
     └── rock.png/
     └── scissors.png/
```

---

## 📜 How It Works

* 🖱 Click **Rock**, **Paper**, or **Scissors**
* 💻 Computer randomly selects a move
* 🏆 Winner determined using classic rules

| Player Move | Beats    |
| ----------- | -------- |
| Rock        | Scissors |
| Paper       | Rock     |
| Scissors    | Paper    |

---

## ▶️ Quick Installation

```bash
git clone https://github.com/MKhurramPro/rock-paper-scissors.git
cd rock-paper-scissors
open index.html
```

No dependencies — ready to play in any browser!

---

## 🧠 Core Logic Example

```js
function playRound(player, computer) {
  if (player === computer) return "draw";
  const rules = { rock: "scissors", paper: "rock", scissors: "paper" };
  return rules[player] === computer ? "win" : "lose";
}
```

---

## ⚡ Future Enhancements

* Multiplayer mode
* AI difficulty levels
* Animated score counters
* Sound effects for wins/losses
* Dark/Light toggle
* Mobile gestures support

---

## 💼 Author

**Muhammad Khurram Shahzad**
Full Stack Developer | AI/ML Engineer | JavaScript Developer

<p align="center">
  <a href="https://github.com/MKhurramPro/rock-paper-scissors/stargazers">
    <img src="https://img.shields.io/github/stars/MKhurramPro/rock-paper-scissors?style=social" alt="GitHub stars">
  </a>
</p>

---

## 🌐 Live Demo

[▶ Play Rock Paper Scissors Online](https://MKhurramPro.github.io/Game-JavaScript/)

---

<p align="center">Made with ❤️ and Vanilla JavaScript</p>
