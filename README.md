<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Autonomous Drone-Vehicle Following System</title>
</head>
<body>

<h1>Autonomous Drone-Vehicle Following System</h1>

<details open>
  <summary><strong>Table of Contents</strong></summary>
  <ol>
    <li><a href="#about-this-repository">About This Repository</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#requirements">Requirements</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<hr>

<h2 id="about-this-repository">About This Repository</h2>
<p>
This project implements an autonomous drone system capable of following ground vehicles using computer vision and ROS2.
It utilizes the Hector drone model equipped with multiple sensors to enable obstacle avoidance, object detection, and
go-to-goal behavior within a simulated environment. The system leverages ROS2 for robotics middleware and OpenCV for
image processing and object tracking.
</p>

<hr>

<h2 id="getting-started">Getting Started</h2>
<p>To use this project, follow the steps below to set up your ROS2 workspace and build the package.</p>

<h3>Clone the Repository</h3>
<pre><code>cd ~/ros2_ws/src/
git clone --recurse-submodules https://github.com/rahulpanchall7/Autonomous-Drone-Vehicle-Following-System.git
</code></pre>

<h3>Build the Workspace</h3>
<pre><code>cd ~/ros2_ws/
colcon build
</code></pre>

<h3>Source the Workspace</h3>
<pre><code>source ~/ros2_ws/install/setup.bash
</code></pre>

<h3>Launch the Drone's Goal Behavior</h3>
<pre><code>ros2 launch drive_drone p2_go_to_goal.launch.py
</code></pre>

<hr>

<h2 id="features">Features</h2>
<ul>
  <li><strong>Autonomous Drone Following Ground Vehicles via Computer Vision</strong><br>
    <img src="https://github.com/noshluk2/ROS2-Drone-Basic-Course-for-Beginners/blob/master/Images/drone_follow_tb3.gif" alt="drone follow gif">
  </li>
  <li><strong>Dynamic Go-to-Goal Navigation</strong><br>
    <img src="https://github.com/noshluk2/ROS2-Drone-Basic-Course-for-Beginners/blob/master/Images/drone_gtg.gif" alt="go to goal gif">
  </li>
  <li>Sensor Integration with Drone Simulation</li>
  <li>Custom World and Launch Files for Simulation</li>
</ul>

<hr>

<h2 id="requirements">Requirements</h2>
<ul>
  <li><strong>Operating System:</strong> Ubuntu 22.04 LTS</li>
  <li><strong>ROS2 Distribution:</strong> Humble</li>
  <li><strong>Python:</strong> Compatible with ROS2</li>
  <li><strong>Libraries:</strong>
    <ul>
      <li>OpenCV</li>
      <li>gazebo_ros</li>
      <li>xacro</li>
    </ul>
  </li>
</ul>

<hr>

<h2 id="license">License</h2>
<p>
  This project is licensed under the GNU General Public License (GPL). See the
  <a href="LICENSE">LICENSE</a> file for more information.
</p>

</body>
</html>
