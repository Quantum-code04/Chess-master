# Chess-Game 
This project involves developing a fully functional chess game using Java. The goal is to create a desktop application that enables two players to play chess with a user-friendly graphical interface. 
Create a two-player chess game using Java that allows players to play the classic game of chess. The game should incorporate a graphical user interface (GUI) for an interactive experience, enabling players to move pieces by clicking or selecting and targeting specific squares. The program should handle all standard chess rules, including piece movement, capturing, checks, checkmates, stalemates, and castling. Additionally, it should have features such as move validation, move history, and the ability to reset or end the game.

# Project Struvture 
ChessGameProject/
├── src/
│   └── com/
│       └── chess/
│           ├── Main.java             
│           ├── board/
│           │   ├── Board.java       
│           │   ├── Square.java       
│           ├── pieces/
│           │   ├── Piece.java       
│           │   ├── Pawn.java         
│           │   ├── Rook.java         
│           │   ├── ...              
│           ├── gui/
│           │   ├── Table.java        
│           │   └── BoardRenderer.java
│           ├── moves/
│           │   ├── Move.java        
│           │   └── MoveValidator.java
│           ├── util/
│           │   └── Utils.java        
├── README.md                         
└── assets/                           
