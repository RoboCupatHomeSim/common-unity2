> [!NOTE]
> This repository is for ROS 2.


# Common Unity Project

This is a common Unity project for the RoboCup@Home Simulation competition.  
Open this project in Unity and export the required assets as a .unitypackage. Then import the .unitypackage into each task's Unity project.

This project is only for generating the common assets. Any of the competition tasks cannot be run in this Unity project.

For the Unity version and other requirements, please refer to the [overview](https://github.com/RoboCupatHomeSim/overview) repository.

See also [wiki page](https://github.com/RoboCupatHomeSim/common-unity2/wiki).

## How to Make a Common Unitypackage

1. Open this project with Unity.
1. Click [Assets]-[Export Package...].
1. Check only the "Competition" and "SIGVerse" folders, and uncheck everything else.
1. Click [Export...] button.
1. Type a file name (e.g. robocup-common) and save the unitypackage file.
