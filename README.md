# Moving-object-detection
Moving object detection using Opencv
Computer vision:takes input as image or video the goal is to understand the image and its properties, perform image processing algorithms to perform the task like human being
1.intialize the camera
2.initialize first frame as none
3.Run the while loop infinite times
4.Read the image as input
5.perform the resizing of image
6.convert BGR colour format of image to gray
7.Do the smoothning of image by removing edges of input image by using Gaussian blur
8.getting the frames and comparing the previous frame with the present frame
9.and finding the countours to draw the rectangle bos around the moving object
10.and in output frame print the text as "NORMAL" if object is not moving
and print "moving object detected" if object is moving
