Description of the Rubik's Cube Code
Class RubikCube:

Initialization (__init__): Creates a 3x3 Rubik's Cube with default colors for each face (White, Yellow, Green, Blue, Orange, and Red).
Method display: Displays the current state of the cube in the console, printing each face and its colors.
Face Rotations: Methods rotate_face_clockwise and rotate_face_counterclockwise rotate the cube's faces in the clockwise and counterclockwise directions, respectively.
Movement and Resolution:

generate_move_table: Generates a precalculated move table using the cube's initial state and applying various moves.
apply_move: Method to apply a specific move to the current cube state; implementation details are still needed.
solve_rubiks_cube: Uses the Kociemba library to solve the cube based on a string representing its state.
Solution Search:

bfs (Breadth-First Search) and dfs (Depth-First Search): Implementations of search algorithms that look for a solution to reach a goal state from a start state, using sets to track visited states and avoid cycles.
Advanced Resolution Methods:

make_cross, f2l, oll, and pll: Planned methods to implement the CFOP technique for solving the cube, though currently empty.
Usage Example:

The code includes a block that shows how to initialize the cube, rotate faces, solve it using Kociemba, and apply search algorithms.
Important Notes:

The logic in apply_move needs to be implemented for proper functionality; it currently does not update the cube's state.
Advanced resolution methods should be completed for effective cube solving.
