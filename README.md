# CS 330 – 3D Desk Scene (C++ / OpenGL)
## Author: **Kain Mason**

This project was created for the SNHU CS-330 Computer Graphics and Visualization course. It demonstrates the fundamentals of 3D graphics programming using **C++ and OpenGL**, including object construction, transformations, lighting, textures, and camera movement. The final scene contains multiple custom objects that I built using geometry-generation algorithms and an organized rendering pipeline.

---

#  How to Download, Build, and Run the Project

##  1. Download the Project

###  Using the ZIP File*
1. Download the ZIP file  
2. Extract it  
3. Open the project in **Visual Studio**

###  2. Required Tools
You will need:


Visual Studio (recommended)


OpenGL (installed with GPU drivers)


GLEW


GLFW or FreeGLUT 



### 3. Build Instructions (Visual Studio)


Open the .sln file


Set configuration to:


Release


x64




Right-click the project → Set as Startup Project


Build the solution:
Ctrl + Shift + B



 ### 4. Run the Program
Run it using F5 or Start Debugging.
Default Project Controls
ActionKeyMove CameraW A S DMove Up/DownQ / ELook AroundMouseAdjust Camera SpeedMouse WheelWireframe ModeLeft / Right ArrowToggle Lights[ ] or ALT keysReset CameraR

## Project Overview
# This 3D scene includes:


Multiple custom geometric shapes


Controllable lighting system


Texture-mapped surfaces


Smooth camera controls


A complete desk environment


# Core programming components include:


Vertex array generation


Texture coordinate mapping


Shape-building algorithms


Model/view/projection transformations


Scene assembly logic

--------------------------------------------------------------------------------------------------------------------

# Enhancements Completed for CS-499 (Algorithms & Data Structures)

 
# Geometry Algorithm Refactoring


Removed duplicated vertex-generation logic


Added reusable shape-building functions


Improved mathematical precision in geometry construction


# Improved Data Structures


Replaced raw arrays with std::vector


Implemented structured containers for vertices, normals, and textures


Reduced memory risk and improved readability


 # Transformation Pipeline Cleanup


Simplified order of operations


Improved hierarchy of object transformations


Enhanced clarity between model, view, and projection steps


# Documentation & Comments


Added detailed explanations to geometry sections


Added algorithm reasoning and occasional complexity notes


Cleaned outdated or unclear comments


# Stability & Cleanup


Removed unused code


Added bounds checking


Repaired small rendering inconsistencies


