# cs4006-minmax-tictactoe

## Overview
This project is a React-based implementation of Tic-Tac-Toe, developed as part of my learning journey in frontend development and the CS4006 Intelligent Systems module. It's designed to showcase concepts related to the min-max algorithm used in game theory and AI.
One of variable is intensionaly incorrect, since i tried to play around with some stuff, I will fix it, later... :)

![Imgur Image](https://i.imgur.com/mCTMUpC.png)
## Features
- Classic Tic-Tac-Toe gameplay for two players
- React-based user interface
- Display of game state and move history
- Calculation and display of metrics used in min-max algorithm:
  - Number of winning ways for each player
  - Difference in covered positions between players
  - Open positions count

## Code Structure
- `App.js`: Main game logic and React components
  - `Square`: Individual game board square
  - `Board`: Game board and state display
  - `Game`: Overall game management and history
- `index.js`: Entry point for the React application

## Key Functions
- `calculateWinner`: Determines if there's a winner
- `countWinningWays`: Calculates potential winning moves for a player
- `countOpen`: Counts open positions on the board

## Learning Outcome
This project helped me understand React state management, component interaction, and basic game theory concepts used in AI. It served as a practical application of the theoretical knowledge gained in the CS4006 Intelligent Systems module.

## Academic Performance
I achieved a grade of B1 in the CS4006 Intelligent Systems module.

## Note
This is a learning project and not intended for production use. It demonstrates basic concepts and may not include advanced features or optimizations.
