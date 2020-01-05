## ros_img_processor
Just a simple template node receivng an image and doing something. Links to OpenCV and ROS wrapped.

## How to run the code
In a terminal window, type:
```sh
$ roslaunch ros_img_processor ros_img_processor.launch
```

## Tip
Check your webcam encodings (yuyv,mjpeg,...) and set them accordingly at file launch/usb_camera.launch

## Perception Exercise
A function to detect circles and show the direction vector (in RVIZ) has been implemented. The images below show the different direction vectors depending on the position of the detected circles.

![alt text](https://github.com/LuisLechugaRuiz/ros_img_processor/blob/master/Photos/Photo1.png)

![alt text](https://github.com/LuisLechugaRuiz/ros_img_processor/blob/master/Photos/Photo2.png)
