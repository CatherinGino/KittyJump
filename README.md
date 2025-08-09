# 🐱 Cute Cat Runner

A colorful, fun, and minimalist twist on the **Google Chrome Dino Game** — but instead of a dinosaur, you guide a **cute little cat** 🐾 to jump over **bushes 🌿, mushrooms 🍄, and flowers 🌸** while chasing your highest score.

Do Check it out: https://catheringino.github.io/KittyJump/

---

## 🎯 Inspiration
I’ve always loved the Chrome Dino Game for its simplicity and addictive gameplay.  
This project started as an idea to **recreate it**, but in a **more colorful, cheerful, and cute** way — replacing the dinosaur with a cat and adding nature-themed obstacles.

---

## ✨ Features
- 🐱 **Cute cat character**
- 🌿 **Random obstacles**: big bushes, small bushes, mushrooms, flowers, and bouquets
- 🏆 **Score counter** & **High score tracking** (saved in `localStorage`)
- 🎮 **Easy controls**:  
  - Press **any key** to start  
  - Press **↑** arrow to jump  
- ⚡ **Speed toggle** (Slow 🐢 / Fast 🚀)
- 🌸 **Bouquet mode** — sometimes two flowers appear together for extra cuteness
- 🎨 **Minimalist yet colorful design**

---

## 🛠 How It Works
1. **HTML** – Creates the game container, cat, scoreboard, and UI elements.
2. **CSS** – Styles the cat, obstacles, and overall game in a minimalist but colorful way.
3. **JavaScript** –  
   - Handles **jumping mechanics**
   - Spawns **random obstacles** at varying distances
   - Detects **collisions** with `getBoundingClientRect()`
   - Tracks **score and high score**
   - Controls game speed

---

## 📦 Installation & Run
1. Clone this repository:
   ```bash
   git clone https://github.com/CatherinGino/KittyJump.git
