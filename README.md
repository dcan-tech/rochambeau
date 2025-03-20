# Rock-Paper-Scissors Game

This is a hand-coded Rock-Paper-Scissors game originally developed as a school project and currently undergoing improvements. The project is built with plain HTML, CSS, and JavaScript, and it's being refactored to adopt industry best practices—including a move toward an MVC-inspired structure and a mobile-first responsive design.

## Overview

The game displays a simple interface where the user can select Rock, Paper, or Scissors against a computer opponent. The computer's choice is randomized, and although there is currently no score tracking, the UI includes dynamic text "Ready? Here we go! Rock! Paper! Scissors!" and interactive buttons. After a round completes, the "Let's Go!" button changes to "Play Again?" and the hand icons display color-coded outcomes (for instance, the player's hand is orange and the computer's is pink, with a combination of colors if there’s a tie).

As part of the project requirements, design choices were captured using Figma based on a provided reference image. This process helped guide the visual layout and overall user experience, ensuring that the final implementation adheres closely to the original design intent.

## Features

- **Responsive Design Goal:**  
  Currently, the game displays correctly in one resolution only. An ongoing goal is to make the UI responsive and adaptive for various devices using a mobile-first approach.

- **Randomized Computer Choice:**  
  The computer randomly selects its move from Rock, Paper, or Scissors.

- **Dynamic Button Text:**  
  The "Let's Go!" button changes to "Play Again?" after the game round completes.

- **Outcome Visuals:**  
  When a tie occurs, the hand icons show a combination of colors (typically, the player’s choice in orange and the CPU’s choice in pink).

## Technologies

- **HTML:** Provides the basic structure of the game interface.
- **CSS:** Used for styling the game. The project has been refactored into separate CSS files for global styles (`main.css`) and game-specific styles (`game.css`), with plans to incorporate a mobile-first stylesheet.
- **JavaScript:** Implements the game logic, including randomizing the computer’s choice and updating the UI dynamically.

## Project Structure

The project follows an organized structure, inspired by the Model-View-Controller (MVC) pattern:
- **assets/**  
  Contains images and other static resources.
- **css/**
    - `main.css`: Global styles, resets, typography, and layout settings.
    - `game.css`: Styles specific to the Rock-Paper-Scissors game.
- **js/**  
  Contains the JavaScript files handling game logic and UI updates.
- **index.html**  
  The entry point of the application.

## How to Run

To run the game locally:
1. Clone the repository.
2. Open the project folder.
3. Open `index.html` in your favorite web browser.
    - Alternatively, you can serve the project using a local server (e.g., using VS Code's Live Server extension or any simple HTTP server).

## Future Enhancements

- **Responsive and Mobile-First Design:**  
  Implement a fully responsive layout using a dedicated mobile-first CSS file.
- **Score Tracking:**  
  Introduce a scoring system to keep track of wins and losses.
- **Enhanced Game Modes:**  
  Consider adding multiple rounds or multiplayer features.
- **UI/UX Improvements:**  
  Refine animations, button interactions, and overall layout for a smoother user experience.
- **Sound Effects:**
  Current iteration has no sound.

## Credits

- Original project developed as a school assignment.
- Design choices were captured using Figma based on a reference image provided in the assignment.
- Currently maintained and improved by Dylan Canfield.
- Inspired by classic implementations of Rock-Paper-Scissors.

## License

This project is open source and available under the [MIT License](LICENSE).
