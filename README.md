# Simple_implementation_of_Monopoly_in_Java
# Monopoly Game

This project implements a Java version of the classic Monopoly board game. It offers two versions: a simplified version without JDBC (Java Database Connectivity) and a more complex version involving JDBC for database interaction. 

## Contributors

- Akarsh Kumar Gowda
- Srihari Acharya
- Pranav Kulkarni

## Features

- *Simplified Version*: The simplified version of the game is fully functional and allows players to play the game without database integration.
- *JDBC Version*: The JDBC version attempts to integrate database functionality using JDBC for storing player information and game data. However, it encountered issues during implementation.
- *Player Management*: Players can be initialized with custom names and starting money.
- *Dice Rolling*: Simulates dice rolls for player movements.
- *Property Management*: Allows players to purchase properties and collects rent when other players land on their properties.
- *Turn-based Gameplay*: Implements a turn-based system where players take turns rolling dice and interacting with the game board.
- *Game End Conditions*: Checks for game end conditions such as bankruptcies or all properties being purchased.

## How to Run

1. Ensure you have a MySQL database set up and running.
2. Modify the JDBC connection details in the DatabaseManager.java file to match your database configuration.
3. Compile the Java files using javac *.java.
4. Run the MonopolyGame class using java MonopolyGame.

## Known Issues

- The JDBC version encountered issues during implementation and may not work as expected. Contributions to resolve these issues are welcome.

Feel free to contribute to this project by submitting bug fixes, feature enhancements, or any other improvements.
