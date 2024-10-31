
# Pencil Sketch Image Converter

## Overview
This project demonstrates how to transform a standard image into a pencil sketch using Python and OpenCV. The program reads an image file, processes it by converting it to grayscale, inverting the colors, and applying Gaussian blur to create a stunning pencil sketch effect. This conversion technique employs basic image processing operations and demonstrates the power of OpenCV for visual effects.

## Features
- **Image Reading**: Load an image using OpenCV.
- **Grayscale Conversion**: Convert the loaded image from BGR (Blue, Green, Red) to grayscale.
- **Inversion**: Invert the grayscale image to prepare for blurring.
- **Gaussian Blur**: Apply Gaussian blur to the inverted image for a smoother look.
- **Sketch Effect**: Combine the grayscale image with the inverted blurred image to produce a pencil sketch effect.
- **Visualization**: Display the original image alongside the resulting pencil sketch using Matplotlib.

## Required Libraries
- `opencv-python`
- `numpy`
- `matplotlib`

## Installation
To run this project, ensure that you have the required libraries installed. You can install them using pip:

```bash
pip install opencv-python numpy matplotlib
```

## How to Use
1. Place the image file you wish to convert in your file system.
2. Update the image path in the code:

   ```python
   img = cv2.imread('/path/to/your/image.jpg')
   ```

3. Run the script to view the original image and its pencil sketch version.

## Example
Below are examples of the original image and its corresponding pencil sketch output:

![Original Image](<path_to_original_image_placeholder>)
![Pencil Sketch](<path_to_pencil_sketch_placeholder>)
