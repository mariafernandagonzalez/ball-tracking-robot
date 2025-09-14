# Computer Vision Detection and Tracking Robotics Project
A mobile robot that uses computer vision and real-time image processing to detect and track a ball. Developed in Caltech’s Introduction to Robotics course, this project focused on vision-based algorithms, image filtering, and motion planning. The system processes live video input to identify and follow a moving ball, demonstrating autonomous behavior through software-driven control. Watch the [DEMO](https://www.youtube.com/watch?v=-PGfyatwvf8).

<p align="center">
  <img src="Front-View-of-Robot.png" width="400">
</p>

## Features
### Smooth Motion Control
-### Smooth Motion Control
- Motor positions and velocities are planned using cubic spline interpolation for both pan and tilt axes.
- At each control loop iteration, the system calculates updated commands based on current feedback and target positions.
- Real-time adjustments ensure smooth transitions, avoiding abrupt starts or stops while accurately following dynamic targets.
- Data logging and visualization of positions and velocities allow verification of tracking performance and system accuracy.
- Full mathematical derivations and implementation details are available in the [Software Architecture Report](Software-Architecture-Report.pdf).

### Object Detection and Tracking
- The robot tracks green tennis balls in real time using computer vision.
- Each video frame is processed to isolate pixels matching the ball’s color, with filtering steps applied to reduce noise.
- Detected ball regions are identified as contours, and the position of each object is calculated from the contour center.
- Object positions are updated continuously, and smooth motion is achieved by interpolating between positions over time.
- This approach demonstrates real-time image processing, object tracking, and integration with motion control algorithms.


## Technologies Used
- Python
- OpenCV 
- Numpy
- Matplotlib
- Raspberry Pi 
- Motors / chassis 
  
