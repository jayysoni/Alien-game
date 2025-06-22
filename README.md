Space Shooter Game

A classic arcade-style 2D space shooter game built using Python and Pygame. Destroy incoming enemy ships, dodge lasers, and survive as long as possible!

   Game Features<br>
	•	✅ Smooth spaceship movement (WASD)<br>
	•	✅ Laser shooting (SPACEBAR)<br>
	•	✅ Increasing enemy wave difficulty<br>
	•	✅ Collision detection using pixel-perfect masks<br>
	•	✅ Health bars and lives system<br>
	•	✅ Game over screen with delay before exit<br>
	•	✅ Start menu screen<br>

How to Run
1. Clone the Repository
   <pre>
```bash
git clone https://github.com/jayysoni/Alien-game.git
   cd Alien-game
```
</pre>

3. Install Dependencies

Make sure you have Python3 installed
Install Pygame:
 <pre>
 pip install pygame
</pre>

3. Run the Game
   python main.py

Controls
<pre>
Key                Action<br>
W / ↑              Move Up<br>
A / ←              Move Left<br>
S / ↓              Move Down<br>
D / →              Move Right<br>
SPACEBAR           Shoot Laser<br>
</pre>
<pre>
text
Alien-game/
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
</pre>


 Game Logic Overview<br>
	•	The player controls a Hero ship
	•	Enemies of random color spawn in waves
	•	Each ship can shoot lasers
	•	Collision detection is handled using Pygame’s mask for pixel-perfect accuracy
	•	The player loses health if hit or if enemies pass them
	•	Game ends after the player runs out of lives or health

 Future Improvements<br>
	•	Add sound effects and background music
	•	Power-ups and different laser types
	•	Boss fights or unique enemy behaviors
	•	Pause functionality
	•	High-score tracking
