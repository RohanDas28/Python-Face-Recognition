
# Python Face Recognition [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
### This is a simple python Face Recognition script . It uses OpenCV library to do the task. 
---
### Instructions
 1. Make sure you have [**Python** ](https://www.python.org/)(Version 3.6 or higher) installed in your system.
 2. Open the folder in CMD or terminal and type ``` pip install opencv-python ``` to install OpenCV.
 3. Now edit the **main.py** file using your favorite code editor(Example: Sublime text editor, VSCode, Vim).
 4. Place the desired photo in the directory.
 5. Change ```image= cv2.imread('1.jpg')```  according to your photo name. (Example: ```image= cv2.imread('example.jpg')```
 6. Now save the file, close the editor and run **main.py**.
---
### Tweaking
You can always tweak the program by just changing the values  here:(line 16)
 ```faces = face_cascade.detectMultiScale(imgGray, 1.2, 5)```
 Where **detectMultiScale** function is used to detect the faces. It takes 3 arguments — the input image, _scaleFactor_ and _minNeighbours_. _scaleFactor_ specifies how much the image size is reduced with each scale. _minNeighbours_ specifies how many neighbors each candidate rectangle should have to retain it. You may have to tweak these values to get the best results.
 
 ---
### Be sure to stargaze the repository and also checkout [My Website](https://rohandas28.github.io/) to contact me.
#### Thank You.