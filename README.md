# Home Rover Project
## About the project
Open source hobby project to create a robot with an orginial structure that moves in a home environment.

The robot structure is a double sided inverted pendulum, with the ability to stand up switching from flat mode (car) to the standing mode (balancing robot), on each of its sides. Further dynamic behaviors to be expected.

This project won't be limited to a single design, rather open to a try and fail approach with multiple design paths.

## Topics of interest
* Robot Pyhsics simulation
* BLDC motors identification and simulation
* Motors control (Vesc, Open loop, Current loop, custom controllers)
* On board computer (ESP32, ESP-IDF)
## Gazebo
* [Github repo for gazebo model, plugins and simulation environment](https://github.com/Roblibs/gzrover)

## Fusion 360
* [Fusion CAD model](http://a360.co/2x9UzpX)

## Concept
<p align="center">
  <img src="doc/side view.png" width="350" title="rover robot concept side view" alt="rover robot concept side view">
  <br>Side view of the robot. It has a main body and articulated limbs, each of them is wheeled for articulated locomotion.
</p>

<br>

<p align="center">
  <img src="doc/limb concept.png" width="350" title="limb concept" alt="limb concept">
  <br>Each limb has a motor for the wheel and for the articulation.
</p>

<p align="center">
  <img src="doc/gazebo sim stand.png" ref="https://www.youtube.com/watch?v=AlXYAZM_Tuc&feature=youtu.be" target="_blank" width="350" title="gazebo sim stand" alt="gazebo sim stand">
  <br>Youtube video from the gazebo simulation.
</p>

## Licensing
This project is open to contributions, fork and reuse in any sort of projects. Third party Subsets are subject to their own licensing.
