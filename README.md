# Hand_Gesture

This code is a hand gesture recognition project using Python and OpenCV. Two main libraries are used for this project: Mediapipe for detecting hand points and OpenCV for image processing and display.

First, the required packages are installed and required. Then, the required models are loaded to detect the important points of the hand and recognize the movements. Models loaded here are pre-trained.

Then a webcam is connected and images are taken continuously from the webcam. Each frame that is captured is first inverted vertically so that it is reflected correctly on the screen.

Then, using a special model, the important points of the hand are detected in each frame. These important points include 'okay', 'peace', 'thumbs up', 'thumbs down', 'call me', 'stop', 'rock', 'live long', 'fist', 'smile'. These points are then used to detect hand movements.




https://github.com/ahmadmirdamadi/Hand-Gesture/assets/113544813/fa412ce9-df9c-4e6c-b350-d82bd0dfc897


The program continues until the user presses the q button and the window is closed.

Source:https://techvidvan.com/tutorials/hand-gesture-recognition-tensorflow-opencv/
