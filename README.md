

Bot with Vision Radius

Description

This is a simple console-based simulation written in Borland/Turbo C++ for DOS.
A bot (*) moves around a rectangular field in search of food (o).
The bot has a vision radius: if food is within that range, the bot moves directly toward it.
Otherwise, the bot makes random steps.

When the bot reaches the food, the food respawns at a new random location.


---

Features

Console field of size 40 × 20.

Bot starts in the center of the field.

Food is placed at a random location.

Bot has a configurable vision radius (default: 3 cells).

Bot moves toward visible food, otherwise makes random moves.

Food respawns when eaten.

Run loop continues until a key is pressed.



---

Controls

The simulation runs automatically.

Press any key to stop and exit.



---

Compilation

This project is designed for Borland/Turbo C++ 3.x (16-bit DOS).

1. Open the source file in Turbo C++ IDE.


2. Compile (Alt + F9).


3. Run (Ctrl + F9).




---

Example Output

*                      
                                        
                           o            
                                        
                                        
                                        
                                        
Bot: (17,10)  Food: (26,3)

Here, * is the bot, and o is the food.


