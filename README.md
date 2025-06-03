# Robot-Return-to-Origin

This solution determines whether a robot, starting at the origin (0,0) on a 2D plane, returns to its original position after executing a series of moves. The moves are represented as a string consisting of the characters 'U' (up), 'D' (down), 'L' (left), and 'R' (right), each indicating a movement by one unit in the respective direction.

The algorithm tracks the robot’s position by maintaining two counters for the x (horizontal) and y (vertical) coordinates. For each move, it updates the coordinates accordingly:

'U' increments the y-coordinate by 1.

'D' decrements the y-coordinate by 1.

'L' decrements the x-coordinate by 1.

'R' increments the x-coordinate by 1.

After processing all moves, if both x and y coordinates return to zero, the robot has returned to the origin, and the function returns True. Otherwise, it returns False.
