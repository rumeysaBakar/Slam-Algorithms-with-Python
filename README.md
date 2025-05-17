# Slam-Algorithms-with-Python

This repository demonstrates various Simultaneous Localization and Mapping (SLAM) algorithms using basic Python implementations. Each notebook or script showcases a different SLAM approach, intended for educational purposes, prototyping, or Medium articles.

##  What is SLAM?

**Simultaneous Localization and Mapping (SLAM)** is the computational problem of constructing or updating a map of an unknown environment while simultaneously keeping track of an agent's location within it. It is widely used in robotics, autonomous vehicles, and AR/VR technologies.

##  Implemented SLAM Algorithms

The following SLAM variants are implemented in this repository:

- **EKF-SLAM (Extended Kalman Filter SLAM)**  
  Uses probabilistic filtering to estimate robot position and landmark locations with uncertainty.

- **Graph-Based SLAM**  
  Constructs a graph of robot poses and constraints, and solves it via optimization techniques.

- **LiDAR-Based SLAM**  
  Demonstrates SLAM using synthetic LiDAR measurements for obstacle-based mapping.

- **Visual SLAM (ORB-SLAM)**  
  Uses ORB (Oriented FAST and Rotated BRIEF) feature extraction and matching between video frames.

- **Deep Learning-Based SLAM**  
  Explores modern SLAM systems enhanced by neural networks and deep features.


Each `.ipynb` file contains:
- Clean, commented Python code
- Visual outputs and simulations
- Brief theoretical background in markdown cells

##  Getting Started

Clone the repository and open the notebooks using Google Colab or Jupyter Notebook:

```bash
git clone https://github.com/rumeysaBakar/Slam-Algorithms-with-Python.git

