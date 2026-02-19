# Coins Rain Game

This project is a simple game developed in Python using the Pygame library.
The player controls a robot that collects coins while avoiding monsters falling from the top of the screen.

#

OOP Concepts Applied:
  - Abstract Base Class usage (FallingObjects)
  - Inheritance & Polymorphism (Coin, Monster)
  - Game loop management
  - Collision detection using AABB algorithm
  - State handling (score, health, game over condition)

#

Architecture:
  - Game management (MiniGame)
  - Player entity (Robot)
  - Abstract falling object behavior (Falling_objects)
  - Concrete object implementations (Coin, Monster)

#

Technologies:
  - Python 3.x
  - Pygame

#

Game Mechanics: 
  - Player movement using LEFT / RIGHT keyboard input
  - Dynamic object spawning with time-based delays
  - Health system (3 HP at start; collision with a monster reduces HP by 1; game ends at 0 HP)
  - Score system (+1 point per collected coin)
  - Automatic object removal after collision or when leaving the screen

#

# How to run

Install dependencies:
  - pip install pygame

Required Assets - The following files must be present in the project directory:
  - robot.png
  - coin.png
  - monster.png

Run the game:
  - python main.py

#

Screenshot:

<img width="639" height="508" alt="image" src="https://github.com/user-attachments/assets/03395dcf-bea5-47a6-bbc6-49d59b594e6d" />

#

Possible Extensions:
  - High score persistence (file or database)
  - Additional coin types with different point values
  - Increasing difficulty over time (e.g., faster falling speed, higher spawn rate of monsters)
  - Time limit mode (e.g., 10-minute countdown)
  - Difficulty levels (easy / medium / hard)







