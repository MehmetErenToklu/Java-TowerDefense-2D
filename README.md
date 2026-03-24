Project Overview:

This project is a strategic 2D tower defense game developed with Java and JavaFX. The gameplay revolves around protecting a base from waves of enemies by placing defensive towers on a grid-based map. 
Each level is generated dynamically from external configuration files that define the map layout and wave data.

Technical Features:

The game utilizes a real-time loop through AnimationTimer to manage movement, combat logic, and UI updates. 
Key mechanics include a variety of tower types such as Laser, Missile Launcher, and TripleShot, each with unique attack patterns and costs. 
Enemies follow predefined paths, and the player must manage resources and lives to progress through five distinct levels.

Implementation Details:

The system is built on object-oriented principles, using an abstract Tower base class to ensure consistency across different defensive units. 
Projectiles and missiles use vector mathematics for accurate targeting, while collision detection is optimized to handle interactions even with fast-moving enemies. 
The game also features a custom UI for tracking money, health, and wave countdowns.

Performance and Optimization:

During development, several optimizations were implemented to maintain a smooth frame rate. 
These include an efficient cleanup routine for inactive objects and a balanced firing system for high-damage towers to prevent performance degradation during large waves.

Technologies:

Language: JavaGraphics: JavaFX
Data Management: External Text Files
Concepts: OOP, Game Loops, Vector Normalization
