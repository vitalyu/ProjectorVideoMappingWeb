# 🎥 Projection Mapping Web

**[Open App](https://vitalyu.github.io/ProjectorVideoMappingWeb/app.html)**

A powerful, browser-based projection mapping tool built with WebGL. Create stunning visual projections by mapping videos, images, or camera feeds onto any surface with precise 4-corner perspective correction.

![Demo](demo.gif)

## Features

- **Multi-Layer Support** - Work with multiple layers simultaneously for complex compositions
- **Multiple Input Sources**
  - 📁 File upload (video/image)
  - 📷 Live camera feed
  - 🎨 Solid colors
- **Real-Time Warping** - Drag corner points to map your content onto any surface
- **Layer Management** - Show/hide, reorder, and delete layers
- **Keyboard Shortcuts** - Fast workflow with hotkeys
- **Fullscreen Mode** - Perfect for live presentations
- **No Installation** - Runs entirely in your browser

## Usage

1. [Open App](https://vitalyu.github.io/ProjectorVideoMappingWeb/app.html) in your browser
2. Click **+ Add Layer** to create a new projection layer
3. Choose your content source:
   - **📁 File** - Upload a video or image
   - **📷 Camera** - Use your webcam
   - **🎨 Color** - Generate a solid color
4. Drag the corner points to map the content onto your target surface
5. Add more layers as needed for complex projections

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `H` | Toggle control panel |
| `F` | Toggle fullscreen |
| `P` | Toggle corner points visibility |
| `R` | Reset active layer corners |
| `1-9` | Switch between layers |
| `Delete` | Delete active layer |

## Controls

- **Reset** - Reset corner positions to default
- **Points (P)** - Show/hide corner control points
- **Panel (H)** - Show/hide control panel
- **Fullscreen (F)** - Enter/exit fullscreen mode

## Technical Details

- Built with vanilla JavaScript and WebGL
- Uses perspective correction shader for accurate mapping
- Supports real-time video playback
- Hardware-accelerated rendering
- No external dependencies

## Browser Compatibility

Works in all modern browsers that support:
- WebGL
- MediaDevices API (for camera input)
- ES6+ JavaScript

## License

MIT License - Feel free to use for personal or commercial projects

