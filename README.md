## Autonomous Navigation Mobile Robot using ROS Navigation Stack.

AMCL is used for localisation, with DWA local planner planner for path planning.

### Sensors used:
1. RP Lidar A1-M8.
2. Motor Encoders.

### Other parts:
1. Nvidia Jetson Nano 4gb.
2. 2x Arduino nano (One for each motor to make sure smooth operation of Interrupt service routine to count the encoder pulses and ROS communication over I2C.)
3. Encoder motors [Link Here](https://robokits.co.in/motors/rhino-gb37-12v-dc-geared-motor/dc-12v-encoder-servo-motors/rhino-gb37-12v-60rpm-10.4kgcm-dc-geared-encoder-servo-motor)
4. Robot Chasis
5. Boost converter to provide 12V for motors.
