# Ultimate-Tic-Tac-Toe

Rules for the game can be found at this site: 
http://mathwithbaddrawings.com/2013/06/16/ultimate-tic-tac-toe/

Implementation details : 
A tree of all the next possible moves in the game is built dynamically upto a depth of 9. A heuristic function is written to evaluate the value of a state of the board. This value is propagated upwards and so the bot chooses the most optimal move.

Heuristic Function:
This function should effectively capture the worthiness of the board. Weightage is given to the number of small baords won and number of consecutive small boards won. Occupying central spot in a small board or winning central small board also has quite some weightage to the score returned by the heuristic function. 

