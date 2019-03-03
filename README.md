# simple-face-detection-with-opencv

### Description
This program explains how to do object detection (face and eyes) using OpenCV on Python. Firstly, I imported some Haar Cascade files. These kind of files are very useful to perform object detection on common elements such as face, vehicles, eyes, facial expressions, and so on. Later I created a grayscale copy of every image being inputed to perform the feature detection.

### Dependencies
There are four different packages and you should select only one of them. Do not install multiple different packages in the same enviroment.

a. Packages for standard desktop environments (Windows, macOS, almost any GNU/Linux distribution):

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;run `pip install opencv-python` if you need only main modules  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;run `pip install opencv-contrib-python` if you need both main and contrib modules (check extra modules listing from OpenCV documentation)

b. Packages for server (headless) environments:
These packages do not contain any GUI functionality. They are smaller and suitable for more restricted environments.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;run `pip install opencv-python-headless` if you need only main modules  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;run `pip install opencv-contrib-python-headless` if you need both main and contrib modules (check extra modules listing from OpenCV documentation)

### Usage
If you want to try this program, you can download this repo and run the [face-detection.py](https://github.com/igerardoh/simple-face-detection-with-opencv/blob/master/face-detection.py) file on your machine. You can also check out a detailed explanation of how this programs work by taking a look at this notebook: [Face Detector](https://nbviewer.jupyter.org/github/igerardoh/simple-face-detection-with-opencv/blob/master/face-detection-explained.ipynb)

![alt text](https://raw.githubusercontent.com/igerardoh/simple-face-detection-with-opencv/master/screenshot.png "Facial detection")

### TO-DO :
- ~~Define image capture function.~~
- ~~Face area detection.~~
- ~~Eyes subarea detection.~~
- ~~Execute the program.~~