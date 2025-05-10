---
title: "Computer Graphics and Visualization (ENCT 201) - BEI II/I Syllabus"
description: "Detailed syllabus for Computer Graphics and Visualization (ENCT 201), a second year, first part subject in the IOE BEI program."
draft: false
image: "/images/syllabus/electronics-syllabus.jpg"
---

**Lecture**: 3  
**Tutorial**: 1  
**Practical**: 3  
**Year**: II  
**Part**: I  

### Course Objectives
The objective of this course is to provide basic principles and their applications to computer graphics and visualization. After completion of this course, students will be able to understand geometric transformations and their applications, two-dimensional and three-dimensional object modeling techniques, rendering techniques, animation and get an overview of the latest trends in computer graphics.

---

### 1. Introduction and Application (4 hours)
- History of computer graphics
- Overview of graphic systems
  - Video display devices: Raster‐scan displays, random-scan displays, flat panel displays, three-dimensional viewing devices
  - Graphics software and tools: Coordinate representations, graphics functions, software standards, PHIGS workstations, DirectX, OpenGL, WebGL, Maya, Blender, Unity
- Graphics pipeline
  - Two‐dimensional (2D) viewing pipeline
  - Three‐dimensional (3D) viewing pipeline
- Applications in various fields like medicine, engineering, art, uses in augmented and virtual realism

---

### 2. Raster Graphics and Algorithms (9 hours)
- Rasterizing a point
- Rasterizing a straight line: DDA line algorithm, Bresenham’s line algorithm
- Rasterizing a circle and an ellipse: Mid‐point circle and ellipse algorithm
- Scan-line polygon fill algorithm
- Scan-line fill of curved boundary areas
- Boundary-fill algorithm
- Flood-fill algorithm
- Point clipping
- Line clipping: Cohen‐Sutherland line clipping, Liang‐Barsky line clipping
- Polygon clipping: Weiler-Atherton polygon clipping
- Text clipping

---

### 3. 2D and 3D Coordinate Systems and Viewing Transformations (9 hours)
- 2D transformation: Translation, rotation, scaling, reflection, shear
- 2D composite transformation
- Window-to-viewport coordinate transformation
- 3D display methods: Parallel projection, perspective projection
- 3D transformation: Translation, rotation, scaling, reflection, shear
- 3D composite transformation
- Projection and viewing transformation

---

### 4. Curve Modeling and Surface Modelling (4 hours)
- Introduction to parametric cubic curves, splines, Bezier curves
- Surface modeling (Polygon surface, vertex table, edge table, polygon table, surface normal and spatial orientation of surfaces)

---

### 5. Visible Surface Determination (4 hours)
- Image space and object space techniques
- Back face detection, Z‐Buffer, A‐Buffer, Scan‐Line method

---

### 6. Illumination and Surface Rendering Methods (4 hours)
- Algorithms to simulate ambient, diffuse and specular reflections
- Constant, Gouraud, Phong and Fast Phong shading models

---

### 7. Computer Animation and Visualization (5 hours)
- Computer animation functions
- Raster animations
- Key-frame systems
- Motion specifications: Direct-motion specifications, goal-directed systems, kinematics and dynamics

---

### 8. Latest Trends in Computer Graphics (6 hours)
- Interactive visualization
- Distributed scene rendering
- Augmented reality (AR), virtual reality (VR) and mixed reality (MR)
- Game development and real-time graphics
- Applications of AR, VR and gaming

---

### Tutorial (15 hours)
1. Computations regarding raster graphics system- frame buffer size, color manipulation techniques, aspect ratio, refresh rate, resolution
2. Implementation of studied algorithms to determine points for digitizing lines, circles, and ellipses
3. Computational problems related to different clipping algorithms
4. Solution of problems related to 2D and 3D transformations and matrix compositions, including fixed-point scaling, pivot-point rotation, and reflection across an arbitrary line, among others
5. Transformation of object descriptions from the window coordinate system to the viewport coordinate system and solving problems related to parallel and perspective projection
6. Calculation of the points required to construct different curves studied using the specified set of control points and the desired number of line segments
7. Calculation of the surface normal of polygons and evaluating visibility using various visible surface determination techniques
8. Calculation of average intensity at a point on a polygon using Gouraud shading

---

### Assignment
Appropriate assignment problems are given to students after the completion of each chapter.

---

### Practical (45 hours)
1. DDA line algorithm
2. Bresenham’s line algorithm
3. Mid-point circle algorithm
4. Mid-point ellipse algorithm
5. Lab on 2‐D transformations
6. Lab on 3-D transformations
7. Program for viewing and shading the 3D object
8. Clipping hidden surface removal
9. Implement the discrete techniques
10. Basic drawing techniques in OpenGL
11. A simple computer animation
12. A simple AR/VR scene or application using a framework (e.g., Unity, ARKit, Unreal Engine)

By the end of the practical, students are required to develop a prototype project to demonstrate their understanding of computer graphics concepts. Students will work in teams and are encouraged to explore new programming languages or platforms (e.g., Unity, Unreal Engine, WebGL) to complete their project.

---

### Final Examination
| Chapter | Hours | Marks Distribution* |
|---------|-------|---------------------|
| 1       | 4     | 5                   |
| 2       | 9     | 13                  |
| 3       | 9     | 13                  |
| 4       | 4     | 5                   |
| 5       | 4     | 5                   |
| 6       | 4     | 5                   |
| 7       | 5     | 7                   |
| 8       | 6     | 7                   |
| **Total** | **45** | **60**             |

*There may be minor deviation in marks distribution.*

---

### References
1. Hearn D., Baker, M. P. (1997). Computer Graphics C version (2nd edition), Prentice Hall.
2. Theoharis, T., Papaioannou, G., Platis, N., Patrikalakis, N. M. (2008). Graphics and Visualization: Principles & Algorithms. United States: CRC Press.
3. Foley, J. D. (1995). Computer Graphics: Principles and Practice in C (2nd edition). Germany: Addison-Wesley.
