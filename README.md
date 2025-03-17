# Electrical Engineering Student

## Projects
### Self-Balancing Robot, University of British Columbia (Jan, 2025 - Present)
- Worked in a team of 3 to program an Arduino Nano that used a gyroscope and accelerometer to measure the tilt angle of the robot.
- Modelled the mechanical system of the robot in MATLAB Simscape and tuned PID coefficients based on the system’s response.
- Interfaced two DC gear motors to an H-bridge chip and controlled the motors by converting the PID’s output from force to PWM.

### Remote Controlled Metal Detector Robot, University of British Columbia (April, 2024)
-	Worked in a team of 6 to program in C an ATmega328P MCU that would read the ADC values from a joystick and send them to an EFM8LB12 MCU via JDY-40 radio modules.
-	Interfaced the EFM8 MCU to two servo motors via an H-Bridge and to a Colpitts oscillator to detect a change in frequency when the car approaches a piece of metal. 
-	Programmed the EFM8 MCU in C to convert the received joystick values into PWM signals, send the PWM signals to the servo motors attached to the car, and to send a signal back to the ATmega MCU when the car detects a piece of metal.

![MetalDetectorRobot](/assests/img/MetalDetectorRobot.png)

[Watch the Remote Controlled Metal Detector Robot here](https://youtu.be/mZLfGB5S_78)

### Reflow Oven Controller, University of British Columbia (February, 2024)
-	Worked in a team of 6 to interface a N76E003 microcontroller coded in assembly to control an oven that reflow soldered PCBs.
-	Programmed in Python a temperature strip chart plot that received values via SPI from the MCU and plotted in real time.
-	Coded the state machine of the MCU to control the time of each state and the PWM output to power the oven.
-	Designed the temperature measuring circuit by using a LM335 as the cold junction, an op amp connected to a thermocouple as the hot junction, and interfacing both junctions to the MCU’s ADC.

![ReflowOven](/assests/img/ReflowOven.png)

[Watch the Reflow Oven Controller here](https://youtu.be/R9UzU7Z3a9Q)

### Simple RISC Machine, University of British Columbia (Nov, 2023)  
-	Designed and coded the data path, finite state machine, Memory, and I/O of a simple RISC machine in Verilog.
-	Worked alongside a partner and used Visual Studio Live Share to achieve paired programming remotely.
-	Simulated designs in ModelSim by creating testbenches to check signal values/waveforms and troubleshooted designs based on the outcome of the simulation.
-	Uploaded the completed design to a DE1-SoC using Quartus to verify correct simulations by testing the system’s I/O.

### Line Following Robot, Kwantlen Polytechnic University (Mar, 2023 – Apr, 2023)
-	Programmed a Pololu 3pi Robot in C with a PIC18F46K42 microcontroller to complete a line track with various obstacles such as gaps, dead ends, nearby tracks, and crossroads.
-	Developed an algorithm that allowed the robot to recognize an obstacle, helped determine which obstacle it had approached, and how it should proceed through the obstacle.
-	Submitted weekly reports entailing the project’s progress, pseudocode solutions for obstacles, and the goals for the following week.

![LineFollowingRobot](/assests/img/LineFollowingRobot.png)

[Watch the Line Following Robot here](https://youtu.be/aSvBTuyrISc)

### Festo Modular Production System, British Columbia Institute of Technology (Jan, 2022 – May, 2022)
-	Programmed an Allen-Bradley PLC to control 3 miniature production stations that sorted small wheels based on colour and material.
-	Implemented an HMI that allowed users to start each station, view each station’s sorted wheels, where a system fault had occurred, and enter a password controlled manual override mode.
-	Designed parts in SolidWorks and manufactured/created them through water jetting, shearing, sanding, drilling, and 3D printing.
-	Installed pneumatic tubing and replaced/fixed broken pneumatic actuators.
-	Troubleshooted the system’s circuit using an oscilloscope and multimeter.

![FMPS](/assests/img/FMPS.png)

[Festo Modular Production System Wheel Sorting](https://youtu.be/S2NsLHZfQiI)

[Festo Modular Production System Manual Override Mode](https://youtu.be/Ey4tMkQz95E)

[Festo Modular Production System Height Detection](https://youtu.be/a36U2wlnijE)

### Maze Solving Robot (2018)
-	Designed and built the casing for a 2-wheel Arduino robot by sawing pieces of plastic board, drilling holes for sensors and buttons, and gluing the pieces together.
-	Soldered/Interfaced buttons, sensors, and motors to an Arduino.
-	Programmed the robot to use its ultrasonic sensors and buttons to navigate its way out of a maze.	
