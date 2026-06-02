# Flappy Bird Java Desktop Game

> Java Programming Course · ITS Surabaya · 2024

A desktop clone of the classic Flappy Bird game built from scratch using Java Swing. Navigate the bird through pipes by pressing the spacebar how far can you go?

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Java_Swing-007396?style=flat&logo=java&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## Overview

This project is a desktop implementation of the iconic Flappy Bird game using **Java Swing** for rendering and game loop management. The player controls a bird that constantly falls due to gravity press `SPACEBAR` to flap and gain altitude, and navigate through the gaps between pipes without crashing.

---

## Gameplay

```
┌────────────────────────────┐
│       ███████              │
│                            │
│    🐦                      │  ← Press SPACE to flap!
│                            │
│       ███████              │
│                            │
│  Score: 5                  │
└────────────────────────────┘
```

- The bird falls continuously due to gravity
- Press `SPACEBAR` to flap upward
- Avoid hitting the pipes or the ground
- Each pipe successfully passed = +1 score
- Game over on collision press `SPACEBAR` to restart

---

## Features

- 🐦 Gravity & flap physics
- 🏆 Score counter
- 🔁 Game over & restart screen
- 🎮 Keyboard input handling (`SPACEBAR`)
- 🖼️ Sprite-based rendering with Java Swing

---

## Repository Structure

```
flappy-bird/
│
├── src/                    ← Java source files
│   └── [game classes]
│
├── bin/                    ← Compiled .class output (auto-generated)
│
├── .vscode/
│   └── settings.json       ← VS Code Java project settings
│
└── README.md
```

---

## Getting Started

### Prerequisites
- Java JDK 11 or higher
- VS Code with [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

  *or simply a terminal with `javac` and `java` available*

### Run in VS Code
1. Clone the repo and open the folder in VS Code
2. Click **Run ▶** on the main class or press `F5`

### Run via Terminal
```bash
# 1. Clone the repository
git clone https://github.com/agnespriscilla/flappy-bird.git
cd flappy-bird

# 2. Compile
javac -d bin src/*.java

# 3. Run
java -cp bin App
```

---

## Controls

| Key | Action |
|---|---|
| `SPACEBAR` | Flap / jump upward |
| `SPACEBAR` | Restart after game over |

---

## Key Concepts Covered

- **Java Swing** : `JFrame`, `JPanel`, `paintComponent()` for rendering
- **Game loop** : `javax.swing.Timer` for fixed-interval updates
- **Physics simulation** : gravity, velocity, collision detection
- **Event handling** : `KeyListener` / `ActionListener` for input
- **Object-oriented design** : Bird, Pipe, and Game classes

---

## Course Context

This project was developed as part of a Java programming course at Institut Teknologi Sepuluh Nopember (ITS) Surabaya (2024), applying object-oriented programming concepts through game development with Java Swing.

---

## Author

**Agnes Priscilla Sekartaji Hadikusuma**  
S1 Teknik Informatika · Institut Teknologi Sepuluh Nopember (ITS) Surabaya

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/agnespriscilla33)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/agnespriscilla)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:agnes.priscilla33@gmail.com)
