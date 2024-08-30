# UAS Operation Education Documentation

This document serves as a suggestion for UAV Educational Resources an individual should take to get started in research in UAS. This document is laid out in a way we suggest you follow, starting from the prerequisite requirements. The section “Mission-specific task” is listed to suggest a few useful tools to tackle specific tasks required for your mission

# Prerequisites
To get started on research involving UAS, we suggest following this path to familiarize yourself with the materials needed for UAS research. We recommend following the courses in this order, depending on the nature of your research. A lot of UAS operations can be done through Python codes under a Linux-based Ubuntu environment. However, C++ language can be used for efficiency and further applications in Robotics.

Note that most autopilot source codes are written in C++, which means that any alteration done directly with the autopilot will require sufficient knowledge of the coding language. Therefore, for mission-specific tasks, sufficient knowledge in C++ will be useful for future, more advanced involvements.

Python 3 

* [The Constructsim Python 3](https://app.theconstructsim.com/courses/58)
* [Udemy Python3](https://www.udemy.com/course/complete-python-bootcamp/)
[Linux for Robotics](https://app.theconstructsim.com/courses/40 )
(Optional for early stage) [C++ for Robotics](https://app.theconstructsim.com/courses/59)

# Useful Additional Tools
[Udacity Version Control with Git](https://www.udacity.com/course/version-control-with-git--ud123)

* It is a good practice to have version control repositories when working in a team and documenting each research progress. We suggest individuals know the basics of Git to be able to work collaboratively in a research team.

[Udemy Docker](https://www.udemy.com/course/docker-kubernetes-the-practical-guide/)
[Docker](https://www.docker.com/) is a useful environment for setting up containers and images for each environment and can be applied to create a fast, repeatable environment setup. It allows containers to be built, shared, and run on any device.

# Robot Operating Software
Robot Operating Software 2 (ROS2) serves as a set of software libraries and tools for building robot applications, allowing fast, open-source tools to complete any robotic computation, including in applications to UAS operations. The official tutorial page for ROS2 humble can be found here. Please note that your ROS2 version can vary, but we recommend selecting a Long-term support version such as the ROS2 “Humble.”

ROS2:
(Highly Recommended) ROS2 Basics: [Udemy ROS2 for Beginners](https://www.udemy.com/course/ros2-for-beginners/)
This course covers all the ROS2 basic knowledge, including the introductions to nodes, topics, services, parameters, etc. This introduces you to writing your first ROS2 code for future use in communicating between UAS and various other components.

[Udemy ROS2 Applications to Gazebo/RViz](https://www.udemy.com/course/ros2-tf-urdf-rviz-gazebo/)
This course is recommended to further strengthen the knowledge of ROS2 applications in a simulator environment, introducing you to topics of TF, URDF, RVIZ, and gazebo. All of these are required to work with a simulated model, its orientation and dynamics, and the simulator environment.


# Other Mission-Specific Tasks
Path Planning and Maze Navigation with ROS2

* This course is useful to introduce multiple popular and useful algorithms in concepts, including localization, mapping, path planning, and motion planning, all of which are useful for maze application and navigation in applications with computer vision.
* [Udemy ROS2 Path Planning and Maze Solving with Computer Vision](https://www.udemy.com/course/ros2-path-planning-and-maze-solving-with-computer-vision/?deal_code=ST22OT72523&lid=&utm_campaign=230727_Student-MX_EM-Promo_Career-Milestone_T2_NEW&utm_content=udemy_braze.95b320ae6ee4cb300b238c1dbaadec95&utm_medium=Email&utm_source=email-pro&utm_term=3x1_REVIEW)

NAV2 Stack with Ros2 for basic waypoint planning

* NAV2 is a library that allows for stable perception, planning, control, localization, and visualization of robotic autonomous systems. This can be applied through ROS sensors and provide an efficient navigation behavior that is worth knowing as a base operation for Waypoint A to Waypoint B autonomous navigation.
* [Udemy ROS2- NAV2 Stack](https://www.udemy.com/course/ros2-nav2-stack/?kw=slam&src=sac) 

Gazebo

* Gazebo is a software commonly used for robotics simulations that supports connections to ROS environments. It is very useful to use Gazebo for simulations related to UAS models and software for any preventable bugs or unstable algorithms.
* [Mastering Gazebo Simulator](https://app.theconstructsim.com/courses/78)
