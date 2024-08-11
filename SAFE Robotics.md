# SAFE Robotics Laboratory

2024 Electrical and Computer Engineering Summer Research Internship

I worked exclusively with the 1/14-scale autonomous mini trucks in Professor Jaime Fernandez Fisac's SAFE Robotics Lab. My primary focus involved addressing the truck's velocity control issues.

## High Accuracy Velocity Measurement System

<img src="https://github.com/user-attachments/assets/bd6f151a-467b-4c03-b645-8d0082da350d" alt="Mini Truck PWM" width="300"/>

<img src="https://github.com/user-attachments/assets/50efaa4a-202a-43c9-8210-47d547f78f51" alt="Oscope PWM" width="300"/>

Utilizing an Arduino Nano and the built-in Hall Effect sensors of the brushless DC motor, I achieved a velocity measurement that Vicon data later validated to be accurate within 3%. This process involved reading the PWM signal from the Spektrum SLT3 Transmitter to the SR305 Receiver using an oscilloscope and replicating this signal using an Arduino Nano. 

<img width="300" alt="Screenshot 2024-08-11 at 11 22 49 AM" src="https://github.com/user-attachments/assets/5a5f4310-707e-4820-8411-859c07897433">

The Arduino accurately reads the velocity of the mini-truck when the SLT3 Transmitter uses 50% throttle.

## PID Control

<img width="700" alt="Screenshot 2024-08-02 at 12 24 16 AM" src="https://github.com/user-attachments/assets/46e304b5-d7d4-46f3-ab87-e0abd21083ff">

Building on the velocity measurement system, I designed and implemented a PID control system using Arduino-generated 50Hz PWM signals. This enabled the mini truck to adjust to and maintain velocities between 1 m/s and 10 m/s. 

## Modular Control

[ECE Summer Research Internship 2024 Final Demo](https://www.youtube.com/watch?v=jGswh1pgZLI)

[Manual Control](https://www.youtube.com/watch?v=TGkLamtdMaw)

[PID Control](https://www.youtube.com/watch?v=QSj4fQSVbEg&feature=youtu.be)

As a final capstone, I enhanced the SLT3 Transmitter’s AUX channel for modular control. Depending on the value of the duty cycle for the AUX channel, which is controlled using the SLT3's 3-Channel Switch, the mini-truck will seamlessly switch between PID-controlled and manual operation modes.



