# Interactive 3D Graphics in WebGL: Transform Multiple object, Shading, Lighting Effect & Animation

This project is a WebGL-based 3D application that demonstrates various shading, transformation, lighting effect, texturing, animation, multiple objects rendering techniques and interactive features for computer graphics.

---

## Demo

[▶️ Download or preview demo](demo-ICG.mp4)

 [▶️ Watch Youtube Demo Video](https://youtu.be/UW7vukE7RjA?si=arQdRzSwB4Ynvrh3)

---

## Features

### 1. Shading Modes
- **Flat Shading**: Basic shading with constant color per face
- **Gouraud Shading**: Smooth shading with color interpolation at vertices
- **Phong Shading**: Advanced shading with per-pixel lighting calculation
- **Toon Shading**: Cel-shading effect with discrete color levels
- **Blinn-Phong Shading**: Modified Phong model using halfway vector
- **PBR Shading**: Physically Based Rendering for realistic materials

### 2. Lighting System
- Introduced **two distinct light sources** at different positions in the scene.
- Verified via **specular highlights** under Phong shading and **distinct colors** from each source.

### 3. 3D Transformations
Implemented transformation controls including:
- **Translation**
- **Rotation** (around X, Y, Z axes)
- **Scaling**
- **Shearing**

### 4. 3D Clipping
- Implemented **view-space clipping** along at least one axis (X, Y, or Z) for occlusion control.

### 5. Multiple Object Rendering
- Rendered **at least three objects** in the scene.
- Included **two different models**, showcasing multi-object handling.

###

- **Lighting Effects**: Color Cycle, Two Lights Interaction with RGB setting, Color Light Mixing. 
- **Texture Control**: Import, UV scale, Mapping, etc.
- **Customized Multi-Object Model Importing**
- **Animations**: Auto Rotation for Multi-Objects.

---
## Controls

### Model Controls
- Select models from the right panel
- Adjust position, rotation, and scale
- Toggle auto-rotation

### Shading Controls
- Switch between different shading modes
- Adjust material properties
- Modify lighting parameters

### Texture Controls
- Upload and apply textures
- Choose blending modes
- Adjust texture coordinates

### View Controls
- Adjust clipping planes
- Toggle panel visibility
- Resize viewport

---

### Available Models
- Teapot
- Mercedes
- Plant
- Patchair
- Mig27
- Longteap
- Kangaroo
- Fighter
- Easter
- Csie
- Church
- Car Road

## Technical Details

### Technologies Used
- WebGL for 3D rendering
- HTML5 Canvas
- JavaScript for interaction handling
- Web Audio API for audio processing
- Custom GLSL shaders for various rendering techniques

### Implementation Highlights
- Custom vertex and fragment shaders for each shading mode
- Matrix transformations for 3D model manipulation
- Texture coordinate handling for material mapping
- Real-time audio analysis for dynamic effects
- Efficient model loading and rendering pipeline

## Usage

1. Open `index.html` in a WebGL-compatible browser
2. Select desired models from the right panel
3. Choose a shading mode from the left panel with dropdown menu
4. Experiment with different controls:
   - Model rotation and positioning
   - Texture mapping options
   - Lighting parameters
   - Clipping planes

## Requirements

- Firefox web browser with WebGL support

## File Structure

- `index.html`: Main application file
- `js/`:
  - `webgl-utils.js`: WebGL utility functions
  - `utils.js`: General utility functions
  - `json.js`: JSON handling
  - `css_style.css`: Styling definitions
- `textures/`: Texture image files
- `model/`: 3D model JSON files

## Credits
Shih-Yu Lai.
This project is part of the Interactive Computer Graphics course, implementing various computer graphics concepts and techniques using WebGL. 
