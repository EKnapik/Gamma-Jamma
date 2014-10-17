Gamma-Jamma
===========

Game jam game

I have never done a program in Monogame before this project.
After this I feel much more comfortable using the Monogame framework and plan to do some more
projects in monogame using raytracing/raycasting. I feel that the 48hr. Game Jam is idea and definately should be done
in the future.

The idea of the game was very simple. Pipes degrade behind you as you progress through a maze.
The key parts of this were:
  The pipe degredation (I use the timer class)
  The collision detection of being within the tubes and where you could move (this needs to be looked at again)
  How to display the sprites so that you can only see part of the screen as you move (A sprite masking layer was used)
  How to load puzzles into the game (just a simple read in from a text file, I did find that the way I read in and the way
    the pipe collision detection works I have to have a 0 buffer around the outter edge of the puzzle, this limits the
    player from going off screen but also makes it have smaller maps, something to fix in the collision detection more than
    anything)
