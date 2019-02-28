Overview

In this project, we need to implement a path planning algorithms to drive a car on a highway on a simulator provided by Udacity(the simulator could be downloaded here). The simulator sends car telemetry information (car's position and velocity) and sensor fusion information about the rest of the cars in the highway (Ex. car id, velocity, position). It expects a set of points spaced in time at 0.02 seconds representing the car's trajectory. The communication between the simulator and the path planner is done using WebSocket. The path planner uses the uWebSockets WebSocket implementation to handle this communication. Udacity provides a seed project to start from on this project (here).
Prerequisites

The project has the following dependencies (from Udacity's seed project):

    cmake >= 3.5
    make >= 4.1
    gcc/g++ >= 5.4
    libuv 1.12.0
    Udacity's simulator.

For instructions on how to install these components on different operating systems, please, visit Udacity's seed project. As this particular implementation was done on Mac OS, the rest of this documentation will be focused on Mac OS. I am sorry to be that restrictive.

In order to install the necessary libraries, use the install-mac.sh.

