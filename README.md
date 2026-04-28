# Broken Biscuit Detection using Classical Image Processing

## Problem Description
This project detects biscuits in images and classifies them as either **Intact Biscuit** or **Broken Biscuit**.

The program uses classical image processing techniques to detect biscuit regions, analyze their shapes, and add labels to the output images. 
Machine learning and deep learning methods were not used in this project.


## Dataset
The dataset contains images of **round biscuits** and **square biscuits** placed on white A4 paper.

The images include both intact and broken biscuits. Each image contains multiple biscuits arranged in different positions.

Input images are stored in the `input_images` folder.

## Tools and Libraries
- Python
- OpenCV
- NumPy
- Jupyter Notebook

## Methods Used
The following classical image processing methods were used:

- Image resizing
- Color detection using HSV
- Color thresholding
- Morphological operations
- Contour detection
- Shape analysis
- Rotated bounding box analysis for square biscuits

## How to Run
1. Open Anaconda Prompt
2. Activate environment:  conda activate ee4216
3. Run Jupyter Notebook
4. Open biscuit_detection.ipynb
5. Run all cells

## Output
Images are saved in output_images folder with labels:
- Intact Biscuit
- Broken Biscuit


