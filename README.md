# Real-Time-Moving-Object-Detection-and-Background-Removal-in-Video-Streams-using-MATLAB
There are three types of methods mainly used in moving object detection. These methods are- the 
frame subtraction method, the background subtraction method and the optical flow method. In the 
Frame subtraction method, the difference between two consecutive images is taken to determine the 
presence of moving objects. The calculation in this method is very simple and easy to develop. But in 
this method, it is difficult to obtain a complete outline of moving object; therefore, the detection of 
moving object is not accurate. In the Optical flow method, calculation of the image optical flow field 
is done. The clustering processing is done according to the optical flow distribution characteristics of 
image. From this, the complete movement information of moving body is found and it detects the 
moving object from the quantity of calculation, poor anti-noise performance makes it unsuitable for 
real-time applications. 

Therefore, In this project, we tried to incorporate the background subtraction method that delivers relatively better results & accuracy.
The background subtraction method is the method in which the difference 
between the current image and background image is taken for the detection moving objects by using 
simple algorithm. But it is very sensitive to the changes which occur in the external environment and 
it also has poor anti interference ability. One advantage of this method is, it can provide the most 
complete object information in the case of the background is known. In the background subtraction 
method, in a single static camera condition, the dynamic background modeling is combined with 
dynamic threshold selection method which depends on the background subtraction. The background 
is updated on the basis of accurate detection of object.
This Method includes steps:

A)Frame Separation
 Frame processing is the first step in the background subtraction algorithm, the purpose of this step is 
to prepare the modified video frames by removing noise and unwanted objects in the frame in order 
to increase the amount of information gained from the frame. Preprocessing of an image is a process 
of collecting simple image processing tasks that change the raw input video info into a format. This 
can be processed by subsequent steps. 

B)Moving Object Detection
Background subtraction is particularly a commonly used technique for motion segmentation in static 
scenes. It attempts to detect moving regions by subtracting the current image pixel-by-pixel from a 
reference background image that is created by averaging images over time in an initialization period. 
The pixels are classified as foreground where the difference is above a threshold. After creating a 
foreground pixel map, some morphological post processing operations such as erosion, dilation and 
closing are performed to reduce the effects of noise and enhance the detected regions. The reference 
background is updated with new images over time to adapt to dynamic scene changes.

C)Detection of Moving Objects in the Video
 Motion detection has been done using spatio-temporal differencing. For motion detection based on 
the spatio-temporal filter, the motion is characterized via the entire three-dimensional (3D) spatio
temporal data volume spanned by the moving person in the image sequence. Its advantages are low 
computational complexity and a simple implementation process. Here, Motion detection is carried 
out by the background elimination algorithm as follows.  

D)Background Elimination
 The background subtraction system is used to provide foreground image through the threshold of 
difference image between the current image and reference image. As the reference image is the 
previous frame, this method is called temporal differencing. The temporal differencing is very 
adaptive to dynamic environment. Background elimination was carried out using mean squared 
error concept.

different approaches to the basic scheme of background subtraction in terms of foreground region 
detection, background maintenance and post processing.  
