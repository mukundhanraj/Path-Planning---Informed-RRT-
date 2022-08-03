# PathPlaning

Informed RRT* algorithm was implemented to find the optimal path from start node to end node for a predefined map. Simulation was implemented on Gazebo,RViz using turtlebot-3.



In a terminal run the turtlebot3 in the world
```
roslaunch turtlebot3_gazebo assignment.launch
```

In a new terminal run the Informed RRT star algorithm
```
cd PathPlaning
python3 informed_rrt_star.py
```eefef

To see the simulation, close the matplotlib screen after the plotting is complete.<br>
You will be notified on the terminal after the simulation is completed.<br>
<br>
**Videos** folder contains two test videos of the working project<br>
test1.mp4 - start point = 60,10 - end point = 80,80 <br>
test2.mp4 - start point = 30,50 - end point = 90,90
