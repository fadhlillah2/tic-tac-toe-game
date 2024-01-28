# Tic Tac Toe WebSocket Game (Multiplayer)

## Introduction
Welcome to the Tic Tac Toe WebSocket Game! This project is a web-based version of the classic Tic Tac Toe game developed using Spring Boot. It features real-time gameplay between two players over a network, enabled by WebSocket technology. This game demonstrates the power of modern web applications in creating interactive and dynamic user experiences.

## Technologies Used
- **Java 17**: The core programming language used.
- **Spring Boot 3.0.1**: Simplifies the bootstrapping and development of new Spring applications.
- **Spring Boot WebSocket**: Enables real-time communication between the server and clients.
- **Thymeleaf**: Server-side Java template engine for web applications.
- **Maven**: Used for project build and dependency management.

## Features
- **Two-Player Gameplay**: Compete against another player in real-time.
- **WebSocket Integration**: Real-time updates of game progress.
- **Responsive UI**: Created with Thymeleaf templates for a seamless user experience.

## Prerequisites
To run this project, you need to have the following installed:
- Java 17 or higher
- Maven

## Installation and Setup
To set up and run the project on your local machine, follow these steps:

1. **Navigate to the project directory:**:
   ```bash
   cd tictactoewebsocket

2. **Build the project with Maven:**:
   ```bash
   mvn clean install

3. **Testing the project with Mockito:**:
   ```bash
   mvn test

4. **Run the application:**:
   ```bash
   mvn spring-boot:run

5. **Access the application at http://localhost:8080 on your browser.**
   
## How to Play
To start a game, a player must visit the site and enter their name. This will create a new game and the player will become player 1. The game will then wait for another player to join.

Player 2 can then visit the site and enter their name. This will start the game, with player 1 going first.

Players alternate making moves by clicking on an empty square on the game board. The first player to get 3 of their symbols in a row (horizontally, vertically, or diagonally) wins the game. If all squares are filled and no player has won, the game is a tie.

If a player leaves the game, the other player wins the game.

The state of the game is displayed at the top of the page, including whose turn it is and the current winner (if any).

Thank you for playing Tic-Tac-Toe!
