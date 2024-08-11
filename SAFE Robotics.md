# SAFE Robotics Laboratory

2024 Electrical and Computer Engineering Summer Research Internship

I worked exclusively with the 1/14-scale autonomous mini trucks in Professor Jaime Fernandez Fisac's SAFE Robotics Lab. My primary focus involved addressing the truck's velocity control issues.

## High Accuracy Velocity Measurement System

<img src="https://github.com/user-attachments/assets/bd6f151a-467b-4c03-b645-8d0082da350d" alt="Mini Truck PWM" height="50" width="50"/>

Utilizing an Arduino Nano and the built-in Hall Effect sensors of the brushless DC motor, I achieved a velocity measurement that Vicon data later validated to be accurate within 3%. This process involved reading the PWM signal from the Spektrum SLT3 Transmitter to the SR305 Receiver using an oscilloscope and replicating this signal using an Arduino Nano. 

## PID Control
Building on this foundation, I designed and implemented a PID control system using Arduino-generated 50Hz PWM signals. This enabled the mini truck to adjust to and maintain velocities between 1 m/s and 10 m/s. As a final capstone, I enhanced the SLT3 Transmitter’s AUX channel for modular control, allowing seamless switching between PID-controlled and manual operation modes with the SLT3 Transmitter. This improvement provides a stepping stone for future advancements. For example, I briefly discussed the possibility of using AI to control the mini-truck with the graduate students. If this were to become a reality, the next step would be to leverage the AUX channel of the SR305 receiver to modularly switch between PID control, manual operation, and AI control.
Throughout these projects, I gained valuable experience with prominent skills related to Electrical and Computer Engineering. I soldered many components, worked with microcontrollers like Arduino Nanos, and improved my proficiency with electronic instrumentation such as oscilloscopes, multimeters, and power supplies. Additionally, I performed a comprehensive analysis of the mini truck's hardware, documenting the technical specifications and capabilities of various components such as the brushless DC motor, steering servo, and ESC for ECE346 and research purposes. This extensive familiarity with these components has significantly enhanced my intuition for electronic components.
Overall, this internship provided tremendous hands-on experience and deepened my understanding of both theoretical and practical aspects of Electrical and Computer Engineering, preparing me for future challenges and innovations. I am deeply grateful to the donors whose support made this internship possible. Thank you for supporting and helping students like me grow and succeed in fields such as Electrical and Computer Engineering.

