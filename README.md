# Project: Guess My Number Game

## Description

The **Guess My Number** game is a simple and interactive number guessing game designed to enhance user engagement. Built using **HTML**, **CSS**, and **JavaScript**, the game dynamically updates the UI based on user interactions and provides a fun way to test your guessing skills. Players aim to guess a randomly generated number between 1 and 20, with feedback provided on each guess.

## Features

### Gameplay
- **Random Number Generation**: Generates a random number between 1 and 20 for each game session.
- **Dynamic Feedback**: Provides immediate feedback on guesses (e.g., "Too High", "Too Low", "Correct").
- **Scoring System**:
  - Players start with a score of 20, which decreases with incorrect guesses.
  - Tracks the highest score achieved during the session.

### User Interface
- **"Check" Button**: Validates the user's guess and provides feedback.
- **"Again" Button**: Resets the game for a new round.
- **Dynamic Styling**: Changes background color and number box size on correct guesses.

### Design
- A retro-inspired design using the "Press Start 2P" font.
- Minimalist and user-friendly interface with clear instructions and visual feedback.

## Technologies Used

- **HTML**: For structuring the webpage and game elements.
- **CSS**: For styling the game, including animations and responsiveness.
- **JavaScript**: For game logic, event handling, and DOM manipulation.

## Code Breakdown

### **HTML**
- Provides the layout for the game, including:
  - A header displaying the game title.
  - Input fields for guesses and buttons for user interaction.
  - Sections for displaying feedback messages, score, and high score.

### **CSS**
- **Design Highlights**:
  - Retro aesthetic achieved using the "Press Start 2P" font.
  - Dynamic visual changes, such as background color and number box resizing.
  - Responsive layout ensuring consistent user experience across devices.

### **JavaScript**
- **Game Logic**:
  - `Math.trunc(Math.random() * 20) + 1`: Generates a random number between 1 and 20.
  - Validates user input and compares it to the secret number.
  - Adjusts the score based on the user's guesses.
- **DOM Manipulation**:
  - Updates the UI dynamically using `document.querySelector`.
  - Changes styles and feedback messages based on user interactions.
- **Event Handling**:
  - Listens for clicks on the "Check" and "Again" buttons to trigger game actions.

## How to Play

1. **Objective**: Guess the secret number between 1 and 20.
2. **Steps**:
   - Enter a number in the input box and click the "Check" button.
   - Follow the feedback messages to adjust your guesses.
   - Guess the correct number before your score reaches 0!
3. Click the "Again" button to start a new game.
