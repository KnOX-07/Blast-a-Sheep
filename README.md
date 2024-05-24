# Blast-a-Sheep

<p align="left">
  <img width="731" alt="Blast-a-Sheep" src="https://github.com/KnOX-07/Blast-a-Sheep/assets/114283758/138e2e1a-9ce4-4eb5-a28e-df20590442bf">
</p>

Blast-a-Sheep is a simple browser-based game that combines elements of a shooting game with an infinite runner. The game is implemented using HTML, CSS, and JavaScript, specifically the HTML5 canvas API for rendering graphics.

## Gameplay

- **Player Character**: The player controls a character on the canvas. The character can move up and down within the bounds of the canvas.
- **Movement**: The character's movement is controlled using the arrow keys:
  - Up arrow key (↑) moves the character up.
  - Down arrow key (↓) moves the character down.
- **Shooting**: The character can shoot bullets to destroy targets by pressing the spacebar.

## Objectives

- **Targets**: Targets move from the right side of the canvas to the left.
  - If a target collides with the player character, it is removed, and the player's score decreases by 10 points.
  - If a bullet hits a target, both the bullet and the target are removed, and the player's score increases by 10 points.

## User Interface

- **Player Name Input**: When the game loads, a popup asks the player to enter their name, which is then displayed above the character during gameplay.
- **Score Display**: The player's current score is displayed in the top-left corner of the canvas.

## Visuals and Styling

- **Canvas Styling**: The canvas has a dark background and a white border, creating a contrasting playing area.
- **Character and Target Representation**: The character and targets are represented using emojis for fun and visually distinct appearance.

## How to Play

1. **Enter Name**: When the game loads, enter your name in the popup and click "Start Game".
2. **Move Character**: Use the up (↑) and down (↓) arrow keys to move your character.
3. **Shoot Targets**: Press the spacebar to shoot bullets at the incoming sheep targets.
4. **Score Points**: Destroy as many targets as possible while avoiding collisions to maximize your score.
