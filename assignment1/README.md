# CS636 - Advanced Rendering Techniques
## Assignment 1

All images use the following coordinate system:
- **X** left-right
- **Y** up-down
- **Z** in-out (of screen)

Camera configuration files are formatted as follows:
- **l** location vector
- **d** direction vector
- **u** up vector
- **a** viewing angle
- **h** horizontal resolution
- **v** vertical resolution

Scene configuration files are formatted as follows:
- **m** number of mesh models
  - followed by a model file path and location vector, for each model
- **p** number of parametric models (only spheres for now)
  - followed by a type, radius, and location vector, for each model

### Scene 1
![Scene 1](scene1.png)
Camera | Scene | Image | Ray Intersect Time
------ | ----- | ----- | ------------------
`camera-003-56-512.txt` | `scene1.txt` | `scene1.png` | `13.636290`

### Scene 2
![Scene 2](scene2.png)
Camera | Scene | Image | Ray Intersect Time
------ | ----- | ----- | ------------------
`camera-007-56-512.txt` | `scene2.txt` | `scene2.png` | `0.055456`

### Scene 3
![Scene 3](scene3.png)
Camera | Scene | Image | Ray Intersect Time
------ | ----- | ----- | ------------------
`camera-007-90-512.txt` | `scene2.txt` | `scene3.png` | `0.049452`

