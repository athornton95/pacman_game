# pacman_game
MVP:
1. create a grid based game-board
2. create pacman that is controlled by arrow clicks (left, right, up, down) but moves on it's own until
you tell it otherwise (change direction or hit a wall)
	--> with an interval speed that looks like it's fluid
3. create a "wall" class, for the walls of the maze that pacman has to navigate
4. create a "points" class & connect score with whether the class changes back to the regular game board class
5. creata a "fruits" class & connect score with whether the class changes back to the regular game board class
6. create a "sensor" (if check that looks at "class" of objects -- walls, fruit, & points)
	--> if check
7. make a score keeper that increases if pacman "eats (runs into)" a point or a fruit


Above & to infinity and beyond:
1. add a ghost class and make pacman lose a life if he runs into one 
	-->  make pacman object that regenerates based on how many "lives are left" 
		a. lives are an array
		b. each time you die, a pacman is pop'ed out of the array
		c. if there is a pacman left, it regenerates
2. have fruit pop up randomly (based on a timer) in any square that has the "game-board" class
3. multiple levels with increased speed/complexity
4. winner board that will updated based on score and host the top 5 scores (i know that this feels wild.....but will also create a sort function that will rearrange the order of scores based on points and recalibrate in the 
"winners board");


![wireframe](pacman.wireframe.jpg)
