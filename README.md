# Tic Tac Toe Game

## Project Description

This is a simple Tic Tac Toe game implemented in React.js. The game allows two players to take turns marking squares in a 3x3 grid. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game. If all squares are filled and no player has three marks in a row, the game ends in a tie.

## Features

- Two-player game (Player X and Player O)
- Interactive 3x3 game board
- Automatic detection of win or tie conditions
- Option to restart the game after it finishes

## Technologies Used

- React.js
- CSS

## Getting Started

### Prerequisites

Make sure you have the following software installed on your local development machine:

- Node.js (https://nodejs.org/)

### Installation

1. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/your-username/tic-tac-toe-react.git
   ```

2. Navigate to the project directory:

   ```sh
   cd tic-tac-toe-react
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

### Running the Application

1. Start the development server:

   ```sh
   npm start
   ```

2. Open your web browser and navigate to `http://localhost:3000` to see the game.

## Project Structure

```
tic-tac-toe-react/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── Components/
│   │   ├── Square.js
│   │   ├── Patterns.js
│   │   └── ...
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── ...
├── package.json
├── README.md
└── ...
```

- `public/`: Contains the HTML file and other public assets.
- `src/`: Contains the React components, CSS, and JavaScript files.
  - `Components/`: Contains the individual component files (`Square.js`, `Patterns.js`, etc.).
  - `App.js`: Main React component that renders the game.
  - `App.css`: Styles for the application.
  - `index.js`: Entry point for the React application.

## Game Logic

### Main Components

- `App.js`: The main component that handles the game logic and state.
- `Square.js`: A functional component that represents a single square on the game board.
- `Patterns.js`: Contains the winning patterns for the game.

### State Management

- `board`: An array representing the 3x3 game board.
- `player`: A string representing the current player ("X" or "O").
- `result`: An object representing the game result with `winner` and `state` properties.

### Functions

- `chooseSquare(square)`: Updates the board state when a square is selected.
- `checkWin()`: Checks if the current player has won the game.
- `checkIfTie()`: Checks if the game has ended in a tie.
- `restartGame()`: Resets the game state to start a new game.

## Styling

The CSS styles are defined in `App.css` to provide a simple and clean layout for the game.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome all contributions and improvements!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy playing Tic Tac Toe! If you have any questions or feedback, feel free to open an issue in the repository.
