# Boxy Dots Random Bot

This is example bot for Boxy Dots project

In order for bot to work it should consist of makeTheMove method, the game state (all current moves that are made). 
Game state structure looks like this:

[  {

     'point_from_x': move.point_from_x,
     'point_from_y': move.point_from_y,
     'point_to_x'  : move.point_to_x,
     'point_to_y'  : move.point_to_y
    },
    
    {
     'point_from_x': move.point_from_x,
     'point_from_y': move.point_from_y,
     'point_to_x'  : move.point_to_x,
     'point_to_y'  : move.point_to_y
    }
    
]


The project has to have the structure

/:

     boxydotsbot.py <- the file that has the bot in it
 
          <- this file has to have a class called "bot"

So it is a list of dictonaries. 

The method should return dictonary that is the same structure as the one above.
When the class will be initialized program will pass dimensions as well.


