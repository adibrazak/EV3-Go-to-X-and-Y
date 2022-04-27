# EV3-Go-to-X-and-Y
EV3 LEGO® Mindstorms® was programmed using Eclipse with c4ev3 software package to move from a start position to a target position on a predefined map.
There are two movement type of the EV3; restricted by the lines drawn on the map and taking shortest path.

Robot was programmed as follows:
1. Request user the movement type to be used; either line restricted movement or shortest path movement. 
2. Request user the target position by getting the x value and y value as the target coordinate (x,y).
3. Up button will increase input value, Down button will decrease input value. 
4. The value for x and y are restricted based on the predefined map, which in this case 0~4 for x, and 0~3 for y.
5. EV3 will move to user target position with the chosen movement type.


The program is written in **C/C++** using **Eclipse** with **c4ev3** software package.
Link for references on c4ev3
https://c4ev3.github.io/


EV3 demonstration
https://www.youtube.com/watch?v=AgZIlj-H2zY
