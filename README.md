# Number Guessing Game

A simple C++ number guessing game where players guess a randomly generated number within a specified range. Players can earn hints, view their scores on a leaderboard, and compete with other players.

## Features

- **Guess the Number**: Players guess a number within a specified range.
- **Difficulty Levels**: Choose from Easy, Medium, and Hard difficulty levels which affect the range of numbers and number of trials.
- **Hints System**: Players can request hints which indicate how close their guess is to the target number.
- **Leaderboard**: Track player scores and display a leaderboard.
- **Hint Rewards**: Earn extra hints after every 3 correct guesses.

## Classes and Functions

### `getValidInt(int min, int max)`

Prompts the user to enter a valid integer within the specified range. Repeats until a valid integer is entered.

### `playGame()`

Manages the gameplay for a single session. Allows the user to guess numbers, request hints, and tracks the number of attempts. Updates the leaderboard and hint counts based on performance.

### `displayLeaderBoard()`

Displays the leaderboard showing player names, their scores, and remaining hints.

### `displayMenu()`

Displays the main menu and handles user choices to play the game, view the leaderboard, or exit the application.

