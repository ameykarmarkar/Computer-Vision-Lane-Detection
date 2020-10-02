# Computer-Vision-Lane-Detection

Lane detection is one of the important component of Autonomous Driving Vehicle Systems (ADAS). With the aim to detect the lane on the road, I have developed a pipeline using Python and OpenCV.

Pipeline consist of following components - 
1. Grayscale conversion
2. Gaussian Smoothing
3. Canny Edge Detection
4. ROI Selection
5. Hough Transform 
6. Line Extrapolation

Limitations of this pipeline -
1. Not able to detecct  curved lanes
2. Issue in detection becuase of lighting conditions
