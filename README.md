# Multi_Digit-Detector-and-Recognizer
The application find the dgits and recognizes it using contours and builds a bounding box over it.

Following are the libraies used in the code:

1)Tensorflow v1.12
2)Open cv
3)Pandas


Working of this model:

1) Takes in a image 
2) Finds the contours
3) Retains the contours with size >300
4) Computes the regoin of intrest based on coordinates of contour
5) Adds paddindg 25 for(top ,bottom,left,right)
6) Converts into grayscale
7) Rescales the pixel value by dividing by 255
8) Converts into mnist format 28X28
7) Feeds the resultant image to cnn
8) Calculates weigths
9) Gives the result.
