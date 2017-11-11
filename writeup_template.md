# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then 2)I applied gaussian_blur
then 3) I applied canny  to find edges then 4) I found region of interest 5) applied Hough transform .... 

Apply grayscale()
Apply gaussian_blur()
Apply canny()
Apply region_of_interest()
Apply draw_lines()
Apply hough_lines()
Then you apply to every frame of the video

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by manipulating the treshhold and parameters of hough transform.






### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when lanes are not properly marked  




### 3. Suggest possible improvements to your pipeline

A possible improvement would be to 

Another potential improvement could be to ...
