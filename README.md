# 🎮 Tic-Tac-Toe in C

A classic **Tic-Tac-Toe game** implemented in **C**, where a human player competes against an AI opponent with two difficulty levels. This terminal-based game includes a smart computer opponent, a scoreboard, and randomized turns.

---

## 🚀 Features

- 🧠 **AI with Two Difficulty Levels:**
  - **Standard Mode:** Basic logic for a fun challenge.
  - **God Mode:** Impossible to beat – perfect blocks and wins.
- 🎲 **Randomized first move** (player or computer).
- 📊 **Scoreboard** tracking wins, losses, and draws.
- 🖥️ **Terminal-based interface** for a clean user experience.
- ⚙️ **Cross-platform support** (Windows/Linux).

---

## 🛠️ Technologies Used

- C (Standard C libraries)
- Console I/O (`stdio.h`, `stdlib.h`)
- Time functions (`time.h`)
- System detection for screen clearing

---

## 🧠 AI Strategy

1. Play for an **immediate win** if possible.
2. Otherwise, **block** the player's winning move.
3. In **God Mode**:
   - Take the **center** or a **corner** strategically.
4. If no better option, take the **first available space**.

---

## 📷 Screenshot

> (You can add a terminal screenshot of the game here.)

---

## ✅ How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-c.git
   cd tic-tac-toe-c
