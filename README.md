# AlpineAscent
A chill climbing platformer game built in Pico 8. The goal behind this project was to learn the basics of game design and coding for games. It was created in December of 2020, and as of December 2021 the game has a small community of players on the [Pico 8 forums](https://www.lexaloffle.com/bbs/?tid=40791). The game can also be found on [itch.io](https://tytydavis.itch.io/alpine-ascent).

# How to play
The game can be played in-browser by following either of the links above. The Pico 8 "cartridge file" can also be downloaded from the Pico 8 forums. Additionally, the game can be found in Pico 8's Splore.


### Gameplay
The goal of the game is to jump and climb through all of the levels until you reach the flag at the top.

The green bar represents your stamina. When it reaches zero, you  cannot climb or jump. You can replenish stamina by landing, or using a green stamina coin. Collecting gold coins will increase your maximum stamina.

You will slip down when climbing on ice blocks. You cannot climb on obsidian blocks, and magma blocks will quickly drain your stamina while you climb them.

For an extra challenge, try to get to the top of the mountain without letting your stamina reach zero, or collecting all the coins, or collecting none of them!

### Controls

X/V/M- Jump (hold for higher jump)

Z/C/N - Spend stamina coin

# Planned features
* Multiple characters
* More levels (using code rather than Pico 8's map editor to store them)
* Procedurally generated levels

# Bugs
* Players occassionally clip through walls while climbing
* Players can jump off of a wall without using stamina if they input the jump in a 1-frame window (this bug will be kept in the game at the request of the community)

# 1.1 patch notes
* The character now only falls off of the bottom of a wall if they are down-climbing, making it easier to cling to the bottom of a wall from a jump.
* A timer now appears on screen while playing.
* A special message now appears if you beat the game without using any green stamina coins.
