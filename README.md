# Lie Detector Device 
Current repository for CS 207 class for Fall 2019.

INTRODUCTION
=================
The idea is of this project is to build a lie detector device in a costly effective way. this device was built from a single arduino uno, bread board, heart pulse sensor, resistors and some wires. it was built over 15 days period. 

The toughest part of this project was the coding part. To calculate the average rate of electrons flowing from the body. we tried to use array but it did not work. so we looked for a different solution and came up with the idea of using Enqueue the data collected from the body and to Dequeue the data collected to calculated and get the constant rate.

The heart sensor was another challenge to code, however arduino has a library called <PulseSensorPlyaground> that made job even easier.  


The uploaded code works as a buffer machine where as it stacks it should calculate an average of the values and then try to see any sudden changes in the input therefore detecting any sympathetic response. 

Bill Of Material
====================
1 x Arduino
1 x breadboard
8 x 10k ohoms resistors
1 x heartbeat sensor(pulse sensor)

SETUP
====================
![alt text][pic2]

[pic2]: https://github.com/IgaGonzalez/CS-207/blob/master/Screen%20Shot%202019-12-05%20at%2011.07.04%20PM.png "Logo Title Text 2"

![alt text][pic3]

[pic3]: https://github.com/IgaGonzalez/CS-207/blob/master/IMG_2295.jpg "Logo Title Text 3"

Technologies
============
*Arduino 1.8.9
*C++ 17

LAUNCH
=========
To run this device the code uploaded here should be uploaded into the arduino first. once the code is uploaded put the heart sensor device on the index fingure. the electron readers on any of the other two fingures. After your set once, ask obvious questions for the first 30 seconds or a mintue to collect the average electron flow in the subjects body. Then have fun asking questions you have doubt abour or just for fun. 

Team
=====
Blossom Ugolo- mainly responsible with the write up
Firaol Gina- mainly wiring and code edition.
Ignacio Gonzalez - mainly coding. 

We all contributed in all the tasks , so it's really hard to take credit for specific task, however according to task division and resposiblities we made sure our project is right on time. 

CREDIT
=======
Roumega Dante, Original Creator

