# Project 5
## Implementation / Features you added
-Controlled with WASD and mouse
-Added enemies that 'charge' at the player once they get within a certain proximity of them
  -Enemies can't track player during charge or remember player position
  -Enemies also house a light source
-No score system, only an HP system

MAIN GOAL OF THE GAME:
  -Explore the maze to find a weapon
  -Once weapon is found, use it to eliminate all enemies
  -Once all enemies eliminated, a door will open to the exit, letting the player leave
  
Unique Features:
  -Added Fog
  -Made an I-Frame system that gives you invulnerability from enemy damage for 1.5 seconds after getting hit, as well as letting you pass through enemies
  -You can visually see the hammer when you pick it up, hammer made of two cylinders with 2 materials
  -Hammer has unique 'swing' system:
    -0.15 through 0.25 seconds after click, checks via raytrace if there is an enemy within 2 units of player's forward position. If so, enemy gets deleted.
    -There is a 0.5 second cooldown from when you click to when you can attack with the hammer again
  -Instructions displayed via progression (i.e. displays new information/task when one task is completed)

## References
n/a
## Future Development
n/a
## Created by
Ethan Brock
