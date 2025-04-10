# 🎲 Snake & Ladders - C++ Console Game

Welcome to **Snake-N-Ladders-OOP-Cpp** — a simple, fun, and object-oriented console-based implementation of the classic board game, built using C++!

This game allows multiple players to race to the top of a 10x10 board while dodging snakes 🐍 and climbing ladders 🪜. Dice rolls are uniquely seeded using user-provided strings for a twist of randomness!

---

## 📌 Features

- 🧑‍🤝‍🧑 **Multiplayer support**
- 🎲 **String-based seeding** for random dice rolls
- 🐍 Random **snakes** and 🪜 **ladders**
- 🔁 **Turn-based** gameplay
- 🏁 Win condition at **position 100**
- 👨‍💻 Clean, modular **object-oriented design**

---

## 🧱 Project Structure

├── src/
│   ├── main.cpp          # Entry point of the game
│   ├── board.h           # Board implementation (snakes, ladders, movement logic)
│   ├── player.h          # Player class (name, position, movement)
│   ├── gameState.h       # Game state management
│   ├── specialEntity.h   # Dice rolling & entity generation (snakes/ladders)
├── README.md             # Documentation


---

## 🎮 How to Play

1. **Compile and run the game**.
2. **Enter number of players**.
3. **Roll the dice** by entering a "lucky" string (used as a seed).
4. **Players move** based on dice outcome.
5. 🐍 Watch out for snakes and 🪜 climb those ladders.
6. First player to reach **position 100** wins! 🏆

---

## ⚙️ Compilation & Execution

### 🔧 Using g++

mkdir build && cd build
cmake ..
make
./SnakeGame

⚙️ Using CMake

mkdir build && cd build
cmake ..
make
./SnakeGame
 ---
🛠️ Customization
Change the board size: modify BoardSize in board.h.

Adjust the number of snakes/ladders: tweak logic in generateSnake() and generateLadders() functions.

🚀 Future Improvements
🖥️ Add graphical interface (SFML/SDL)

🤖 AI-controlled players

💾 Save/resume game state feature
---
📜 License
This project is open-source. Feel free to fork it, modify it, and share it with the world! 🌍


💡 Contributions & Feedback
Open to suggestions, bug reports, and pull requests!
If you enjoyed the game, give the repo a ⭐ and help spread the fun!









