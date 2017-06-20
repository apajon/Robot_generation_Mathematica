# Robot_generation_Mathematica
Kinematic simulation of robot from Denavit-Hartenberg configuration with Mathematica

The code description is in french.
The report ("rapport_projet_robot_auto.pdf") is also in french.

"01_General.nb" file is like the main file of this program. It imports the function in "02_MatriceGeom.nb", "03_FormulesRobotAuto.nb" and "04_RobotAutoTotal.nb". They are like library.

"99_Robottest.nb" is an example of robot generation and what this program can do.

"99_HRP2.nb" and "99_HRP4.nb" are the generation example of HRP2 and HRP4 humanoid robot from Kawada industry and are example of complex humanoid robot generation.

TODO work:

Create a real library from imporetd functions

Optimize the robot generation for fast computation. With complex robot (HRP2 for example) it is very slow and memory consumming.