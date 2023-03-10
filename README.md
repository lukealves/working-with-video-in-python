# Working with Video Data in Python

In this project, you will learn how to work with video data in Python. You will learn about the basics of video data, how to convert between video formats, pull metadata from video files, open a video file, and extract images using cv2 (openCV). You will also learn how to add annotations to video frames and save edited videos.

# What is video data?
Video data is a series of images that, when shown in succession, give the illusion of motion, much like a flipbook. Video resolution is the size of each image in the video. It doesn't need to be a standard size, but there are common sizes for video. Frame rate determines the number of "images" seen per second and can be described as fps (frames per second) or Hz (general unit for frequency).

# Getting Setup for working with Video in Python
Packages you'll need installed:

* opencv / cv2: `pip install opencv-python`
* matplotlib: `pip install matplotlib`
* ffmpeg (for converting videos)
* import pandas as pd
* import numpy as np
* import cv2
* import matplotlib.pyplot as plt
* from glob import glob
* import IPython.display as ipd
* from tqdm import tqdm
* import subprocess

``plt.style.use('ggplot')``

# Dataset:
The dataset can be downloaded here: **https://www.kaggle.com/datasets/robikscube/driving-video-with-object-tracking**

# Converting video types
Use ffmpeg to convert mov to mp4. Read more in the documentation in **https://ffmpeg.org/ffmpeg.html**.
