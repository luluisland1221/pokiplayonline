# single-player-chess_game
Build a single-player chess game with HTML, CSS, and JavaScript! Create a checkered board and design piece icons. Users click squares to move pieces, with JavaScript validating moves. For a challenging opponent, consider using a chess engine library like Chess.js.
## Chess Game (VS Computer)
 we are going to create a chess game with javascript. in this javascript chess game you can play with computer, flip board and set position. in this code you will learn to use chessboardjs and chess.js library❗️
 ## FEN Notation
 FEN (Forsyth-Edwards Notation) is a standard notation used to represent a particular chessboard position. It provides a concise and human-readable way to describe the placement of chess pieces on the board, as well as other important information about the position. Here's how FEN notation works:

 A FEN string consists of six fields separated by spaces:

 1. Piece Placement (8 ranks): This field represents the positions of the pieces on the board. Each rank is represented by a series of characters, where:
    * <kbd>K</kbd> represents a white king.
    * <kbd>Q</kbd> represents a white queen.
    * <kbd>R</kbd> represents a white rook.
    * <kbd>B</kbd> represents a white bishop.
    * <kbd>N</kbd> represents a white knight.
    * <kbd>P</kbd> represents a white pawn.
    * <kbd>k</kbd> represents a black king.
    * <kbd>q</kbd> represents a black queen.
    * <kbd>r</kbd> represents a black rook.
    * <kbd>b</kbd> represents a black bishop.
    * <kbd>n</kbd> represents a black knight.
    * <kbd>p</kbd> represents a black pawn.
    * Digits (1-8) represent empty squares, with the number indicating the count of consecutive empty squares.

    For example, <kbd>rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR</kbd> represents the starting position of a chess game.

 2. Active Color (1 character): This field indicates which player's turn it is to move. <kbd>w</kbd> represents White's turn, and <kbd>b</kbd> represents Black's turn.
 3. Castling Availability (1-4 characters): This field indicates whether castling is still available for each player. The characters used are:
      * <kbd>K</kbd> for White kingside castling.
      * <kbd>Q</kbd> for White queenside castling.
      * <kbd>k</kbd> for Black kingside castling.
      * <kbd>q</kbd> for Black queenside castling.
      * <kbd>-</kbd> if no castling is possible.
   
  4. En Passant Target Square (1-2 characters): If a pawn has just moved two squares forward from its starting position, this field represents the square where the opposing pawn can capture en passant. Otherwise, it is represented as <kbd>-</kbd>.
  5. Halfmove Clock (1-2 characters): This field represents the number of half-moves (ply) since the last pawn move or capture. It is used for the fifty-move rule.
  6. Fullmove Number (1-2 characters): This field represents the number of full moves (complete turns) in the game. It starts at 1 and is incremented after Black's move

Here's an example FEN string:

```
rnbqkb1r/ppp1pppp/5n2/3p4/3P4/8/PPP2PPP/RNBQKBNR w KQkq - 0 4
```

This FEN represents a specific board position where it's White's turn to move, both sides have the potential to castle kingside and queenside, there's no en passant target square, the halfmove clock is 0, and the fullmove number is 4.

You can use FEN notation to record and share specific chess positions and use them for various purposes, including setting up custom positions for analysis or practice.

## Screenshot
Here we have project screenshot :
### example_1:
![Uploading image.png…](screen_shot/img1.png)
### example_2{set position}:
![Uploading image.png…](screen_shot/img2.png)
### example_3{flip board}:
![Uploading image.png…](screen_shot/img3.png)
