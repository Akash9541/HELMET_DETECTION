Akash Thakur | 2025
This is a YOLOv3-based model designed to detect and count the number of people wearing helmets in an image. It can be used for monitoring intrusions or identifying individuals riding bikes without helmets.

Getting Started
This code is simple to use, and with minor modifications, you can:

Count the number of detections for a specific class (helmet/no helmet).
Extract the coordinates of bounding boxes.
Download the necessary models, create the required files, set the full paths correctly, and run the Python script.

Training
If you want to train your own model, follow the Darknet framework.

Prerequisites
Install Python 3
Install pip3
Install OpenCV:
sudo pip3 install opencv-python
Install other required libraries if missing.
Setup
After setting up the paths:

Change the path of the class file in line 19
Change the path of the configuration file in line 25
Change the path of the weights file in line 26
Change the output folder name in line 133 where you want to keep your output files
Change the input folder name in line 150 for input images
Once done, it's ready to run.

Run the Script
Open the terminal and execute:

python3 Helmet_detection_YOLOV3.py
Required Files
model → Contains trained YOLOv3 weights
cfg → YOLOv3 configuration file
obj.names → Class labels
Expected Results
If everything is set up correctly, you should get outputs like these:  
![img1](https://github.com/BlcaKHat/yolov3-Helmet-Detection/blob/master/test_out/img3.jpg)  
![img2](https://github.com/BlcaKHat/yolov3-Helmet-Detection/blob/master/test_out/img4.jpg)  
![img3](https://github.com/BlcaKHat/yolov3-Helmet-Detection/blob/master/test_out/img.jpg)  
#### link to files.  
[model](https://drive.google.com/file/d/1_xBdP1GRK4i7yzJP8_a5GWaejZZKjdyI/view?usp=sharing)  
[cfg](https://drive.google.com/file/d/119l1wonij3kXcuyAHC6-jRTw1NT0FzFH/view?usp=sharing)  
[obj.names](https://drive.google.com/file/d/1eSA8XVuzCe9Ka63v-HEWx7Hxo8z_cpaF/view?usp=sharing) 


