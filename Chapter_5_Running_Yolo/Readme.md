This chapter introduces Yolo - a fast objected detection model used for both images and videos. The model produces labeled boxes (rectangles) that bound and classify each of the objects. In this case the 'cv2' image processing library is used to read the intial image and to display the various image feature. In the python version in the tutorial, cv2 is also used to display the resulting image.  However, in the notebook version cv2 does not work with the Yolo modeling results. For this reason, I had to provide a couple of functions to actually create the display with the bounded areas. As is often the case, I was able to find a couple of functions that fit the bill

https://inside-machinelearning.com/en/bounding-boxes-python-function

Three images are used to illustrate the overall process.  Included are:

<ul>
<li>An image containing a school bus at a stop where students are loading. Some of the students have backpacks and skateboards. All of the objects are detected.</li>
<li>An image of bumper-to-bumper cars. The object is to detect each of the cars.</li>
<li>An image with a number of motorcycles in the foreground and cars, people, and trucks in the background.</li>
</ul>
