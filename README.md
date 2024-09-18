# Connect4 Game

A classic Connect4 game built using Python, VS Code, where two players compete to connect four of their pieces in a line. The game can be played in two modes: Player vs Player (PvP) and Player vs Computer (PvC). This project offers a clean, interactive UI with a grid-based board and dynamic game state management. The game is designed for fun, quick matches, and can be easily expanded or modified for additional features.

## Features

- **Two Game Modes**: 
  - **Player vs Player**: Two human players take turns.
  - **Player vs Computer**: Play against an AI-controlled opponent.
- **Interactive UI**: A responsive grid for placing pieces.
- **Real-time Feedback**: Immediate win/loss/draw detection with animated alerts.
- **Dynamic Game Board**: Click-based controls for easy interaction.
- **Reset/Restart Option**: Quickly reset the game for a new match.
- **AI Strategy**: The computer opponent uses a basic decision-making algorithm.

## How to Play

1. Players take turns dropping their pieces (red and yellow) into the 7-column, 6-row grid.
2. The goal is to be the first player to form a horizontal, vertical, or diagonal line of four consecutive pieces.
3. The game announces a winner or declares a draw when all grid spaces are filled without a winning line.

## Installation & Setup

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/pankajkr-143/Connect4-Game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Connect4-Game
   ```

3. Install dependencies (if applicable):

   ```bash
   # For Python
   pip install -r requirements.txt

   # For JavaScript
   npm install
   ```

4. Run the game:

   ```bash
   # Example: For Python
   python connect4.py

   # Example: For JavaScript/Node
   npm start
   ```

5. Open your browser and navigate to `localhost:3000` (or another specified port) to start playing.

## Game Rules

- Players must drop their pieces into one of the columns.
- The piece will occupy the lowest available space in that column.
- The first player to align four pieces in a row (horizontally, vertically, or diagonally) wins the game.
- If all spaces are filled and no player has aligned four pieces, the game results in a draw.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (React/Vanilla JS) 
- **AI Algorithm**: Basic AI for computer vs player mode using Minimax (or any other AI technique).
  
## Screenshots

### Main Game Screen
![Screenshot 2024-09-18 081453](https://github.com/user-attachments/assets/f760f137-26ab-44dd-9ef3-1d7b4125f34d)


### Win/Loss Alert
![Screenshot 2024-09-18 081535](https://github.com/user-attachments/assets/5822c8bd-47bf-45fc-8cc7-f46fb56f8374)

## Future Enhancements

- Implement advanced AI strategies for more challenging gameplay.
- Add player statistics and leaderboard features.
- Implement multiplayer functionality with online support.
- Improve UI/UX with additional themes and animations.

## Contributions

Feel free to fork the repository, submit pull requests, or report issues. Contributions and feedback are always welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/newFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/newFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
