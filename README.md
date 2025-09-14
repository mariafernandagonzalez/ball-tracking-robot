# Computer Vision Detection and Tracking Robotics Project
A mobile robot that uses computer vision and real-time image processing to detect and track a ball. Developed in Caltech’s Introduction to Robotics course, this project focused on vision-based algorithms, image filtering, and motion planning. The system processes live video input to identify and follow a moving ball, demonstrating autonomous behavior through software-driven control. Watch the [DEMO](https://www.youtube.com/watch?v=-PGfyatwvf8).

<p align="center">
  <img src="Front-View-of-Robot.png" width="400">
</p>

## Features
### Smooth Motion Control
- The robot calculates motor positions and velocities along a cubic spline trajectory at each time step.
- This ensures fluid movement without abrupt starts or stops, improving tracking performance.
- Full mathematical derivations and implementation details are available in the [project report](docs/project_report.pdf).
