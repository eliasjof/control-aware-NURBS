# Supplementary Material for: 
## **Deliberative Control-Aware Motion Planning for Kinematic-Constrained UAVs in a Dynamic Environment**

This repository contains supplementary materials related to the paper titled **"Deliberative Control-Aware Motion Planning for Kinematic-Constrained UAVs in a Dynamic Environment"**. 

## Paper Abstract

This paper introduces a motion planning approach for navigating in a dynamic environment. The path is represented using a Non-Uniform Rational B-Spline (NURBS) to ensure smoothness, curvature continuity, and proper orientation by adjusting its parameters. A Differential Evolution algorithm optimizes the curve parameters and traversal speed at each re-planning interval, taking into account speed limits, maximum curvature, and obstacles in the environment. A constraint based on the Velocity Obstacle (VO) ensures collision-free motion, considering bounds provided by lower-level controllers. The feasibility of the approach is validated through simulations and real-world experiments with the Crazyflie 2.1 micro quadcopter.

## Contents

### 1. Figures
The folder `figures/` contains high-resolution images used in the paper. These figures include:

- Fig.1: Worst conservative avoidance scenario
- Fig.2: Comparison between our motion planner with VO constraint and without VO constraint, using a naive projection of the obstacles and checking collision along the trajectory.
- Fig.3: Snapshots of the simulated robot's motion in an environment with 50 obstacles
- Fig.4: Speed profiles of the UAV over time.
- Fig.5: Snapshots of the recorded robot's motion in an environment with five virtual obstacles


### 2. Videos
The folder `videos/` contains the following video demonstrations:

- **Simulation Experiments**: These videos illustrate the UAV's path planning and navigation behavior in dynamic environments during simulation. The videos demonstrate how the Non-Uniform Rational B-Spline (NURBS) is optimized for smoothness, curvature continuity, and obstacle avoidance.
  - `simulation_experiment_1.mp4`
  - `simulation_experiment_2.mp4`

- **Real-World Experiments**: These videos showcase the Crazyflie 2.1 micro quadcopter navigating in real-world environments based on the proposed motion planning algorithm. The videos highlight the quadcopter's ability to avoid obstacles and dynamically re-plan its trajectory in real-time.
  - `real_robot_experiment_1.mp4`
  - `real_robot_experiment_2.mp4`



## How to Cite

If you use any material from this repository, please cite the paper:



## Contact

For any questions or further information, please contact [Elias J R Freitas] at [Email].

