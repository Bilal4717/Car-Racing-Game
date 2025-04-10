# 🚗 Car Racing Game

A 2D car dodging game built in **C** using the [raylib](https://www.raylib.com/) library.

Dodge traffic, race toward the score goal, and survive through increasing difficulty levels — all while enjoying smooth visuals and background music. Designed with a focus on **clean UI**, **game feel**, and **performance**.

---

## 🎮 Gameplay Overview

- You control a car that moves left and right.
- Avoid oncoming vehicles — collisions cost you a life.
- You start with **5 lives**, and the goal is to reach **100 points**.
- **Three levels of increasing difficulty**:
  - 🟢 **Easy**
  - 🟡 **Medium**
  - 🔴 **Hard**
- Each level features faster cars and trickier patterns.
- Includes a **high score system** to track your best performance.

---

## ✨ Features

- 🎚️ Level progression with increasing difficulty
- 🧠 High score tracking
- 🎵 Background music and sound effects
- 🖥️ Clean and simple GUI using raylib
- 🎮 Responsive and intuitive keyboard controls

---

## 🛠️ Built With

- **Language:** C
- **Graphics/Audio Library:** [raylib](https://www.raylib.com/)

---

## 🚀 Getting Started

### Prerequisites

- [raylib](https://www.raylib.com/) installed on your system

### Clone and Compile

```bash
git clone https://github.com/yourusername/car-dodger-game.git
cd car-dodger-game
gcc main.c -o car-dodger -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
./car-dodger
