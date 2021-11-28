# Battleship
Battleship game created in Pygame Zero

Based on the Battleship game featured in Beginning Game Programming with Pygame Zero:

[Book Beginning Game Programming with Pygame Zero - Apress / Springer](https://link.springer.com/book/10.1007/978-1-4842-5650-3) 

This is simple battleship game, where you have to outsmart the computer by sinking all their fleet first.

This has now been developed further. It supports two different screen sizes. To enable small screen size (used for pip) then update battleship.py with 

```SIZE_SML = True```

For a large screen size update battleship.py with

```SIZE_SML = True```

To run 

```python3 battleship.py ```

## Game play

First you need to position your ships on your grid on the left. The ship will be placed where your cursor is. It will show a rectangle showing the approximate position of the ship. 

After placing your ships you fire shots at the enemy grid on the right. Take it in turn to fire shots with your enemy. Misses are marked with a splash and hits with an explosion. Once an entire ship is destroyed it will become visible. 

The first person to destroy all the enemy ships will be the winner. 

To exit press Q on a keyboard. 

## Work in progress / support for the pip

This is currently work in progress. In particular I am currently making some changes so it can work with the pip Raspberry Pi based handheld games console. 

You will need a keyboard and mouse connected at the moment, but I plan to change that in future.

## More information
See the project website: 

[Battleship Python Pygame Zero Game by PenguinTutor](http://www.penguintutor.com/projects/battleship) 
