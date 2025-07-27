# Portfoilo 


<h2 align="left">Education</h2>

<div align="left">

<table>
  <tr>
    <th>Qualification</th>
    <th>Specialisation</th>
    <th>Institution</th>
  </tr>
  <tr>
    <td>Diploma</td>
    <td>System Engineering & Management</td>
    <td>Republic Polytechnic<br><em>(March 2023)</em></td>
  </tr>
  <tr>
    <td>Certificate in Higher Nitec</td>
    <td>Offshore & Marine Engineering Design</td>
    <td>ITE Central<br><em>(March 2017)</em></td>
  </tr>
</table>

</div>

## Project
### Limo Robot Navigation
Technical Skill: <strong>[ROS]</strong>  <strong>[Gazebo]</strong>  <strong>[Python]</strong>  <strong>[RtabMap]</strong> 
#### Overview
The objective of this project was to enable the Limo Robot to autonomously navigate through various environments designed by our group and others. The robot had to determine and follow the correct route through different zones using mapping, localization, and path planning techniques.
#### Limo Robot
![Limo Robot](image/Limo.jpg)
In this project, our group utilized the Limo robot as the main robotic platform to explore autonomous navigation in complex environments. To enable the robot to perceive and understand its surroundings, we implemented RTAB-Map (Real-Time Appearance-Based Mapping), a robust SLAM (Simultaneous Localization and Mapping) solution. RTAB-Map allowed the Limo robot to create and update detailed 3D maps of the environment in real time, facilitating accurate localization and environmental awareness.

For autonomous movement, we integrated the ROS navigation stack, which relies heavily on the use of global and local costmaps. The global costmap provides a high-level, long-range representation of obstacles and navigable space over the entire mapped area, which is crucial for strategic path planning. Meanwhile, the local costmap offers a short-range, dynamic view centered around the robot’s immediate surroundings, enabling quick detection and avoidance of unexpected obstacles during navigation.

Together, these costmaps enable the robot to plan efficient paths while reacting adaptively to changes in its environment, ensuring smooth and safe navigation.

All software development was conducted primarily using Python, leveraging its strong integration with ROS for sensor data processing, motion control, and algorithm implementation. Our codebase includes modules for sensor fusion, mapping, localization, path planning, and real-time obstacle avoidance — all coordinated to achieve reliable autonomous navigation.
#### Area Environment
