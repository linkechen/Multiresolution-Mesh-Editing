# Multiresolution-Mesh-Editing
## Introduction
This project presents an innovative approach to 3D model deformation using multi-resolution mesh editing, rooted in naive Laplacian editing techniques. It enables interactive deformations of 3D models through direct manipulation of vertices, offering an intuitive and efficient user experience.
### Key Features
1. Multi-Resolution Mesh Editing: Smoothly deforms 3D models by applying user-defined transformations to selected vertices, preserving the model's original details.
2. Interactive Vertex Selection: Features a user-friendly interface for selecting and manipulating vertices.
3. Algorithmic Deformation Phases: The deformation process encompasses smoothing the mesh, applying deformations, and restoring high-frequency details, ensuring a realistic output.
## Technologies and Dependencies
* libigl
* Numpy
* Meshplot
* Scipy
* ipywidgets
## Installation
You can install the required libraries using 'pip'. Open your terminal or command prompt and run the following command:
```bash
pip install numpy scipy ipywidgets
pip install git+https://github.com/libigl/libigl.git
pip install meshplot
```
 If pip not found on your computer please refer to this website https://pip.pypa.io/en/stable/installation/.
 
Note: `libigl` and `meshplot` might require specific installation steps or dependencies. Refer to their official documentation for the most accurate instructions.
## Usage
To use this Jupyter Notebook, you will need to have Jupyter installed on your system. If you do not have Jupyter installed, you can install it using pip:

```bash
pip install notebook
```
## Contribution
This project is currently maintained by me(linkechen) only.
## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this software under the terms of the license.
## Contact
If you have any questions or need support, please contact a7783222520@gmail.com.
## Demo Video
[Watch the demo video on YouTube](https://youtu.be/lWIefzIcqyI)
