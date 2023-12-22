Cartoonize Project Readme

This Python script transforms images or live video into cartoon-style representations. It employs edge detection, bilateral filtering, and color quantization to achieve the cartoon effect.

Prerequisites

Python 3.x
OpenCV (cv2) library
NumPy library
scikit-learn library for KMeans clustering
Install the required libraries using the following command:

pip install opencv-python numpy scikit-learn


Usage

Run the script using the command:

python script_name.py

Choose between video mode (1) or image mode (2) when prompted.
Video Mode (1)
The script captures live video from the default camera and enables real-time cartoonification.
Trackbars for thresholding are provided to adjust the edge detection parameters.
Image Mode (2)
The script captures an image from the default camera and performs cartoonification.
Two cartoonification methods are provided: "SKETCHED CARTOON" and "BLENDED CARTOON."
The user can choose to save the resulting images.

Customization

Tune the trackbars in video mode for threshold calibration.
Adjust the KMeans clustering parameter (k) in the quantization function to control color quantization.
Explore additional image processing techniques or adjust existing parameters for different cartoon styles.

Acknowledgments

The script includes a welcome ASCII art from patorjk.com.
Inspired by OpenCV documentation and Stack Overflow discussions.
The project supports both live video and image-based cartoonification.
