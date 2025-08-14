# My First Extension - STC-DEV-101: Slicer Scripting and Module Development

This repository contains the code developed for the **STC-DEV-101: Slicer Scripting and Module Development** tutorial in 3D Slicer. The main goal of this exercise was to create a module that positions a spherical model using two markup points.

## How to Use

1. Open the **Center of Mass** module from the Slicer modules menu.
2. In any 2D or 3D Slicer view, use the markup placement tool (Fiducials) to add two points to the scene.
3. In the **Input Markups** section, select the node containing the points you just created.
4. Click the **Apply** button to generate the sphere.
5. The sphere will appear at the center of mass of your points, with its size determined by the distance between the first two points.
6. To see real-time updates, check the **Auto Update** box.

## Clone the repository:
 ```bash
 git clone https://github.com/mdlv0/Slicer-MyFirstExtension.git
