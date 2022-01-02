# robot_path_planning
Implemented Manhattan distance algorithm to navigate a mobile robot throughout workspace when the obstacles co-ordinates are pre-defined.

This code navigates a mobile robot through an obstacle course to a goal location. The start position of the robot as well as the locations of all obstacles and of the goal are
given before the robot is started.

The workspace for the robot is a rectangular area, 4.88 m x 3.05 m in size (this corresponds to exactly 16 x 10 floor tiles in the lab). 
Obstacles are black cardboard squares 0.305 m x 0.305 m in size (the size of 1 floor tile) which will be placed in the workspace. The goal is a black circle with a radius of
0.305 m. 

To simplify experiments, the center of the goal area, of the obstacles, and of the start will coincide with the intersection point of four floor tiles and their orientation will be aligned with the tiles.
