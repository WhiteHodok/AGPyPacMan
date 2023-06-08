# AGPyPacMan - ENG

PyPacMan is a Pac-Man game implemented in Python using the Pygame library.

## Dependencies

PyPacMan relies on the following libraries:
- pygame
- numpy
- tcod

You can install the required dependencies by running the following command:

```sh
# lib install
pip install -r requirements.txt
```

## Game Overview

PyPacMan is a Pac-Man game where the player controls the character Pac-Man and navigates through a maze to collect cookies while avoiding ghosts. The objective is to collect all the cookies without being caught by the ghosts. Power-ups are also available that allow Pac-Man to eat the ghosts temporarily.

## How to Play

- Use the arrow keys to control the movement of Pac-Man.
- Collect all the cookies in the maze to win the game.
- Avoid the ghosts, as they will cause Pac-Man to lose a life if caught.
- Power-ups can be collected to temporarily enable Pac-Man to eat the ghosts.

## Features

- Player-controlled Pac-Man character.
- Ghosts with different behaviors: chase and scatter.
- Maze with walls and cookies.
- Power-ups that allow Pac-Man to eat ghosts.
- Scoring system: cookies, power-ups, and ghost eating.
- Lives system: Pac-Man has three lives.
- Game over condition: when Pac-Man loses all lives.
- Win condition: when all cookies are collected.

## Acknowledgments

- The Pygame library: https://www.pygame.org/
- The numpy library: https://numpy.org/
- The tcod library: https://python-tcod.readthedocs.io/

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
