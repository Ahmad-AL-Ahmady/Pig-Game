# Pig Game

Welcome to the **Pig Game** repository! This project is a two-player dice game built with HTML, CSS, and JavaScript.

## Table of Contents

- [Demo](#demo)
- [Objective](#objective)
- [Gameplay](#gameplay)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Demo

Check out the live demo of the game [Pig Game](https://pig-game-alahmady.netlify.app/).

## Objective

- Be the first player to reach a total score of 100 or more.

## Gameplay

1. **Setup:**

   - Two players take turns rolling a dice.
   - Each player starts with a current score of 0.
   - Player 1 goes first.

2. **Rolling:**

   - On your turn, roll the dice.
   - If the dice roll is not 1:
     - The dice roll is added to your current score.
     - You can choose to roll again or hold.
   - If the dice roll is 1:
     - Your current score becomes 0.
     - Your turn ends, and the other player takes their turn.

3. **Holding:**

   - If you choose to hold, your current score is added to your total score.
   - Your turn ends, and the other player takes their turn.

4. **Winning:**

   - The first player to reach a total score of 100 or more wins the game.

5. **Resetting:**
   - To start a new game, both players' scores are reset to 0.

## Features

- **Interactive Gameplay**: Two-player turn-based dice rolling game.
- **Responsive Design**: Optimized for various screen sizes to ensure a smooth experience on all devices.
- **Dynamic UI Updates**: Messages and styles update dynamically based on user interactions.
- **Score Tracking**: Track current and total scores for both players.
- **Reset Option**: Easily reset the game to start over.

## Installation

To get a local copy up and running, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/pig-game.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd pig-game
   ```

3. **Open `index.html` in your browser:**

   You can simply double-click the `index.html` file to open it in your default web browser, or you can serve the project using a local server like `live-server`:

   ```bash
   live-server
   ```

## Usage

1. **Start the game:**

   - Player 1 starts by rolling the dice using the "Roll dice" button.
   - Follow the rules described in the [Gameplay](#gameplay) section.

2. **Reset the game:**
   - Click the "New game" button to reset the scores and start a new game.

## Contributing

Contributions are welcome! If you have suggestions for improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.
