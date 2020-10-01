Prequisites OpenCV,you can get it from the github repository and build it via this link (https://github.com/opencv/opencv)

Cascades are car.xml gotten from a pre-trained haar cascade classifier by Andrew Sombral

For Linux users
-----------------
* For Linux users, a Makefile is provided to compile the source code.
* * Requirements: OpenCV 2.4.x (it only works with this version).
* * Check out the latest project source code and compile it:

~/git clone https://github.com/andrewssobral/vehicle_detection_haarcascades.git

~/cd vehicle_detection_haarcascades

~/vehicle_detection_haarcascades/ chmod +x run_vehicle_detection_video1.sh

~/vehicle_detection_haarcascades/ chmod +x run_vehicle_detection_video2.sh

~/vehicle_detection_haarcascades/ cd build

~/vehicle_detection_haarcascades/build/ cmake ..

~/vehicle_detection_haarcascades/build/ make

* Run demos:

~/vehicle_detection_haarcascades# python vehicle_detection.py

* In some cases the python version hinders the program from executing,this is an alternative.

~/vehicle_detection_haarcascades# python3 vehicle_detection.py

## Credit goes to Andrew Sobral,the original creator
