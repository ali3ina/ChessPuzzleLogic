# EECS 3201 Final Project - Chess Visualisation Puzzles

## Project Team

- Beto Rico Alfaro
- Ali Sina

## Project Overview

The EECS 3201 Final Project focuses on chess visualization puzzles. It features six predetermined puzzles with puzzle coordinates displayed. Users input their answers using switches, toggling between digits, and the leftmost switch for digit selection. The key1 button functions as a skip or verify/advance button. The LED score system indicates correct puzzle answers. After the last puzzle, LEDs reset, and the cycle begins again.

## Code Structure

- **input_handling.v:**
  - Verilog module that interprets user inputs from switches and buttons.

- **chess_puzzle_logic.v:**
  - Verilog module that controls the chess puzzle game.
  - Stores puzzle views and answers.
  - Determines correctness of user responses.

- **seven_seg_display_driver.v:**
  - Verilog module that translates binary inputs into signals for seven-segment displays for character visualization.

- **DE10_LITE_Golden_Top.v:**
  - Top-level Verilog module integrating sub-modules.
  - Coordinates flow of information between user interface, game logic, and display output.

## Chess Puzzle Information

- User always controls white pieces.
- Coordinates for the best move for the given piece.

## Puzzles List

1. **Knight Fork:**
   - Black King: b3
   - Black Rook: d7
   - Knight: e4

2. **Knight Fork:**
   - Black King: a2
   - Black Rook: c6
   - Knight: c2

3. **Bishop Fork:**
   - Black King: f6
   - Black Rook: c3
   - Bishop: b6

4. **Bishop Skewer:**
   - Black King: c3
   - Black Queen: a5
   - Bishop: h4

5. **Queen Checkmate:**
   - Black King: b8
   - White Bishop: f3
   - Queen: g7

6. **King Draw:**
   - Black King: e5
   - Black Pawn: e6
   - King: d2

## Answers List

C5, b4, d4, E1, b7, E3

## Video Link

[Watch Project Video](https://www.youtube.com/watch?v=ZWpLmUFcZTg&ab_channel=bobthecookie)

## Project Files

- input_handling.v
- chess_puzzle_logic.v
- seven_seg_display_driver.v
- DE10_LITE_Golden_Top.v

Feel free to explore the Verilog project files, watch the video, and provide feedback for further improvement!
