The change detector is an algorithm that uses your laptop webcam to recognize real time modifications in a video sequence using background subtraction techniques. 

#### Background subtraction techniques used:
- _Absdiff_
- _MOG2_
- _KNN_

To execute the implemented system, the version 3.2.0 of OpenCV or above is needed. To compile the file [change_detector.cpp](https://github.com/tiagoadonis/Change-Detector/blob/master/change_detector.cpp) do the following:
- g++ change_detector.cpp -o change_detector `pkg-config --cflags --libs opencv`
