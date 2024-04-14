
## Autonomous Robot Navigation Using Optical Flow-Based Obstacle Avoidance

This repository hosts the implementation and complete documentation of a cutting-edge autonomous navigation system for mobile robots, utilizing optical flow-based obstacle avoidance techniques. Developed by a team from the University of Maryland, this project harnesses the power of optical flow data captured by a single camera to enable sophisticated navigation and obstacle evasion in complex environments.

## Repository Contents

- **FOE_new.py** - Calculates the Focus of Expansion (FOE) from optical flow data.
- **optical_flow.py** - Core implementation of optical flow algorithms.
- **distancesensor.py** - Handles distance sensing for obstacle detection.
- **ei_monitor.py** - Monitors execution and system performance metrics.
- **motordriver_lite.py** - Manages motor responses based on navigational inputs.
- **optflow_util.py** - Utility functions for optical flow calculations.
- **optical_flow_control.py** - Integrates optical flow data into the motor control system.
- **picam2multithread.py** - Manages camera operations using a multithreaded approach.
- **TTC+depth.py** - Computes Time-to-Contact (TTC) and depth estimations from optical flow.
- **Research Paper.pdf** - Detailed documentation covering methodologies, experiments, and results.

## Setup and Running Instructions

### Prerequisites
Ensure Python is installed along with the following packages: NumPy, OpenCV, Matplotlib, and other relevant libraries for image processing and hardware interface.

1. **Clone the repository:**
   ```
   git clone <https://github.com/kalavagunta-vamshi/Autonomous-Robot-Navigation-Using-Optical-Flow-Based-Obstacle-Avoidance.git>
   cd <https://github.com/kalavagunta-vamshi/Autonomous-Robot-Navigation-Using-Optical-Flow-Based-Obstacle-Avoidance.git>
   ```

2. **Install required libraries:**
   ```
   pip install numpy opencv-python matplotlib
   ```

3. **Execute the main script to run the autonomous robot**
   ```
   optical_flow_control.py
   ```

## Project Overview

### Introduction
Employing a Raspberry Pi 3 equipped with a PiCamera 2, this system integrates advanced optical flow algorithms, such as the Lucas-Kanade and Gunnar Farneback methods, to provide real-time navigation capabilities. Techniques like the focus of expansion (FOE), time-to-contact (TTC), and depth mapping are central to its ability to understand and navigate the environment.

### Technologies and Techniques
- **Optical Flow Computation**: Utilizes both sparse and dense optical flow methods to detect and react to environmental changes.
- **Hardware Setup**: Built on Raspberry Pi 3 and PiCamera 2, optimized for low-power, effective real-time processing.
- **Algorithmic Innovations**: Includes implementations for FOE detection, TTC calculation, and real-time motor control based on sensory data.

### Demonstration Videos
Watch our system in action in various testing scenarios:
- [Navigation in an Enclosed Arena 1](https://drive.google.com/file/d/1Kyi-XHULSolmZ1Yvu_x-AtzaH3ZCqBX-/view?usp=drive_link)
- [Navigation in an Enclosed Arena 2](https://drive.google.com/file/d/1V-B7K9e8r10P9FsO0sNeUwOI4MhRgyO-/view?usp=drive_link)


## Contributions
 Yi-Chung Chen,  Vamshi Kalavagunta,  Weili Su,  Zidong Zha, Ji Liu.

