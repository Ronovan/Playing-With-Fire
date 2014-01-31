PlayingWithFire
Ron Yehoshua
May 09, 2012

--------------
DESCRIPTION


PlayingWithFire is a game where players can drop dynamite to destroy barrels, which drop powerups, and ultimately blow up other players as well. Each player can only drop one dynamite at a time, has three lives, and gains points for killing a player. A player gets more points per kill depending on how well the player that was killed eventually ended up ranking in the whole game. There are four power-ups: Lightning (makes dynamite more powerful, larger blast radius), DropMore (for every one of these power-ups picked up, a player can drop one more dynamite at a time), Hammer (ability to step on Dynamite), and Golden Shoes (makes you move faster). The objective is to kill all the enemy player. Anyone who would want to have a good time for a little while would want to play this game.  

--------------
INSTRUCTIONS

Controls for Player 1:
Move Up: (Up Arrow)
Move Down: (Down Arrow)
Move Left: (Left Arrow)
Move Right: (Right Arrow)
Drop Dynamite: ; (Semi-colon)

Controls for Player 2:
Move Up: W
Move Down: S
Move Left: A
Move Right: D
Drop Dynamite: R 

--------------
CLASS LIST

Absolutely Necessary:
PlayingWithFire (contains main method)
MainPanel (contains WestPanel & GamePanel)
WestPanel (contains PlayerPanels proportional to the number of Players)
PlayerPanel (displays Image of Player and stats etc.)
GamePanel (this is where the game is actually being played, contains a BoundedGrid<Item>)
BoundedGrid (extends AbstractGrid implements Grid)
Player (one of the players that can be played)
Implements Interface PowerUp:
 - Lightning
 - DropMore
 - Hammer
 - GoldenShoes
Implements Interface Item
 - GridItem
Extends GridItem:
 - All PowerUps
 - Barrel (obstacle in the game that can contain a power-up and is blown up by user)
 - Dynamite (represents dynamite that can be dropped by a player)
Implements Interface Item
 - Player
 - Block (obstacle in the grid that cannot be blown up)
MenuPage (first panel that the user sees when starting the program)
Instructions (an Instructions page)
InstructionsPowerUps (second Instructions page)
EndGameScreen (the panel shown when the game ends)
DynamiteStuff (the stuff that shows when the dynamite explodes)

--------------
Responsibilities

Ron Yehoshua did everything, holla at him.







