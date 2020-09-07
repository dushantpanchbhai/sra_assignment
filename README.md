# Obstacle-Avoidance-Using-Ros-Gazebo

## Table of Contents

* [About the Project](#about-the-project)
  * [Tech Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Results and Demo](#results-and-demo)
* [Future Work](#future-work)
* [Troubleshooting](#troubleshooting)
* [Contributors](#contributors)
* [Acknowledgements and Resources](#acknowledgements-and-resources)
* [License](#license)

## About The Project

### Tech Stack
Technologies used for this project:
* [ROS](https://www.ros.org/)  
* [Gazebo](http://gazebosim.org/)  

### File Structure


## Getting Started
1. Clone this repository.
2. Launch your terminal and run the command `roslaunch my_worlds <world_name>.launch`. 
   This will launch the gazebo environment.
3. In another terminal, run the command `roslaunch my_robot_urdf robot.launch`. 
This will load the dd robot in the gazebo environment at the origin.  
4. In another terminal run `rosrun motion_plan OA.py`. This will start the robot and obstacle avoidance algorithm.

## Prerequisites  
* [ROS](http://wiki.ros.org/kinetic)  
* [Gazebo](http://wiki.ros.org/gazebo_ros_pkgs)

### Installation
Clone the repo
```sh
git clone https://github.com/Git-Saurabh5/Obstacle-Avoidance-Using-Ros-Gazebo.git
```
## Results and Demo
### GIF
![](https://github.com/Git-Saurabh5/Obstacle-Avoidance-Using-Ros-Gazebo/blob/master/Visuals/oa.gif)
### Video
[Obstacle Avoidance](https://youtu.be/btZGbhEyh00)

## Future Work
- [ ] Motion Planning Algorithm
- [ ] Path Planning Algorithm

## Troubleshooting
* Common errors while configuring the project

## Contributors
* [Saurabh Suresh Powar](https://github.com/Git-Saurabh5)

## Acknowledgements and Resources
* [SRA VJTI](https://github.com/SRA-VJTI)
* Reference for achieving this :
   * [ROS wiki](http://wiki.ros.org/ROS/Tutorials)
   * [Gazebo](http://gazebosim.org/tutorials)
   * [The Construct](https://www.theconstructsim.com/ros-projects-exploring-ros-using-2-wheeled-robot-part-1)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
