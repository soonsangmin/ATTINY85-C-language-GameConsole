# ATTINY85-C-language-GameConsole
INTRODUCTION
 1. PROBLEMS
 The rapid advancement of technology, particularly in graphics, processors and memory, has played a pivotal role in the emergence of game consoles. As technology progressed, it became feasible to develop specialized gaming hardware capable of delivering immersive and visually stunning gaming experiences. Simultaneously, the surging popularity of video games and the increasing demand for accessible and convenient gaming platforms led to the creation of game consoles. These devices offered a plug-and-play experience, allowing gamers to enjoy their favorite titles without the need for complex setups or technical expertise. Consequently, the gaming industry experienced significant growth, with game consoles serving as dedicated and reliable platforms for developers to create and showcase their games. By using the knowledge learned and referenced, we want to learn and design a game console. So we choose the topic: “DESIGN A GAME CONSOLEUSING ATTINY85 MICROCONTROLLER”

 2. PURPOSES
 The project "DESIGN A GAME CONSOLE USING ATTINY85 MICROCONTROLLER" is to create a functional game console using the Attiny85 microcontroller. The project aims to demonstrate the ability to design and develop a gaming device by utilizing the capabilities of the Attiny85 microcontroller. The console may include features such as game controls, display output, sound, and gameplay functionality. The project seeks to showcase skills in hardware design, microcontroller programming, and game development, ultimately providing an enjoyable gaming experience on a compact and affordable platform.

 3. RESULTS
 The result of the project "Designing a Game Console Using Attiny85 Microcontroller" would be a fully functional game console built using the Attiny85 microcontroller. The specific outcome and features of the console will depend on the design and implementation choices made during the project. However, the expected result would be a compact gaming device capable of running custom-made or programmed games, with controls, display output, and possibly sound capabilities. The success of the project would be measured by the functionality, performance, and user experience of the game console.

BLOCK DIAGRAM
![image](https://github.com/user-attachments/assets/c5b9b0d1-2e88-4c7c-80a6-adcf265f9673)
The system is designed to consist of 5 interconnected blocks:
- Power block: Power supply for active other blocks.
- Processor block: Receive signals from a button block, process it, and transmit it to the display block and the sound block.
- Display block: Display of parameters, images of the program.
- Sound block: Emit the sound of the program.
- Button block: Move left, right, up and down and fire depends on the games.

SOFTWAREDESIGN
  Introduction
 "Space Attack" is an exciting and fast-paced game that puts you in the role of a space pilot defending your planet from an alien invasion. As the last line of defense, your mission is to shoot down the incoming alien spacecra while dodging their attacks.
  Gamelogic
 The logic behind the Space Attack ATtiny game involves several key components and mechanisms:
  Initialization:
 - The game initializes the necessary variables, such as the player's score, number of lives, and game state.
 - It sets up the display, input devices, and any other required hardware components.
  GameLoop:
 - The game operates within a continuous loop that updates the game state and handles player input.
 - Within each iteration of the loop, the game performs the following actions.
  Player Input:
 - The game checks for player input from buttons.
 - It detects movement commands to adjust the position of the player's spaceship horizontally.
 - It detects firing commands to launch projectiles towards the enemy spaceships.
  Enemy Spaceship Movement:
 - The enemy spaceships move horizontally across the screen.
 - They follow a predefined pattern or algorithm to determine their movement behavior.
 - The game may incorporate variations in speed and direction to increase difficulty.
  Player Spaceship and Projectile Interaction:
 - The game updates the position of the player's spaceship based on the player's input.
 - It restricts the movement within the boundaries of the screen.
 - When the player fires a projectile, the game creates a projectile object and launches it vertically towards the enemy spaceships.
 - The game checks for collisions between the player's projectile and the enemy spaceships.
 - If a collision occurs, both the projectile and the affected enemy spaceship are destroyed.
  Enemy Spaceship Projectile Interaction:
 - The enemy spaceships periodically fire projectiles towards the player's spaceship.
 - The game checks for collisions between the enemy projectiles and the player's spaceship.
 - If a collision occurs, the player loses a life or triggers a game over, depending on the implementation.
  Scoring and Level Progression:
 - The game updates the player's score based on the number of enemy spaceships destroyed.
 - It may provide bonus points for achieving specific milestones or consecutive enemy spaceship destruction.
 - As the player progresses, the game may increase the speed or aggression of the enemy spaceships.
  Game Overand Restart:
 - The game monitors the player's remaining lives and checks if any end-game conditions are met.
 - If the player loses all lives or the enemy spaceships breach the player's defenses, the game ends.
 - The game provides an option to restart, allowing the player to embark on a new mission to defend the galaxy.
 These are the fundamental elements of the game's logic, which handle player input, enemy movement, collision detection, scoring, and game over conditions. The specific implementation of these components may vary based on the chosen ATtiny microcontroller and the hardware and software configuration.

