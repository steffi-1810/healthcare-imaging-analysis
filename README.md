# Brain Tumor Detection using OpenCV

This project uses OpenCV and basic image processing techniques to detect possible tumor regions in brain MRI images by identifying abnormal areas based on contour size.

## 🧠 Overview

The script:
- Loads a brain MRI image
- Converts it to grayscale
- Applies Gaussian blur for noise reduction
- Thresholds the image to isolate bright regions
- Finds and filters contours based on area
- Draws detected tumor regions on the image

## 🖼️ Sample Input
Make sure your input image is named `brain3.jpg` and placed in the same directory as the script. You can change the filename in the code if needed.

## 🛠 Requirements

Install the required packages:
```bash
pip install opencv-python numpy
# healthcare-imaging-analysis
brain tumor detection 
