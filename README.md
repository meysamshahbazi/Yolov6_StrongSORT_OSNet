# Yolov6_StrongSORT_OSNet
Adapted from [Yolov5 + StrongSORT with OSNet](https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet)
So at first, have look at that repository. 
 The only change I've made is porting [YOLOv6](https://github.com/meituan/YOLOv6) to it.

 ## How to use:
 - First install any requirments in [Yolov5 + StrongSORT with OSNet](https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet)
 - make a copy of this repository in your machine
    ```
    git clone https://github.com/meysamshahbazi/Yolov6_StrongSORT_OSNet.git
    cd Yolov6_StrongSORT_OSNet
    mkdir weights
    ```
- Download yolov6 [weights](https://github.com/meituan/YOLOv6/releases/tag/0.1.0) and put them in ```weights```
- Now run tracker by :
    ```
    python track.py --source 0  # webcam
                            img.jpg  # image
                            vid.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            'https://youtu.be/Zgi9g1ksQHc'  # YouTube
                            'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
    ```



