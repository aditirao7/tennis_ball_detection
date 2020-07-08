# Tennis Ball Detection
Detecting tennis balls using OpenCV. A few different scripts for detection using different methods.

## MEC_hough
   Detection by comparing the areas of the minimum enclosing circle and the hough circle.
   
## aspectratio
   Detection based on the following comparisons:
   1. Areas of contour and minimum enclosing circle.
   2. Centroids of contour and minimum enclosing circle.
   3. Value of Aspect ratio of bounding rectangle.
   
## hough_contour
   Detection by comparing the areas of the contour and the hough circle.

## solidity
   Similar to aspectratio but also checks solidity.
   
## tennisballtracker
   A script to help determine the mask values for HSV colourspace in a given environment.
