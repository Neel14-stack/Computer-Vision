# Template Matching

## Overview
As part of **object detection** and **recognition**, we need to do shape analysis and feature analysis. To do this, there is a robust technique called **Template Matching**.

This technically is a **brute force algorithm** or a **simple mechanism** to extract an object based on a previously acquired template.
* **OpenCV** has a **matchTemplate()** function to perform **Template Matching**

*This function takes a **"sliding window"** of the image being queried and slides it across the image it is searching for to determine its presense. It does this one pixel at a time. Then, for each of these locations, a correlation coefficient is calculated if there is a match at all. Region with a high correlation are the regions that match.*

*This method uses a template to detect an object after segmentation. If the segmented object is similar to the template, then the object detection process is concluded: Otherwise, another template is picked for a similarity check.*
