Simple 2D Movement Game with Boundaries

This Python game is created using the Pygame library, where a character moves within a window and is restricted by boundaries. If the character touches any edge of the screen, a message appears for a short period of time, indicating that the character has hit a boundary.

Features:
The character can move up, down, left, and right using the arrow keys or the W, A, S, D keys.
When the character hits the edges of the screen, a collision message appears.
Movement is influenced by acceleration, and the character's speed gradually changes (slows down when no key is pressed).
The game updates the screen and handles input in real-time.

How It Works?

Character Movement:
The character moves using the arrow keys or the W, A, S, D keys.
The movement is smooth, with acceleration and deceleration effects applied to simulate inertia.

Boundary Collision:
If the character touches the edges of the screen (left, right, top, or bottom), it will stop at the boundary, and a "You hit the boundary!" message will appear for 2 seconds.
Speed Control:
The speed of the character in each direction is controlled by acceleration, which gradually increases when keys are pressed and decelerates when they are released.
