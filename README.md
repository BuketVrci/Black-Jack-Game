# ♠️ Java Console Blackjack 

![Java](https://img.shields.io/badge/Java-CLI-orange?style=for-the-badge&logo=java)
![OOP](https://img.shields.io/badge/Architecture-OOP-blue?style=for-the-badge)

### 📌 About the Project
This repository contains a fully playable, console-based Blackjack game written in Java. It is designed to run directly in the terminal and serves as a practical demonstration of Object-Oriented Programming (OOP) concepts, including state management, algorithmic logic, and custom object interactions.

---

## 🎮 Game Features
The application faithfully recreates standard casino Blackjack rules through command-line inputs:
* **Dynamic Ace Evaluation:** The game automatically adjusts the value of an Ace (either 1 or 11) to prevent the player or dealer from busting unnecessarily.
* **Automated Dealer Logic:** The dealer's hand plays automatically according to standard rules, hitting until it reaches a value of 17 or higher.
* **Hidden Cards:** The dealer's first card is hidden (displayed as an "X") during the player's turn to simulate a real table environment.
* **Unicode Formatting:** Cards are printed to the console using cleanly formatted strings and Unicode suit symbols (♥, ♦, ♠, ♣).
* **Continuous Play:** A game loop allows the user to play multiple rounds consecutively without restarting the application.
<img width="215" height="161" alt="Screenshot 2026-03-30 at 16 38 15" src="https://github.com/user-attachments/assets/ad29e249-f454-46ce-afec-54599b12e302" />
<img width="385" height="397" alt="Screenshot 2026-03-30 at 16 38 34" src="https://github.com/user-attachments/assets/2c26969e-989e-4312-ad33-fc871481066e" />

---

## 💻 Technical Architecture
The codebase is structured modularly, separating the game loop from the core components of a card game.

* **`Blackjack.java`**: The main driver class that manages the `Scanner` for user input, controls the game loop, and determines the win/loss/push conditions.
* **`Deck.java`**: Generates a standard 52-card deck and utilizes a custom randomization utility to shuffle the array of `Card` objects.
* **`Hand.java`**: Manages an `ArrayList` of cards for both the player and the dealer, containing the mathematical logic to calculate hand values and check for "bust" or "blackjack" conditions.
* **`Card.java`**: A data class representing an individual card, holding its rank, suit, and string representation.
* **`Randomizer.java`**: A Singleton-patterned utility class that handles random number generation for deck shuffling.

---
po-name.git](https://github.com/YourUsername/your-repo-name.git)
