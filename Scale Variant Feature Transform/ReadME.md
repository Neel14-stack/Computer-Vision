# Scale Variant Feature Transform 📄

## Overview
**Scale Variant Feature Transform (SIFT)** is currently patente but can be freely used for academic purpose. 

* **OpenCV** has built-in-function for **SIFT**, but they need to be explicity installed since they are patented.

*The following steps show how to implement the SIFT functions:*
 - Load an image and convert it to grayscale.
 - Construct a SIFT object using the **SIFT_create()** function.
 - The **sift.detect()** function find the **keypoint** in the images. We can pass a mask if we want to search only part of the image. Each **keypoint** is a special structure that has many **attributes** such as its **(x,y) coordinates, size of the meaningful neighborhood, angle that specifies its orientation, response that specifies the strength of the keypoints, and so on.**
 - **OpenCV** also provides the **cv2.drawKeyPoints()** function, which draws small circles on the locations of the keypoints. If we pass the **flag = cv2.DRAW_MATCHES_FLAGS_DRAW_RICK_KEYPOINTS** to it, it will draw a circle with the size of the keypoint, and it will even show its orientation.


<p align="center">
  <img width="460" height="300" src="https://aishack.in/static/img/tut/sift-result.jpg">
</p>
