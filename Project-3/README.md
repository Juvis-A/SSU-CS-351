# Project 3 – WebGL Shapes

**Name:** Jovani Alvarez  
**Course:** CS 351  
**Project:** Project-3

---

## Overview
In this project various shaped were made using WebGL using vertex and fragment shaders. each succesive file builds on the previous.

---

## Versions of the Program

### 1. Wireframe Triangle  
[triangle.html](triangle.html)  
A triangle made using VertexID and drawn with gl.Line_loop

### 2. 10-Sided Filled Polygon  
[polygon.html](polygon.html)  
a 10 sided polygon made using gl.TRIANGLE_FAN and a uniforn N variable to generate a filled 10 sided polygon

### 3. Five-Pointed Star  
[star.html](star.html)  
Alternates the vertex radius using `mod(gl_VertexID, 2)` to create a star shape.  

### 4. Rotating Star  
[rotating_star.html](rotating_star.html)  
uses time based variable "t" to rotate the star by using "t" into vertex angle


