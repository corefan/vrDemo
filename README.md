# gvrDemo 0.2.1 alpha
Google Daydream demo app using Unity 5.4

This is a simple Daydream app created to showcase the technical skills necessary for producing an interactive VR world.

The [latest](https://github.com/jdknox/vrDemo/blob/master/build/jeff_knox_vr_demo.apk) Android version can be found in the [build](https://github.com/jdknox/vrDemo/tree/master/build) folder.

![overview of game island][island_01]
[island_01]: https://github.com/jdknox/vrDemo/blob/document/docs/img/island_01.jpg "Overview of island"


# Motivation
The future of Virtual Reality looks bright, and this project was started with the intent to build a VR game from scratch.  The main goal is to create a demo from the ground up to determine the challenges and potential solutions that arise in this relatively new medium.  One of the goals of this particular project is to find intuitive ways for the player to interact with the environment through a virtual hand.  These interactions include grabbing/interacting with objects (see Fig's. 1 and 2), rotating objects around an axis that is perpendicular to the player (see Fig. 3), and rotation around a parallel axis (work in progress).
![door opening example][door_opening]
###### Figure 1. Example of opening a door

![object grabbing example][object_grab]
###### Figure 2. Example of grabbing an object

![gear rotation example][gear_rotation]
###### Figure 3. Example of rotation about perpendicular axis

In addition, problems typical to any programming project--and in particular a computer game--are sure to crop up.  So, creating this demo also serves as a study into producing a game from start to finish, including appropriate user feedback, optimization and debugging.
[door_opening]: https://github.com/jdknox/vrDemo/blob/document/docs/img/door_opening.jpg "Opening a door"
[object_grab]: https://github.com/jdknox/vrDemo/blob/document/docs/img/cube_grab.gif "Grabbing a cube"
[gear_rotation]: https://github.com/jdknox/vrDemo/blob/document/docs/img/gear_rotation.gif "Rotation about perpendicular axis"


# Running the demo
Either a Google Daydream Controller or a second Android phone to act as the controller emulator is required as described [here](https://developers.google.com/vr/concepts/controller-emulator).
The in-game controls are as follows:
* Touchpad area (large circle): character movement
* Touchpad double tap (click emulation): interact
* App button: interact


# Future improvements
Optimization is always ongoing, targeting 60 FPS.  More interactions are in the works, as well as general polishing and cleanup.  Also, the code is in more of a prototyping stage; better use of OO principles would make it easier to extend and maintain.


# About me
I have a Bachelor's degree in Physics, as well as formal training in Computer Science and Technical 3D Animation.  I enjoy the debugging process to quickly diagnose problem areas, and have strong analytical skills.  Mathematics is a common thread throughout all my interests and education, which has resulted in a strong affinity for math, especially how it relates to real world problems like 3D graphics and physical applications.  Locating and solving problems is a passion of mine, and I enjoy prototyping an idea, and then analyzing the results to look for places where I can improve the efficiency.  Creating this VR demo game combines all of my passions and I hope you will enjoy the final product as much as I have enjoyed creating it.
