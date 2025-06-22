Space Shooter Game

A classic arcade-style 2D space shooter game built using Python and Pygame. Destroy incoming enemy ships, dodge lasers, and survive as long as possible!

   Game Features
	•	✅ Smooth spaceship movement (WASD)
	•	✅ Laser shooting (SPACEBAR)
	•	✅ Increasing enemy wave difficulty
	•	✅ Collision detection using pixel-perfect masks
	•	✅ Health bars and lives system
	•	✅ Game over screen with delay before exit
	•	✅ Start menu screen

How to Run

1. Clone the Repository
   git clone https://github.com/jayysoni/Alien-game.git
cd Alien-game

2. Install Dependencies

Make sure you have Python 3 installed.

Install Pygame:
pip install pygame

3. Run the Game
   python main.py

🎮 Controls
Key                Action
W / ↑              Move Up
A / ←              Move Left
S / ↓              Move Down
D / →              Move Right
SPACEBAR           Shoot Laser

📁 Project Structure
space-shooter/
│
├── assets/
│   ├── pixel_ship_blue_small.png
│   ├── pixel_ship_green_small.png
│   ├── pixel_ship_red_small.png
│   ├── pixel_ship_yellow.png
│   ├── pixel_laser_blue.png
│   ├── pixel_laser_green.png
│   ├── pixel_laser_red.png
│   ├── pixel_laser_yellow.png
│   └── background-black.png
│
├── main.py
└── README.md

 Game Logic Overview
	•	The player controls a Hero ship
	•	Enemies of random color spawn in waves
	•	Each ship can shoot lasers
	•	Collision detection is handled using Pygame’s mask for pixel-perfect accuracy
	•	The player loses health if hit or if enemies pass them
	•	Game ends after the player runs out of lives or health

 Future Improvements
	•	Add sound effects and background music
	•	Power-ups and different laser types
	•	Boss fights or unique enemy behaviors
	•	Pause functionality
	•	High-score tracking
