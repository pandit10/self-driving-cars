# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project you will detect lane lines in images using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images.  

The following techniques are used:
1. Color Selection
2. Canny Edge Detection
3. Region of Interest Selection
4. Hough Transform Line Detection


[Medium Link](https://medium.com/@somesh.pandit/detecting-lane-lines-on-the-road-for-sdc-16fdfa83068d)


My Pipeline consitsed of below steps
Apply grayscale()
Apply gaussian_blur()
Apply canny()
Apply region_of_interest()
Apply draw_lines()
Apply hough_lines()
Then you apply to every frame of the video

