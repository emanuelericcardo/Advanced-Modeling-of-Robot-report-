# Advanced-Modeling-of-Robot
Kinematics and Dynamics of a Biglide robot

The geometric, kinematic and dynamic models of the Biglide robot were modeled in the MATLAB environment and compared to the results obtained with ADAMS. 

It was possible to observe that the error between the two simulations was always negligible when compared to the absolute value of the corresponding quantity. 

Moreover two different control schemes were implemented on SIMULINK and used to perform trajectory tracking through ADAMS co-simulation. 

The first one was based on a Kinematic Control Law, while the second one applied a Computed Torque Control law: both schemes showed a good convergence behavior for the tracking error, except when the robot was approaching a Type 2 singularity. 

This latter issue was overcome by designing a trajectory that respected the criterion necessary to cross such singularity.
