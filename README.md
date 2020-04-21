# Python-CV
Opencv is a library used for Image processing means used to perform different kind of operation related to Images.

## Drawing on live Camera :
 This file contains the python code to open the camera through opencv library and drawing various shapes on it according to the user's choice.
 #### Rectangle:
 1. When the user first clicks the left mouse button (say pt1), a small red colored circle will be drawn on the screen and when again the button is pressed (say pt2), then a blue colored rectangle will be drawn between pt1 and pt2.
 2. This process continues untill the camera is quited.
 
 #### Circle:
 1. A circle of radius 30 will be drawn whenever left mouse button is pressed. 
 2. This process continues untill the camera is quited.
 
 ## Template Matching:
 It is a technique for finding areas of an image that are similar to a **patch**(template). A patch is a small image with certain features. The goal of template matching is to find the patch/template in an image.To find it, the user has to give two input images: Source Image (S) – The image to find the template in and Template Image (T) – The image that is to be found in the source image.
  Here, **Source Image - full** and **Template Image - face**
 
 Using all the six methods for Template Matching, the Heatmap and corresponding image is shown using matplotlib library. In the shown example, the red colored box shows the template image identified using *cv2.TM_CCOEFF* method:
 
![alt text](https://github.com/goyalmayank522/Python-CV/blob/master/Data/image1.PNG)
 
 
