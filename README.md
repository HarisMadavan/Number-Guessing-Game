# Number Guessing Game

## Overview

The **Number Guessing Game** is a simple Java console application where the user tries to guess a randomly generated number. The game provides feedback on whether the guess is too high or too low until the correct number is guessed. The program keeps track of the player's performance on a scoreboard, displaying the best results.

## Features

- **Interactive Menu**: Users can choose to play the game, view the scoreboard, or exit the game.
- **Random Number Generation**: The range for the number to be guessed is determined by the user before the game starts.
- **Scoreboard**: Tracks the number of attempts it took to guess the correct number. The results are displayed in ascending order.
- **Input Validation**: Handles invalid inputs and prompts the user to try again.

## How to Play

1. When the game starts, you are greeted with a menu that offers the following options:
   - Play the game
   - View the scoreboard
   - Exit the game
2. If you choose to play the game, you will be prompted to enter the range for the random number generation (e.g., 1-100).
3. After the range is set, you will start guessing the number. The game will guide you by saying "Higher" or "Lower" until you guess the correct number.
4. After guessing the number correctly, the game will display the number of attempts and store your score on the scoreboard.
5. The scoreboard shows all your previous results, sorted by the number of attempts.

## Code Structure

- `menu()`: Displays the main menu and handles user input.
- `randomNumber()`: Generates a random number within the range specified by the user.
- `guessNumber()`: Handles the user's guessing process, provides feedback, and tracks the number of attempts.
- `displayScoreBoard()`: Displays the player's results, sorted by the fewest attempts.

## Requirements

- **Java**: The project is written in Java and requires JDK 8 or above.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/NumberGuessingGame.git
