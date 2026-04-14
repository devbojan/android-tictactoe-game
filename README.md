# Android Tic Tac Toe Game

## 🚀 Author
Bojan Brankovic 

## Project Overview
This project is a classic Tic Tac Toe (XO) game developed for Android devices. It demonstrates core game logic, user interaction, and mobile UI behavior through a simple yet strategic board game.

Tic Tac Toe is a well-known two-player game played on a 3x3 grid where players take turns placing symbols (X and O) and aim to align three in a row (horizontal, vertical, or diagonal). :contentReference[oaicite:0]{index=0}  

The project focuses on implementing game rules, turn-based logic, and responsive UI for a smooth mobile gaming experience.

## Features
- Two-player gameplay (local device)
- Turn-based logic (X vs O)
- Win/draw detection
- Game reset functionality
- Simple and intuitive UI
- Real-time board updates

## Tech Stack
- Java / Kotlin (Android)
- Android SDK
- Android Studio

## Game Logic
- Players take turns placing X or O on the grid  
- System checks for win conditions after each move  
- Game ends when:
  - A player gets 3 in a row  
  - All cells are filled (draw)  

## Application Flow
1. User launches the app  
2. Game board is displayed  
3. Players take turns tapping cells  
4. System updates board and checks result  
5. Winner or draw is displayed  
6. User can restart the game  

## Scope of Testing
- Game logic validation (win/draw conditions)
- Turn switching functionality
- UI responsiveness (tap interactions)
- Game reset behavior
- Edge cases (fast tapping, same cell click)

## Tools Used
- Manual Testing
- Android Emulator / Real Device
- Logcat (debugging)

## Testing Types
- Functional Testing
- UI Testing
- Exploratory Testing
- Regression Testing

## Deliverables
- Test Cases
- Bug Reports
- Test Execution Report

## Key Issues Identified
- Same cell can be selected multiple times
- Win condition not detected in certain diagonal cases
- Game allows moves after game is finished
- Reset button does not fully clear board state
- UI delays on rapid tapping

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/devbojan/android-tictactoe-game.git
