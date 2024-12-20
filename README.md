# Y sub zero's Egg Roll

## Synopsis
In this game, you are given a grid of objects. Each object is represented by an emoji on the grid. Your task is to roll the eggs in the grid to a nest in the grid.  
Each nest in the grid can only fill 1 egg. Eggs will stop if they hit a filled nest or a brick. Eggs will break if they hit the pan.  

Brick = 🧱  
Egg = 🥚  
Green = 🟩  
Nest = 🪹  
Done = 🪺  
Pan = 🍳  

You are only given a set amount of moves to roll the eggs into the nests.

## Loading the Game
To load the game, follow these steps:
1. Navigate to the project directory.
2. Open your terminal and enter the following command:
```
python main.py
```
## Level files
Level files have the filename extension of `.in`. Level files come in the format of:  
```
ROWS
MAX_MOVES
LEVEL_DATA
```
The first line is the number of rows, which will determine how many rows of LEVEL_DATA will be read. The remaining rows will not be read so input the number of rows in your level correctly.  
The next line is the number of maximum moves, which will determine how many moves the player will be able to input before he runs out.  
The following lines are the level data itself, which are a grid of emojis.  

This repository contains 3 sample levels for you to enjoy. They are all located in the levels\ directory, and all custom levels must be placed inside that directory to function.

## Controls
- **F**: Roll the eggs upwards on the grid.
- **B**: Roll the eggs downwards on the grid.
- **L**: Roll the eggs leftwards on the grid.
- **R**: Roll the eggs rightwards on the grid.
- **undo**: Undo your previous move.
- **help**: Display all available commands.

**Note:** Commands are case-sensitive.

You **CAN** combine instructions into one string to do multiple operations in one command.  
Press **ENTER** after inputting your desired instructions to ensure that your instructions are read by the program.

## Scoring
You are given 10 points for each egg rolled into the nest, plus bonus points for each move left on that move.  
You lose 5 points for each egg that gets destroyed by a pan.

## Dependencies
Python 3.13  
sys, os and time

# THANK YOU!
```
I am
                                                                                         
`YMM'   `MM' .M"""bgd `7MMF'   `7MF'`7MM"""Yp, MMM"""AMV `7MM"""YMM  `7MM"""Mq.    .g8""8q.   
  VMA   ,V  ,MI    "Y   MM       M    MM    Yb M'   AMV    MM    `7    MM   `MM. .dP'    `YM. 
   VMA ,V   `MMb.       MM       M    MM    dP '   AMV     MM   d      MM   ,M9  dM'      `MM 
    VMMP      `YMMNq.   MM       M    MM"""bg.    AMV      MMmmMM      MMmmdM9   MM        MM 
     MM     .     `MM   MM       M    MM    `Y   AMV   ,   MM   Y  ,   MM  YM.   MM.      ,MP 
     MM     Mb     dM   YM.     ,M    MM    ,9  AMV   ,M   MM     ,M   MM   `Mb. `Mb.    ,dP' 
   .JMML.   P"Ybmmd"     `bmmmmd"'  .JMMmmmd9  AMVmmmmMM .JMMmmmmMMM .JMML. .JMM.  `"bmmd"'   
                                                                                              
and I did this for fun.
                                                                                          
                                                                                          
                                                                                          
        -%@@@%%%%%%%@@@%%#*+=-:                                                           
       *@+               .:-=+#%@#+-.                                                     
     -@%:                        .-+#%#+:                                                 
    *@+                               .=#@#=.                                             
  =@#.                                    :+%#=.                                          
.#@=                                         :+@%=                                        
@#.                                             -#@*:                                     
-                                                 .+%#-                                   
                                                     -%@=                                 
                                       %+              -%%-                               
                                       =%#+:             -%%:                             
                                         :=@@#=:           +@*                            
                                           .%@##%#+-.       .#@-                          
                                             +@*..-+#@#+-.    =@+                         
                                              .+@#=   +@%%@*=: -@#                        
                                                 :*%%+-@%- :+@+ .%#                       
                                                    .=*@@@+:+@-  .@%                      
                                                        .-+%@#    :@*                     
                                                          :@*      =@=                    
                             %@%*=-.                                #@.                   
                            :@=.:=*#%#*=:                           .@*                   
                            :@=      .-+#@%*-.                       *@:                  
                            :@=           .-*%%*-.                   :@*                  
                            .@+               .-+%%*-                 %@                  
                             @*                   .-*@#+.             =@-                 
                             #@                       :+%%+:          .@+                 
                             =@:                         .=#%+:        %%                 
                              @*                            .=%%+.     *@                 
                              +@:                              :+%#-   =@:                
                               %@                                 -#@+.:@+                
                               :@*                                  .+@%@#                
                                =@=                                    -*=                
                                 +@-                                                      
                                  *@-                                                     
                                   +@=                                                    
                                    =@+                                                   
                                     -@#.                                                 
                                      .#@-                                                
                                        =@#.                                              
                                          +@*:                                            
                                            +%%=.                                         
                                              :+#%*=:                                     

```