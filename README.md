# Drowsiness_Detection_System
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

Logic of project
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.

![image](https://user-images.githubusercontent.com/81178925/112022782-9ea61700-8b58-11eb-86d2-06dbcd94a1d7.png)

The 68-landmark detector data


The working of the project
As you can see the above screenshot where the landmarks aredetected using the detector.
Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.
Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.

![image](https://user-images.githubusercontent.com/81178925/112022965-c9906b00-8b58-11eb-82ca-bb7479f165eb.png)
![image](https://user-images.githubusercontent.com/81178925/112022977-ce551f00-8b58-11eb-805c-b8e44c6744db.png)
![image](https://user-images.githubusercontent.com/81178925/112022986-d2813c80-8b58-11eb-821f-83d2877d36cc.png)
