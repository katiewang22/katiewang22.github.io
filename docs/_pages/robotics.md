---
layout: single
title: Robotics
permalink: /robotics/
---

<a id="top"></a>

<a href="https://github.com/RoboLions/frc-2022-new" target="_blank">Full Robot Repo</a>

<a href="https://github.com/RoboLions/shooter-test" target="_blank">Code To Test Shooter</a>

<p align="center">
    <img src="/assets/images/robot.jpg" alt="Robot Pic" width="600"/>
</p>

<p align="center">
    <img src="/assets/images/shooterDemo.gif" alt="Shooter Demo" width="600"/>
</p>

Currently, I am working on the code for my team's 2022 season FRC robot. A new subsystem this year is our shooter. With the help of our Viasat mentor, I implemented a PID control loop to decrease the amount of time it took for the RPM of the shooter to mitigate the disturbance from the ball that was shot.

We used the Ziegler–Nichols method to calculate PID after finding a P-value where the shooter motor just began oscilating.

<p align="center">
    <img src="/assets/images/pidvalues.png" alt="PID Calculated" width="500"/>
</p>

<p align="center">
    <img src="/assets/images/shooterGraph.jpg" alt="PID Working" width="400"/>
</p>

After commanding a velocity to the motor, it is passed through our feedforward and PID calculations. 

<p align="center">
    <img src="/assets/images/shooterpid.png" alt="PID Calculated" width="800"/>
</p>

&nbsp;

<div class="bottomright">
    <a href="#top">Back to top</a>
</div>