# face_recognition_from_rtmp

This project is hosted by Hohai University Robotics motion and vision Lab by National Defense Student. As its name meaning, we release a stable solution on face_recognition through RTMP. Before starting this project, we accumulate abundant practical experience on real-time video transmission system based on RTMP, which has been applied in [dog_project](https://github.com/ZhuChaozheng/dog_project). As we all known, RTMP is the best method for live video, since it has minimum delay time than other solutions (e.g. RTSP). Also, to obtain better result in face recognition, we call many functions on [Johe](https://github.com/ageitgey/face_recognition)'s C++ library. As you can see, it will draw a rectangle to contain someone face and name him below this rectangle.


## Get Started
``
pip3 install opencv-python3.4-20.0.0
pip3 install dlib
pip3 install face_recognition
git clone 
python3 face_recognition_from_rtmp.py --cpus 4
``

## parrallel compute
you can also set the argument to equal with your cpu cores. *e.g. --cpus 40*

## multi-video-input
we can easy to realize multi video sources input by using command line, set the argument --rtmp. *e.g. --rtmp 192.168.1.117/2710/live*
