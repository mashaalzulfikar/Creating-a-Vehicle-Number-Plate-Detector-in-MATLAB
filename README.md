# Creating a Vehicle Number Plate Detector in MATLAB

This project provides an automated solution for detecting and extracting vehicle license plate numbers from images using Digital Image Processing (DIP) techniques in MATLAB.

## Features
- **Image Acquisition & Pre-processing**: Grayscale conversion and noise reduction.
- **Edge Detection**: Horizontal and vertical edge processing to locate plate boundaries.
- **Segmentation**: Isolates the region of interest (license plate) from the vehicle image.
- **Algorithm**: Implemented using MATLAB R2013a with custom edge processing histograms.

## Requirements
- MATLAB R2013a or newer.

## How to Run
1. Clone this repository.
2. Open the project folder in MATLAB.
3. Ensure your sample images (e.g., `CAR2.jpg`) are in the directory.
4. Run the `main.m` script.

## Methodology
The algorithm follows these core steps:
1. Capture Input Image
2. Extract Y component (Grayscale conversion)
3. Noise Removal
4. Dilation Morphology
5. Horizontal and Vertical Edge Processing
6. Segmentation
