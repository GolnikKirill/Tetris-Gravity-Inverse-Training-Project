# Tetris: Gravity Inverse

This is my second **Godot C#** project. Built upon [Russ's Tetris tutorial](https://www.youtube.com/watch?v=2T2Fkzwf6FM) as a foundation, this version introduces custom gameplay mechanics—most notably **gravity inversion**, which reverses the falling direction of blocks every time 3 rows are cleared, alongside a landing preview ("ghost piece") and 5-tile pentomino figures.

## Screenshots
<img width="1308" height="658" alt="Gameplay screenshot 1" src="https://github.com/user-attachments/assets/3e30d254-03dd-4042-822f-123e4fea9bd9" />
<img width="1309" height="659" alt="Gameplay screenshot 2" src="https://github.com/user-attachments/assets/a46a637b-1137-48b0-ae31-db057af1dca7" />
<img width="1280" height="581" alt="Gameplay screenshot 3" src="https://github.com/user-attachments/assets/8ed58304-d266-403a-9e97-62d637ce74b3" />

## Technology Stack
* **Languages:** C#, GDScript
* **Engine:** Godot Engine (.NET / C# version)

## Features
* **Gravity Inversion:** Reverses block falling direction after clearing 3 rows.
* **Ghost Piece (Landing Preview):** Displays a visual indicator showing where the current block will land.
* **Extended Piece Set:** Includes custom 5-tile figures (pentominoes) in addition to classic tetrominoes.
* **Core Gameplay:** Piece movement, rotation, collision detection, row clearing, score tracking, and progressive speed increase.
* **Game State Controls:** Functional Pause and New Game states.

## How to Run Locally
1. Make sure you have the **Godot Engine (.NET version)** installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/GolnikKirill/Tetris-Gravity-Inverse-Training-Project
   ```
3. Open Godot Project Manager, click **Import**, and select the `project.godot` file from the cloned folder.
4. Run the project by pressing **F5** (or run the main scene directly with **F6**).

## Credits & Acknowledgments
* Core Tetris grid and tilemap mechanics were originally adapted from [Beginner Godot Tutorial - How to Make Tetris](https://www.youtube.com/watch?v=2T2Fkzwf6FM) by **Coding With Russ**, then ported to **C#** and expanded with custom mechanics.
