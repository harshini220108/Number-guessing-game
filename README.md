 # Number Guessing Game

A simple console-based Number Guessing Game written in Java. The program 
generates a random number between 1 and 100, and the player has **5 attempts** 
to guess it correctly. After each guess, the game gives a hint telling the 
player whether the actual number is greater or smaller than their guess.

## Features

- Random number generation (1–100)
- Limited attempts (5 tries)
- Real-time hints (higher / lower)
- Simple, beginner-friendly Java code using `Scanner` and `Math.random()`

## How to Run

1. Make sure you have Java (JDK 8 or later) installed:
   ```bash
   java -version
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/number-guessing-game.git
   cd number-guessing-game
   ```

3. Compile the program:
   ```bash
   javac Geeks.java
   ```

4. Run it:
   ```bash
   java Geeks
   ```

## Example

```
A number is chosen between 1 and 100.
You have 5 attempts to guess the correct number.
Enter your guess: 50
 The number is greater than 50
Enter your guess: 75
 The number is less than 75
Enter your guess: 63
 Congratulations! You guessed the correct number.
```

## Project Structure

```
number-guessing-game/
├── Geeks.java
├── .gitignore
└── README.md
```

## License

This project is open source and available under the [MIT License](LICENSE).
