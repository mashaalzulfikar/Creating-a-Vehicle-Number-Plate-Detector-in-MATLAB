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
1. [cite_start]Capture Input Image [cite: 374, 375]
2. [cite_start]Extract Y component (Grayscale conversion) [cite: 376, 377]
3. [cite_start]Noise Removal [cite: 378, 379]
4. [cite_start]Dilation Morphology [cite: 380, 381]
5. [cite_start]Horizontal and Vertical Edge Processing [cite: 385, 387, 408]
6. [cite_start]Segmentation [cite: 389, 390]
