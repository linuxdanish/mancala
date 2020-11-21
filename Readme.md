# Mancala design 
This project is an implementation of the mancala ruleset as a practice project for different concepts.
For that reason this implementation isn't always the most direct way of accomplishing a simple game. 

## How to play
Mancala consist of a board with two rows of 6 bowls each and two large bowls at either end. 48 stones or 
marbles are divided into 4 in each bowl (minus the large scoring bowls at the end). The completely setup 
board looks like this:

+--+  +-+ +-+ +-+ +-+ +-+ +-+  +--+  
|  |<-|4|-|4|-|4|-|4|-|4|-|4|<-|  |  
|  |  +-+ +-+ +-+ +-+ +-+ +-+  |  |  
|  |                           |  |
|  |  +-+ +-+ +-+ +-+ +-+ +-+  |  |  
|  |->|4|-|4|-|4|-|4|-|4|-|4|->|  |  
+--+  +-+ +-+ +-+ +-+ +-+ +-+  +--+  

On each players turn, they select a bowl from their side of the board. Then scoop up all the stones in that 
bowl and, moving around the board counter-clockwise, deposit one stone in each bowl (including their large 
scoring bowls) until they run out of stones. 

* Moving around the board counter-clockwise, each bowl get exactly one stone.
* Players will place a stone in their large scoring bowl (scoring bowl to their right), but never in the 
  oponents.
* If their last stone is placed into their scoring bowl, then they get another turn. 
* If their last stone is placed into an empty bowl on their side of the board, they "capture" by moving the  
  the conetns of both that bowl and the one directly across the board on the opponents side into their scoring 
  bowl.
* A players score is count of stones in their scoring bowl. 
* a stone can never be taken out of the scoring bowl. 
