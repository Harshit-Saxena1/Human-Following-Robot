# Human-Following-Robot
This Arduino-based robot follows a human using IR sensors to detect hand movements and an ultrasonic sensor to maintain distance. It adjusts motor speed dynamically to turn and move towards the detected hand. Ideal for basic autonomous navigation and human interaction projects.
This project implements a human-following robot using an Arduino, IR sensors, and an ultrasonic sensor. The robot detects a human hand using IR sensors and moves accordingly while maintaining a safe distance using the ultrasonic sensor.

Features
    Follows a human by detecting hand movements using IR sensors
    Maintains a specified distance using an ultrasonic sensor
    Controls motor speed dynamically for turning and movement
Components Required
    Arduino UNO R3 Board
    HC-SR04 Ultrasonic Sensor (for distance measurement)
    IR Sensors (for hand detection)
    L298N Motor Driver (or equivalent for motor control)
    DC Motors
    Power Supply
How It Works
    The IR sensors detect the presence of a hand.
    If the right sensor detects a hand, the robot turns right.
    If the left sensor detects a hand, the robot turns left.
    The ultrasonic sensor measures the distance to an object in front.
    If the object is within 10 to 30 cm, the robot moves forward.
    If no object is detected within range, the robot stops.
    The motors are controlled using PWM signals, allowing speed adjustments.
Setup Instructions
    Connect the IR sensors to digital pins 2 and 3.
    Connect the HC-SR04 ultrasonic sensor to digital pins 11 (TRIG) and 12 (ECHO).
    Connect the motor driver to control the right and left motors through the defined pins.
    Upload the provided Arduino code to the board.
    Power the system and test the movement based on hand gestures.
