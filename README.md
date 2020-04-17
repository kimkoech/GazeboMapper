# GazeboMapper
An autonomous occupancy grid(OG) mapper that for turtlebot2 simulated in gazebo using the ConstructSim



## Running the simulation
1. Make sure to clone your repository to the root directory of your account i.e. in the `user/` directory such that your launch and py files are in `user/gazebo-pset-4a`

1. Instantiate the world and spawn the turtlebot by launching GazeboMapper.launch file using the command below. Note the x and y specifies the position of the turtlebot in cartesian coordinates and yaw specifies the orientation of the turtlebot in radians i.e. 3.142 = 180 degrees.

`roslaunch GazeboMapper.launch x:=0 y:=0 yaw:=3.142`

1. From the burger menu launch Gazebo to view the world and the turtlelbot

1. Also launch the Graphical Tools to view OpenCV windows (when dispaling windows using your code)

1. Launch the mapping program using the command below

`python mapper.py`

