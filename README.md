# TextAdventure2
Another simple TextAdventure written in python  
How to launch the game:  
-download all the files in the repository;  
-if you are using Linux or Mac, then execute the file gui_map.py in a shell;  
-if you are using windows you can import the all project in a IDE (Pycharm for example) and execute the file gui_map.py from the there.  
  
The game is very simple, you can move among the rooms to find a treasure in the castle.  
  
There are also some actions you can perform:  
-N,S,W,E,DW,UP: move in a room up,down,left or right from your position. The options DW and UP are for switch to a different plane;  
-Pickup: take an item in the room;  
-Watch: watch an item in you inventory;  
-Inventory: take a look at your inventory;  
-Combine: combine two items to get another one;  
-Examines: take a look at an artifact or a mechanism;  
-Use: use an item on another key object;  
-Save: save the game;  
-Load: load the game;  
  
NB: when you save the game, the program doesn't prompt nothing on the screen, but you create a 'savegame' file in the directory 'TextAdventure2/'.  
When you save again, you overwrite that file. make sure to not overwrite it!  
  
When you load the game, you also load all the text about the previous game: this might help you to remember how you left the game.  
