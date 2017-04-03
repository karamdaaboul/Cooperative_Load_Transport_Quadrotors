Overview
---
We address the problem of cooperative transportation of a cable-suspended payload by multiple quadrotors. This work based on the work which is maded by Kumar and Sreenath [1](http://www.kumarrobotics.org/wp-content/uploads/2014/01/p11.pdf). In the beginning, we determine the equations describing the dynamics of the system. Then we define the differentiall flatness of a dynamic system and determine the flat output vector of our system.  Finally we write a program with matlab to implement the motion of N quadrotors with a mass point. 

Dynamic Model
---
<img src="https://github.com/kaya2016/Cooperative_Load_Transport_Quadrotors/blob/master/QuadrotorsWithLoad.png" width="400">
The equation of motion and the definition of differential flatness are in the note book [2](https://github.com/kaya2016/Cooperative_Load_Transport_Quadrotors/blob/master/Cooperative_Load_Transport_with_group_of_Quadrotors.ipynb)

Dependencies
---
This program requrirs no additional toolboxes


Functions
---
`Quadpolt`: creates an object to plot one of the quadrotor    
`Loadpolt`: create an object to plot the Load    
`DiffFlat`: determines the input vector and the state vector from the output vector  
`CreatTraj`: creates optimal trajectory between two given way points  
`PlotResults`: plots the results.

To start the program with the default value you can use the code:
```matlab
step1
```

References
---
[1]: K. Sreenath and V. Kumar. Dynamics, Control and Planning for Cooperative Manipulation of Payloads Suspended by Cables from Multiple Quadrotor Robots, 2013,  http://www.kumarrobotics.org/wp-content/uploads/2014/01/p11.pdf 
[2]: D. Mellinger and V. Kumar. Minimum Snap Trajectory Generation and Control for Quadrotors,http://www-personal.acfr.usyd.edu.au/spns/cdm/papers/Mellinger.pdf  
[3]: M.K. Daaboul. Kooperative Regelung von Quadrokoptern bei Berücksichtigung von Hindernissen und Kopplung,2017,# Project: Cooperative Load Transport with group of Quadrotors
