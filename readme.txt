#general description
This project describes the 3D dynamic particle-based model, which is able to analize mechanical properties of thrombus, and dependence of the thrombus geometry on the geometry of the vessel and the flow in the vessel.
Model is able to calculate hydrodynamic forces acting on thrombus under the condition of a constant parabolic velocity profile.  
The program is written in VisualStudio 19 ("Console App"), Windows

After compilation but Before starting the program, you need to change the "Reserved stack size" to 8388608 (that's 2^23):
Project - Configuration Properties - Linker - System - Stack Reserve Size

Change "Debug" to "Release"

The following are the lines with the main parameters:
76 - side of the square - to determine the injury area 
104 - the parameter responsible for the extent of maximum activation (it varied from 3 to 7, which gave from 145 to 580 pN)
222 - shear rate parameter (1 = 1000 1/s)
