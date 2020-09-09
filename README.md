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
      .
      ├── git readme files                                                           # consist of images for readme file
      │   ├── image_1.png
      │   ├── image_2.png
      │   ├── laser test.mp4
      │   └── simplescreenrecorder-2020-09-06_13.55.43.mp4                          
      ├── my_robot_description                                                       # main file consist of actual code
      │   ├── CMakeLists.txt                                                            
      │   ├── configure                                                              
      │   │   └── joints.yaml                                                          
      │   ├── launch                                                                 # launch file for launching gazebo
      │   │   ├── rviz backup                                                        
      │   │   ├── rviz.launch
      │   │   ├── spawn backup
      │   │   └── spawn.launch
      │   ├── package.xml
      │   ├── rviz
      │   │   └── robotmodel.rviz                                          
      │   ├── scripts                                                                 # consits of the script code of OA and reading_laser
      │   │   ├── obstacle_avoidance.py                                                
      │   │   └── reading_laser.py                                                        
      │   ├── urdf                                                                    # urdf file for robot model
      │   │   ├── macros.xacro                                                                   
      │   │   ├── materials.xacro                                                              
      │   │   ├── plugin.gazebo                                                               
      │   │   ├── robot.urdf                                                                 
      │   │   └── sacc                                                                       
      │   └── world                                                                   # world file for manupulating world
      │       ├── ad.dae
      │       └── empty_world.world
      └── README.md



## Getting Started
1. Clone this repository in your src folder of ROS.
2. Launch your terminal and go to catkin_ws folder(workspace folder of ROS).
3. Now run the command `catkin_make` to add it to ros and then run `source ~/catkin_ws/devel/setup.bash` to build it.
4. Then enter `cd src` to go to the src directory Run the command `roslaunch my_robot_description spawn.launch`.This will launch the bot in gazebo environment.  
3. In another terminal enter src directory and run `rosrun my_robot_description obstacle_avoidance.py`. This will start the obstacle avoidance algorithm and robot will perform obstacle avoidance

## Prerequisites  
* [ROS](http://wiki.ros.org/kinetic)  
* [Gazebo](http://wiki.ros.org/gazebo_ros_pkgs)

### Installation
Clone the repo
```sh
git clone https://github.com/dushantpanchbhai/sra_assignment.git
```
## Results and Demo
### Bot image
![](/git_readme_files/image_1.png)
![](/git_readme_files/image_2.png)
### Video
* [click here](https://youtu.be/FrSkhQ49nTs)

## Troubleshooting
* Common errors while configuring the project

## Contributors
* [Dushant Panchbhai](https://github.com/dushantpanchbhai)

## Acknowledgements and Resources
* [SRA VJTI](https://github.com/SRA-VJTI)
* Reference for achieving this :
   * [ROS wiki](http://wiki.ros.org/ROS/Tutorials)
   * [Gazebo](http://gazebosim.org/tutorials)
   * [The Construct](https://www.theconstructsim.com/ros-projects-exploring-ros-using-2-wheeled-robot-part-1)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
