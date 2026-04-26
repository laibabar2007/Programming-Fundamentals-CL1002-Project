# Programming-Fundamentals-CL1002-Project

###  Digital Hangman using Arduino

This project is a hardware-based implementation of the classic **Hangman game**, developed using **Arduino** and integrated electronic components. It combines programming fundamentals with embedded systems to create an interactive and engaging game experience.

The game randomly selects a word from a predefined pool, and the player guesses letters via the **Serial Monitor**. The current game state, including the word progress, remaining attempts, score, and timer, is displayed on a **16x2 I2C LCD**. A **buzzer** provides audio feedback for correct and incorrect guesses, while a **reset button** allows the user to restart the game at any time.



###  Hardware Components Used

- Arduino Board  
- 16x2 I2C LCD Display  
- Buzzer  
- Push Button (Reset)  
- Breadboard  
- Jumper Wires  



###  Features

- Random word selection from a predefined list  
- Real-time display of game progress on LCD  
- Score system with high score tracking  
- Countdown timer for each turn (15 seconds)  
- Automatic hints when time runs out  
- Sound effects for win, lose, and guesses  
- Reset functionality using a hardware button  



### Learning Outcomes

This project demonstrates:

- Integration of hardware with software  
- Use of Arduino libraries like `Wire` and `LiquidCrystal_I2C`  
- Game logic implementation in embedded systems  
- Handling user input via Serial Communication  
- Real-time feedback using display and sound  

