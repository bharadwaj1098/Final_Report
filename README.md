# Final_Report

## Docker

1) `source ~/robot/ghost_gazebo/ros1_simulator/docker/run_ghost_sim.bash` to spin up the docker container along with Rviz and Gazebo.

2) `docker exec -it ghost_simulator bash` to enter the container in different terminal.

3) While operating multiple instances of the same `ghost_simulator` container <a href="https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/"> `tmux` </a>is recommended.

4) Some Tmux commands have been customised for ease of use 

    1) For verticle division `ctrl + a` and `\` (not together, `ctrl + a` triggers and awaits for instruction of verticle or horizontal split).
    
    2) For horizontal `ctrl + a` and `-`(minus sign).
    
    3) To move around `right-alt + arrow keys`.
    
5) Rest of the information can be found in <a href="https://ghostusers.gitlab.io/docs/docker_reference.html">here </a>.

6) Finally to kill the container after you've excited it `source ~/robot/ghost_gazebo/ros1_simulator/docker/docker_clean.bash`

## RVIZ 

1) Getting Rviz is as simple as typing `rviz` in the terminal once the PC is connected to the robots wifi.

2) RVIZ is a powerful tool which can used to draw intercative markers around the robot, to make it interact with the world around it while also able to visualize all of the data from the cameras and sensors of the robot.

3) Rviz complements with Gazebo i.e; the same command makes the robot do exact same stuff in both gazebo and rviz in the docker container.

## Note

1) Please get access to gitlab(Ghost robotics).

2) After connecting the PC to the robot's <a href="https://ghostusers.gitlab.io/docs/network.html">wifi </a> run `roslaunch ghost_dance dance.launch`

3) Make sure to close the Ghost Application on the controller tablet while giving commands to the robot from PC. 

4) All the information on controlling the robot about it's main nodes and topics can be found <a href="https://ghostusers.gitlab.io/docs/piloting.html">here</a>.
