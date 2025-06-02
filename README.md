# Card Game – Daniel Sela

A modern, animated, and sound-enhanced iOS **Card Game** built in Swift using UIKit.  
The game simulates the classic "War" card game: in each round, both the player and the PC draw a card — the higher card wins the round. First to win more rounds out of 10 is the winner.  
In case of a tie after 10 rounds, the game continues until there is a clear winner.

---

## 🎮 Features

- 🌍 Location-based side assignment (East vs. West) using CoreLocation.
- 🕹️ 10-round card battle game logic with automatic countdown and round management.
- 🔁 Automatic card flipping animation every few seconds.
- 🔊 Background music, flip sound, win and lose effects.
- 🎉 Confetti animation if you win!
- 🌓 Supports Dark Mode and adjusts visuals accordingly.
- 📱 Fully responsive layout for landscape and portrait orientations.
- 📸 Screenshots and video demonstration included.

---

## 📱 Screenshots

### 🧭 Welcome Screen
Portrait  
![Welcome Portrait](https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/1.png)

Landscape – Light & Dark  
![Welcome Light](https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/2.png)
![Welcome Dark](https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/3.png)

---

### 🃏 Game Screen  
Light & Dark  
![Game Light](https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/4.png)
![Game Dark](https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/5.png)

---

### 🏆 Result Screen  
Victory with confetti 🎉  
![Result Win](https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/6.png)

Loss screen 😢  
![Result Lose](https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/7.png)

---

## 🎥 Demo Video

https://raw.githubusercontent.com/DanielSelas/CardGame/main/Assets/example.mov

---

## 🧱 Built With

- `UIKit` – Interface and interaction logic.
- `CoreLocation` – To determine east or west side for the player.
- `AVFoundation` – For playing background music and sound effects.
- `CAEmitterLayer` – Used to implement confetti fireworks animation on victory.

---

## 📦 Assets Attribution

All sounds and images used in this app were sourced from publicly available free asset websites (e.g., freesound.org, flaticon.com) and are not self-created.  
They are used for academic and non-commercial purposes only.

---

## 👤 Author

**Daniel Sela**

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/DanielSelas/CardGame.git
