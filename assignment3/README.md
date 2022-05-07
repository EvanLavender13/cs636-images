# CS636 - Advanced Rendering Techniques
## Assignment 3

## Configuration
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
- number of lights
    - ambient light value
    - followed by a list of:
        - type (not used currently)
        - intensity
        - location
- number of objects
    - followed by a list of:
        - type (0 = mesh model, 1 = sphere)
        - model file path or sphere radius
        - diffuse coefficient
        - spectral coefficient
        - ambient coefficient
        - shininess factor
        - color
        - location
        - rotation
        - scale

## Images
All images are `512x512` resolution.

## Bounded Volume Hierarchy

images/scene_bvhtest0.png | images/scene_bvhtest10.png
--- | ---
![](images/scene_bvhtest0.png) | ![](images/scene_bvhtest10.png)