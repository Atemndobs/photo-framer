# Image Profiler

A web-based tool for creating circular profile pictures with customizable borders and effects.

## Features

- Upload any image to create a circular profile picture
- Adjustable frame size (100px to 500px)
- Customizable border thickness (up to 50px)
- Border color and transparency controls
- Gradient border support
- Image cropping and zoom functionality
- Drag to reposition image within frame
- Download as high-quality PNG

## Usage

1. Open the app in your browser
2. Click "Choose File" to upload an image
3. Use the controls to customize:
   - Frame Size: Adjust the overall size of the profile picture
   - Border Thickness: Set the border width
   - Border Transparency: Adjust border opacity
   - Border Gradient: Choose border color
   - Crop Zoom: Zoom in/out of the image
4. Drag the image to position it within the frame
5. Click "Download as PNG" to save your profile picture

## Customization Options

- **Frame Size**: 100px - 500px
- **Border Thickness**: 0px - 50px
- **Border Transparency**: 0 (fully transparent) to 1 (fully opaque)
- **Border Gradient**: Any color via color picker
- **Crop Zoom**: 1x - 3x magnification

## Technical Details

- Built with HTML5, CSS3, and JavaScript
- Uses Canvas API for image processing
- FileReader API for image uploads
- Responsive design works on all screen sizes

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- JavaScript enabled

## How to Start

1. Clone the repository:
   ```bash
   git clone git@github.com:Atemndobs/photo-framer.git
   ```
2. Open the project directory:
   ```bash
   cd photo-framer
   ```
3. Run the application using one of these methods:
   - **Direct file access**:
     ```bash
     open index.html
     ```
   - **Python HTTP server**:
     ```bash
     python -m http.server 8000
     ```
     Then open http://localhost:8000 in your browser
