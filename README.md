# Intelligent-gym
Project mainly focuses on safely reopening of gym. During covid-19 pandemic gyms have been closed for long time which casted its effect on people by drastically reducing there health and immunity .


It provides a complete safety system for gyms starting from checking whether the customers have a mask at the entrance as well as inside the gym. It will also check whether the customers are following the social distancing norms inside the gyms by calculating the distance of each customer from everyone else and highlights in red if they are not. Many countries have also imposed a restriction on the number of customers inside the gym at a given time. This maintains the count of all the customers inside the gym. The number of staff members also have to be reduced so this implies they wont be able to monitor the gym activities properly so we have made a fall detection system which will help monitor the safety of the customers even when the gym trainers are outside the exercise area . This provides a complete solution to the challenge posed by Covid on opening of gyms.


## How I build it
The entire code is written in python 3.8. For person counting and person detection we have used YOLOv3 which is the most accurate algorithm present for object detection. For face detection(caffe based) and mask detection(mobile net v2) we have used opencv and imutils for preprocessing .
For fall detection we used yolov3 with an algorithm based on athematics foe detecting a fall (sudden increase in width of the box and decrease in height )


what next for Intelligent-gym
## What's next for Intelligent gymn  
We have almost made a complete solution for reopening of gym and accidents detection but further a yoga pose detector for accurate pose detection and gym workouts detector for preventing any wrong exercise can be added for accurate measurement of there poses and preventing any injury to the people can be added .
