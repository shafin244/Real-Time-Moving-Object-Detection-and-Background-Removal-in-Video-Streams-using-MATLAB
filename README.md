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
