# Features from Accelerated Segment Test (FAST) 📝

## Overview
**Features from Accelerated Segment Test (FAST)** was first introduced in 2006 by Edward Rosten and Tom Drummond. The previous **Feature
Detectors** are not useful for real-time applications, for example those with video cameras collecting real-time images or robots. These use
cases will fail if any delay is caused in feature detection at runtime. 

The **FAST** algorithm uses a pixel neighborhood to compute key points in an image.
- For the neighborhood, three flags are defined: cv2.FAST_FEATURE_DETECTOR_TYPE_5_8, cv2.FAST_FEATURE_DETECTOR_TYPE_7_12, and cv2.
FAST_FEATURE_DETECTOR_TYPE_9_16.

<p align="center">
  <img width="400" height="300" src="https://raw.githubusercontent.com/Neel14-stack/Computer-Vision/main/Feature%20from%20Accelerated%20Segment%20Test/output.jpg">
</p>
