# Vehicle-Number-Plate-Detection

This project implements vehicle number plate detection using OpenCV and a pre-trained Haar Cascade Classifier (`haarcascade_russian_plate_number.xml`). The system detects the region of the number plate from an image and visualizes it with bounding boxes.

## What It Does
- Loads a car image.
- Converts it to grayscale for processing.
- Uses Haar Cascade to detect number plate-like regions.
- Draws bounding boxes around detected plates.
- Visualizes the output using Matplotlib.
