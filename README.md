# Arcade Racer

A classic top-down 2D car racing game built entirely in the browser using HTML5 Canvas, CSS (Tailwind CSS for UI), and Vanilla JavaScript. Experience the thrill of dodging traffic and pushing your high score in this retro-inspired arcade game!

## Features

*   **Classic Arcade Gameplay:** Simple yet addictive top-down racing action.
*   **Responsive Controls:** Use arrow keys (Left/Right) or A/D keys to steer your car.
*   **Dynamic Difficulty:** Opponent cars and obstacles appear randomly and increase in frequency and speed as your score climbs.
*   **Scrolling Road Effect:** Realistic road movement and lane markings create an illusion of speed.
*   **Collision Detection:** Beware of crashes! One hit and it's game over.
*   **Score Tracking:** Challenge yourself to beat your high score, saved locally in your browser.
*   **Speed Indicator:** Keep an eye on your current speed as it increases with your score.
*   **Vibrant Graphics:** Clean, colorful, and simple graphics for a retro feel.
*   **Sound Effects:** Engaging engine and collision sounds powered by the Web Audio API.
*   **Responsive Design:** Playable on various desktop screen sizes.

## How to Play

1.  **Start the Game:** Click the "START GAME" button on the overlay.
2.  **Steer Your Car:**
    *   **Left:** Press the `Left Arrow` key or the `A` key.
    *   **Right:** Press the `Right Arrow` key or the `D` key.
3.  **Dodge Obstacles:** Avoid colliding with the opponent cars coming from the top of the screen.
4.  **Score Points:** Your score increases automatically as you survive.
5.  **Increase Speed:** As your score goes up, the game speed will gradually increase, making it more challenging.
6.  **Game Over:** If you hit an obstacle, the game ends. Your final score and the all-time high score will be displayed.
7.  **Restart:** Click the "RESTART GAME" button to play again and try to beat your high score!

## Technical Details

*   **Frontend:** HTML5, CSS (Tailwind CSS), Vanilla JavaScript.
*   **Graphics:** HTML5 Canvas for all game rendering (player car, obstacles, road, lane markings, score, speed).
*   **Audio:** Web Audio API for generating dynamic sound effects.
*   **State Management:** Minimal global variables and `localStorage` for high score persistence.
*   **Animation:** `requestAnimationFrame` for smooth, 60fps animations.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
