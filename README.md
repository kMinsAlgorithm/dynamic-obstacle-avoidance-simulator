# Dynamic obstacle avoidance simulator

This simulation environment was used for training and testing in [HADP: Hybrid A*-Diffusion Planner for Robust Navigation in Dynamic Obstacle Environments](https://kminsalgorithm.github.io/HADP.html).

It requires the [gazebo_sfm_plugin](https://github.com/robotics-upo/gazebo_sfm_plugin) to run.  

As I know, the plugin is currently only available for ROS1, but an improved ROS2-compatible version will be released in the future.

The environment includes four scenarios, each designed to reflect various dynamic obstacle situations that may occur in real-world autonomous navigation:


- **Straight World (6 pedestrians)** – Typical pedestrian avoidance scenario in an open space.  
- **U-Corridor World (4 pedestrians)** – Pedestrian avoidance in a corridor and corner environment.  
- **Crowd World (31 pedestrians)** – Pedestrian avoidance in a dense crowd scenario.  
- **Intermediate-Wall World (25 pedestrians)** – Pedestrian avoidance in the presence of static obstacles.
