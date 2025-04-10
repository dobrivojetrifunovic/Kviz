# Quiz

This project is two-player quiz game written in go programming language. In this project TCP was used for networking and SQLite was used for question storage.

## Features
- **Two player game**: Players can connect using TCP and play a game together.
- **SQLite database**: The quiz questions and answers are stored in SQLite database.
- **Real-time score updates**: The current score for both players is updated during the game. In the end of the game player can see number of points he achieved and also if he won, lost or it was draw.
- **Private rooms**: Players can create or join private rooms using random generated code.

## Technologies
- **Go**: Backend logic, TCP server
- **Fyne**: GUI client for interface
- **SQLite**: Database created for questions and answers
- **TCP**: Network communication for multiplayer gameplay
