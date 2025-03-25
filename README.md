# 3D Rendering using Python 🎨✨
![Model](project_output/step_3/texture/frames/diablo3_pose/diablo3_pose_350.png?raw=true)

This repository provides a hands-on educational experience to understand the basics of 3D rendering and graphics. It uses Python to generate various rendering techniques like basic lighting, texture mapping, and the z-buffer algorithm.

The project takes 3D models and textures as input, processes them, and outputs rendered frames and animations to visualize the results.

## Project Structure 🗂️

Here’s a simplified view of the project structure:

```
project.ipynb              # Notebook with rendering logic 
│
├── gifs/                   # Rotating animations
├── models/                 # 3D .obj model files
├── project_output/         # Rendered frames
│   ├── step_1/             # Bresenham's line algorithm
│   │   └── rendered_triangles/
│   ├── step_2/             # No z-buffer rendering
│   │   ├── lighting/       # Triangles with white color and lighting
│   │   │   └── frames/
│   │   └── random/         # Triangles with random color
│   │       └── frames/
│   ├── step_3/             # Z-buffer rendering
│   │   ├── texture/        # Texture mapping
│   │   │   └── frames/
│   │   └── z_buffer/       # Basic lighting with z-buffer
│   │       └── frames/
├── textures/               # Textures for models
```
## Concepts Covered 💡

This project helps you learn about:
- **Bresenham’s Line Algorithm**: Drawing 3D triangles.
- **Lighting Models**: Simulating light on 3D objects.
- **Texture Mapping**: Applying textures to models.
- **Z-buffer Algorithm**: Handling depth in 3D rendering.

## Requirements 📋

This project uses the following Python libraries:
- `os`
- `numpy`
- `PIL` (Pillow)
- `random`
- `matplotlib`
