# JetsonTX1
This is a project starts with some problem I met when I set environment with Jetson TX1.

#Q :

After I install TX1 followed by the  Jetson Develop Kit, I can not use opencv to capture stream from usb-cam.

#A :

I download opencv wget http://downloads.sourceforge.net/project/opencvlibrary/opencv-unix/2.4.9/opencv-2.4.9.zip
and [follow this link ] (http://elinux.org/Jetson/Installing_OpenCV) to reinstall opencv. one more thing is that when build and install this code need to replace *NCVPixelOperations.hpp* which I put is in this project too.

