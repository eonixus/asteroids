# Asteroids

Asteroids is a classic arcade-style game built using Python and the Pygame library. In this game, the player controls a triangle-shaped spaceship, avoiding and destroying asteroids to survive as long as possible.

## Features

- **Single-player Gameplay**: Control the spaceship and navigate through a field of asteroids.
- **Asteroid Splitting**: Large asteroids split into smaller ones when shot, continuing to divide until they disappear upon reaching their minimum size.
- **Random Respawning**: Asteroids respawn at random locations, increasing the challenge.
- **Shooting Mechanics**: Destroy asteroids using the spaceship's shooting capability.

## How to Play

1. **Controls**:
   - Use the arrow keys to navigate the spaceship.
   - Press the spacebar to shoot.
2. **Objective**:
   - Avoid collisions with asteroids.
   - Shoot and destroy asteroids to earn points.
   - Survive as long as possible!

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/eonixus/asteroids/archive/refs/heads/main.zip
   cd asteroids-main
   ```

2. Create a virtual environment at the top level of your project directory:
   ```bash
   python3 -m venv venv
   ```

3. Activate the virtual environment:
   ```bash
   source venv/bin/activate
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the game:
   ```bash
   python3 main.py
   ```

## Acknowledgments
- Inspired by the classic arcade game "Asteroids" you can see in https://freeasteroids.org/.
- Built with Python and Pygame.