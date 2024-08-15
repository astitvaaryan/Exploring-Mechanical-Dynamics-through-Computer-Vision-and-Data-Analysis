# Exploring-Mechanical-Dynamics-through-Computer-Vision-and-Data-Analysis
This repository contains a series of experiments conducted as part of the Statics and Dynamics course under Professor Jayaprakash K R at IIT Gandhinagar. These experiments explore key concepts in mechanical dynamics, integrating advanced computational techniques such as MATLAB-based image processing and data analysis.

## Experiments

### 1. Velocity and Acceleration of a Moving Particle in a Rotating Frame
- **Objective**: This experiment focuses on analyzing the velocity and acceleration of a moving particle in a rotating reference frame, particularly investigating the Coriolis effect.
- **Tools Used**:
  - **MATLAB Image Processing Toolbox**: Used to process video recordings, extracting positional data by breaking down the motion into individual frames for precise analysis.

### 2. Application of Newton's Second Law in Inertial and Non-Inertial Reference Frames
- **Objective**: The goal of this experiment is to design and analyze an experimental setup that demonstrates the application of Newton's Second Law in both inertial and non-inertial reference frames. The experiment aims to highlight how Newton's Second Law holds true in inertial frames but fails in non-inertial frames unless additional fictitious forces are introduced.
- **Tools Used**:
  - **MATLAB Image Processing Toolbox**: Utilized to analyze video footage of the experiment, tracking the motion of objects to accurately measure their acceleration in different frames.
  - **Phyphox Application**: The Phyphox app was used to measure acceleration in real-time during the experiment, providing precise data for both inertial and non-inertial frames.

### 3. Planar Four-Bar Linkage Mechanism Analysis
- **Objective**: This experiment involves designing a planar four-bar mechanism where one link (the crank) rotates continuously at a constant angular velocity, and the opposite link (the rocker) rotates partially. The goal is to determine the velocity of the center of mass of the coupler link (which connects the crank and rocker) and its angular velocity for at least six different crank angles. The velocities are analyzed using three methods: analytically, experimentally, and through simulation using MSC Adams.
- **Tools Used**:
  - **MSC Adams**: Used for simulating the four-bar linkage mechanism. Adams provided a virtual environment to analyze the kinematic behavior, including the velocity of the center of mass of the coupler link and its angular velocity at various crank angles.
  - **MATLAB Image Processing Toolbox**: Applied to process video footage of the experimental setup, tracking the motion of the coupler link. This data was crucial for experimentally determining the velocities.
  - **Python (Data Analysis)**: Python scripts were used for processing the experimental data and comparing it with both the analytical solutions and the simulation results from Adams.

## Acknowledgements
Special thanks to Professor Jayaprakash K R for his guidance and support throughout these experiments.


