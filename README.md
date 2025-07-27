# Portfoilo 


<h2 align="left">Education</h2>

<div align="left">

<table>
  <tr>
    <th>Qualification</th>
    <th>Course</th>
    <th>Institution</th>
  </tr>
    <tr>
    <td>Bachelor's Degree</td>
    <td>Robotic System</td>
    <td>Singapore Insitution of Technology<br><em>(Currently Undergoing)</em></td>
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
![Limo Robot](image/Limo.jpg)<br>
In this project, our group utilized the Limo robot as the main robotic platform to explore autonomous navigation in complex environments. To enable the robot to perceive and understand its surroundings, we implemented RTAB-Map (Real-Time Appearance-Based Mapping), a robust SLAM (Simultaneous Localization and Mapping) solution. RTAB-Map allowed the Limo robot to create and update detailed 3D maps of the environment in real time, facilitating accurate localization and environmental awareness.

For autonomous movement, we integrated the ROS navigation stack, which relies heavily on route planning supported by global and local costmaps. The global costmap provides a broad, high-level representation of obstacles and free space across the entire mapped area, enabling strategic route planning to find the optimal path from the robot’s current position to its goal.

The local costmap focuses on the immediate vicinity around the robot and dynamically incorporates sensor data to detect and avoid obstacles in real time. An important aspect of the navigation setup is the management of clearance—the safe spacing between the planned route and nearby walls or obstacles. This clearance is configured within the costmaps and navigation parameters to ensure the robot maintains a safe distance from obstacles, reducing collision risk and allowing smooth navigation even in narrow or cluttered environments.

By combining real-time mapping, dynamic obstacle avoidance, route planning, and clearance management, our system enables the Limo robot to navigate efficiently and safely.

All software development was conducted primarily using Python, leveraging its strong integration with ROS for sensor data processing, motion control, mapping, localization, route planning, obstacle avoidance, and clearance management.
#### Area Environment
