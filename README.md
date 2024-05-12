# GestureNav-Virtual-Mouse Using Hand Gesture Recognition
* At first webcam access is given which is video interface for tracing the Hand Landmarks and recognizing them.
* Algorithms like MediaPipe's HandPose or OpenPose are used to estimate the landmarks (key points) of the hand, such as fingertips, palm center, etc. These algorithms are based on deep learning models trained specifically for hand landmark detection.
* Once hand landmark tracing is done, now we can design algorithms for gesture recognition.
* Here Pyautogui is used for tracing the mouse movements or clicks.
* After the algorithms are written,now on running the code   the webcam activates on the screen and recognises the hand gesture and performs the operations accordingly.
* If I have my index finger and middlle finger up then it is for double click,Middle finger to perform right click,Index finger to perform left click,moving my index finger up to increase the volume and moving my index finger down to decrease the volume.
* Based on gesture recognition ,mouse operations are performed like double click,right click,left click, volume up and volume down.


