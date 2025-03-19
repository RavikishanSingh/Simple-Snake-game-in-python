# 🐍 Simple Snake Game in Python

A classic **Snake Game** implemented in **Python** using the `turtle` module. The player controls a snake that moves around the screen, eating food to grow in length while avoiding collisions with walls and itself. The game keeps track of the player's score and stores the highest score achieved.

## 🎮 Features
✔️ **Smooth Snake Movement**  
✔️ **Random Food Placement**  
✔️ **Score Tracking & High Score Saving**  
✔️ **Collision Detection (Wall & Self)**  
✔️ **Game Over Screen**  
✔️ **Simple & Minimalist UI**  

## 📌 How to Play
- **Arrow Up (↑)** → Move Up  
- **Arrow Down (↓)** → Move Down  
- **Arrow Left (←)** → Move Left  
- **Arrow Right (→)** → Move Right  
- The snake grows when it eats food.  
- The game ends when the snake collides with the wall or itself.  
- The highest score is saved for future sessions.  

## 🛠 Installation & Setup
1. **Install Python 3**  
   Ensure Python 3 is installed on your system. You can download it from [Python's official website](https://www.python.org/downloads/).

2. **Clone this repository**  
   Open your terminal or command prompt and run:  
   ```sh
   git clone https://github.com/RavikishanSingh/Simple-Snake-game-in-python.git
   cd Simple-Snake-game-in-python
   ```

3. **Run the Game**  
   Execute the following command:  
   ```sh
   python main.py
   ```

---

## 📂 Project Structure
```
📦 Simple Snake Game
 ┣ 📜 main.py         # Main game loop
 ┣ 📜 snake.py        # Snake class (movement and growth)
 ┣ 📜 food.py         # Food class (spawning new food)
 ┣ 📜 scoreboard.py   # Scoreboard class (score tracking)
 ┗ 📜 data.txt        # Stores high score
```

### 🔹 `main.py`  
- Sets up the game window using `turtle.Screen()`.  
- Creates instances of `Snake`, `Food`, and `Scoreboard`.  
- Listens for keyboard input to move the snake.  
- Contains the main game loop that updates the game state.  

### 🔹 `snake.py`  
- Defines the `Snake` class to manage the snake's movement.  
- Implements methods to extend the snake, move in different directions, and prevent it from reversing into itself.  

### 🔹 `food.py`  
- Defines the `Food` class, which generates food at random locations.  
- Uses `turtle.Turtle()` to display food as a small blue circle.  

### 🔹 `scoreboard.py`  
- Manages the player's score and the high score.  
- Displays the current score on the screen.  
- Saves the highest score to `data.txt` and loads it on game start.  

---


## 🚀 Future Improvements (Optional)
- Add sound effects for eating food and game over.  
- Implement different difficulty levels (speed increase over time).  
- Add a pause and resume feature.  
- Introduce power-ups for bonus points or special abilities.  

---

## 📝 License
This project is **open-source** and available under the **MIT License**.  

---

## 🤝 Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request with your improvements.  

---

Enjoy playing **Simple Snake Game in Python**! 🎮🐍  
If you like the project, consider giving it a ⭐ on GitHub!  

```

Replace `"yourusername"` in the **git clone** URL with your actual GitHub username. You can also **add screenshots** to make the `README.md` more visually appealing.  

Let me know if you need further modifications! 🚀
