# CarND-LaneLines-P1
# **Overview Finding Lane Lines on the Road** 
---
MY First Project in Udacity
The goals of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report
finds lane lines example image

![alt text][image2]


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"
[image2]: ./examples/line-segments-example.jpg "line-segments-example"
[image3]: ./examples/Canny_out.jpg "Canny_out"
[image4]: ./examples/Region_mask.jpg "Region_mask"
[image5]: ./examples/Hough_transform.jpg "Hough_transform"
---

### Reflection

### 1. Describe your pipeline.

My pipeline consisted of 3 steps:
**Step 1:**, I converted the images to grayscale, and I Use Gaussian smoothing filtering, and I use Canny Edge Detect Lane Lines
![alt text][image3]

**Step 2:**, I use a quadrilateral region mask to filter out detected line segments in image.
![alt text][image4]

**Step 3:**, Use Hough Transform to Find Lane Lines on Edge Detected Image
![alt text][image5]

### 2. Identify potential shortcomings with your current pipeline

One potential shortcoming would be what use the extrapolation technique to calculate the slopes as a guide for extrapolation to get the solid lines on the lane. because, I can't understand, So I can't calculation in current pipeline.

### 3. Suggest possible improvements to your pipeline

If you help me to understand calculate function. May be possible improvement
