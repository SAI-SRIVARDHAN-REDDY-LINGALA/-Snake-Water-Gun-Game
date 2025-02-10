# -Snake-Water-Gun-Game
 Snake-Water-Gun Game using PYTHON


# 🎯 **Snake-Water-Gun Game**  

Welcome to the **Snake-Water-Gun** game! 🐍💧🔫  
This is a simple Python-based command-line game where you play against the computer.  

---

## 📌 **How to Play?**  
- The game follows the classic **Snake-Water-Gun** rules:  
  - 🐍 **Snake** beats 💧 **Water**  
  - 💧 **Water** beats 🔫 **Gun**  
  - 🔫 **Gun** beats 🐍 **Snake**  
- You enter your choice:  
  - `"s"` for **Snake**  
  - `"w"` for **Water**  
  - `"g"` for **Gun**  
- The computer randomly picks its choice.  
- The winner is decided based on the game rules.  

---

## 🛠 **Setup & Run the Game**  
### 🔹 Prerequisites  
Make sure you have **Python** installed (Python 3 recommended).  

### 🔹 Run the Game  
1. **Clone the repository**  
   ```sh
   git clone https://github.com/YOUR_USERNAME/Snake-Water-Gun-Game.git
   cd Snake-Water-Gun-Game
   ```
2. **Run the script**  
   ```sh
   python game.py
   ```
3. **Enter your choice and play!** 🎮  

---

## 🖥 **Code Explanation**  
- **`random.choice([-1, 0, 1])`** → Computer randomly selects Snake, Water, or Gun.  
- **`youDict` & `reverseDict`** → Used to map user input to numbers & vice versa.  
- **Game logic** → Compares user and computer choices to decide the winner.  

---

## 🏆 **Example Gameplay**  

```
Enter your choice: s
You chose Snake
Computer chose Water
You win!
```

---

## 🎯 **To-Do List & Improvements**  
- ✅ Add user input validation  
- 🔲 Add multiple rounds & scoring system  
- 🔲 Convert to GUI-based game using Tkinter or Pygame  

---

## 🤝 **Contributing**  
Feel free to fork and improve the game! 🚀  
Pull requests are welcome.  

---

## 📜 **License**  
This project is **open-source** and available under the **MIT License**.  

---

🚀 **Enjoy the game & have fun!** 🐍💧🔫
