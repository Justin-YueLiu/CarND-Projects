# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project you will detect lane lines in images using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images.  


---

My pipeline basically follow the step of the tutorial to modify the draw_lines() and here is the result of my test image.

<img src="./test_images_output/solidWhiteCurve.jpg" width="480" alt="Combined Image" />
<img src="./test_images_output/solidYellowCurve.jpg" width="480" alt="Combined Image" />
<img src="./test_images_output/solidYellowLeft.jpg" width="480" alt="Combined Image" />
<img src="./test_images_output/whiteCarLaneSwitch.jpg" width="480" alt="Combined Image" />

One major shortcome is when apply the method to the bonus video, the result is not acceptable and can not follow the line curve. 

A possible improvement would be to adjust the draw_lines() method to make it more robust.


