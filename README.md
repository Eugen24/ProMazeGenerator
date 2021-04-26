#### Unity ProMazeGenerator v0.1
- Generates a random perfect maze with given width and height data using "Recursive backtracker" algorithm each time.

#### What is Recursive-backtracker Algorithm?
## The depth-first search algorithm of maze generation is frequently implemented using backtracking what:
- Make the initial cell the current cell and mark it as visited.
- While there are unvisited cells.
- If the current cell has any neighbours which have not been visited.
- Choose randomly one of the unvisited neighbours wall.
- Push the current cell to the stack.
- Remove the wall between the current cell and the chosen cell.
- Make the chosen cell the current cell and mark it as visited.
- Else if stack is not empty, Pop a cell from the stack and make it the current cell.

#### Utils
- Generate a random maze each time by setted rows and columns fields in Inspector.
- Modular Changeable Wall object as prefab.
- Camera Top View auto sizeable by Generated Maze Size.