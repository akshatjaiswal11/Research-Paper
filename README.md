# Research-Paper
Research on Grayscale to Color Image Conversion 
# Grayscale to Color Image Conversion

This project converts grayscale images into colorized versions using a deep learning model in Python.

## Project Description

- Uses a pre-trained model based on the work by Richard Zhang et al.
- Implemented in Python with OpenCV and NumPy.
- Input: Grayscale image
- Output: Colorized image

## Requirements

- Python 3.x  
- OpenCV (`cv2`)  
- NumPy

Install dependencies using:
- pip install numpy opencv-python

## Model Files Required

Download and place the following model files in your project directory:

1. `colorization_deploy_v2.prototxt`  
   [GitHub Link](https://github.com/richzhang/colorization/tree/caffe/colorization/models)

2. `pts_in_hull.npy`  
   [GitHub Link](https://github.com/richzhang/colorization/blob/caffe/colorization/resources/pts_in_hull.npy)

3. `colorization_release_v2.caffemodel`  
   [Dropbox Link](https://www.dropbox.com/s/dx0qvhhp5hbcx7z/colorization_release_v2.caffemodel?dl=1)

## How to Run

Make sure the model files are in the same directory as your script, then run:

You can modify the script to load and colorize any grayscale image.

## Reference

Original model and paper:  
[https://github.com/richzhang/colorization](https://github.com/richzhang/colorization)


