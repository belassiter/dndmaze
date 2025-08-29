# DnD's Maze Runner

A web-based maze game where you must navigate through a randomly generated maze, avoid enemies, and reach the exit.

## How to Play

-   **Objective:** Escape the maze by reaching the green exit.
-   **Controls:**
    -   **Desktop:** Use the arrow keys to move your character.
    -   **Mobile:** Use the on-screen D-pad to move.
    -   **Gamepad:** The game has support for gamepads.
-   **Enemies:** Avoid the red guardians that will pursue you through the maze.
-   **Scoring:** Your score is based on how quickly you complete each level. There are session and all-time high scores.

## Features

-   **Random Maze Generation:** Each level presents a new, randomly generated maze.
-   **Enemy AI:** Enemies use a pathfinding algorithm to hunt the player.
-   **Scoring System:** The game tracks your score, session high score, and all-time high score using Firebase.
-   **Sound Effects:** The game uses Tone.js to generate sound effects and music.
-   **Responsive Design:** The game is playable on both desktop and mobile devices.
-   **Multiple Game Modes:**
    -   **Difficulty:** Easy and Hard modes.
    -   **Style:** "Crazy" mode, which periodically regenerates the maze.
    -   **Graphics:** Choose between "Retro" and "Emoji" graphics.

## Technologies Used

-   **Frontend:** HTML, CSS, JavaScript
-   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
-   **Audio:** [Tone.js](https://tonejs.github.io/)
-   **Backend:** [Firebase (Firestore)](https://firebase.google.com/docs/firestore) for high score storage.

## Running Locally

To run the game locally, simply download the `dndmaze.html` file and open it in your web browser.

## Deployment

The game is automatically deployed to an FTP server on every push to the `main` branch using a GitHub Actions workflow. The workflow can be found in `.github/workflows/deploy.yml`.
