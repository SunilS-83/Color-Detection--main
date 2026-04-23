# Color Detection Project

## Overview

This project is an interactive application that detects colors in an image using Python and OpenCV. When the user double-clicks on any part of the image, the program identifies the color and displays its name along with RGB values.

---

## Setup Instructions

### 1. Install Python

Ensure Python 3.x is installed on your system.

### 2. Install Required Libraries

Run the following command in terminal:

pip install opencv-python numpy pandas

---

## Usage Instructions

Run the program using:

python color_detection.py -i pic2.jpg

### Steps:

* The image will open in a window
* Double-click anywhere on the image
* The detected color name and RGB values will be displayed

---

## How It Works

* The program captures the RGB values of the pixel where the user clicks
* It compares these values with a dataset (`colors.csv`)
* The closest matching color is found using a distance formula
* The color name is displayed on the image

---

## Libraries Used

* OpenCV – image processing
* Pandas – data handling
* NumPy – numerical operations

---

## 📸 Output

* Displays color name
* Shows RGB values
* Interactive detection using mouse clicks

---

## Conclusion

This project demonstrates basic image processing and color detection techniques using Python.

---

## Note

This project was implemented as part of an internship task.
