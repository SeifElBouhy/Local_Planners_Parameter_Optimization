# Local Planner Parameter Optimization in ROS 2

Welcome to the **Local Planner Parameter Optimization** repository! This repository provides an in-depth analysis and optimization guidelines for several local planning algorithms implemented in **ROS 2**. The goal is to improve the efficiency, consistency, and behavior of local planners in dynamic and unknown environments.

## Documentation Overview

For a comprehensive understanding of each local planner and its optimization process, please refer to the following detailed documents available in the `docs/` directory:

- **[DWB Parameter Optimization in ROS 2](docs/DWB_Parameter_Optimization_in_ROS2.pdf)**  
  Explore how the **Dynamic Window Approach (DWB)** planner can be fine-tuned to navigate the robot effectively through various environments. This document dives deep into the parameter settings, considerations for optimization, and real-world application scenarios.

- **[MPPI Parameter Optimization in ROS 2](docs/MPPI_Parameter_Optimization_in_ROS2.pdf)**  
  Learn about the **Model Predictive Path Integral (MPPI)** method and how its parameters can be optimized to enhance trajectory planning and handling of dynamic obstacles. The document also covers the trade-offs between computational cost and planner performance.

- **[RPP Parameter Optimization in ROS 2](docs/RPP_Parameter_Optimization_in_ROS2.pdf)**  
  This document delves into the **Rapidly-exploring Random Tree (RPP)** method, focusing on parameter adjustments to improve efficiency in tight spaces while maintaining robustness against obstacles.

- **[Tuned Parameters for Each Local Planner](docs/parameters.pdf)**  
  A dedicated file showcasing the tuned parameters for **DWB**, **MPPI**, and **RPP** local planners. This includes the optimal values obtained after rigorous testing to enhance performance across different environments.

- **[Evaluation Metrics](docs/metrics.pdf)**  
  In this file, we describe the **evaluation metrics** used to assess the effectiveness of the local planners. From path smoothness to obstacle avoidance and goal completion, these metrics provide a standardized way to measure the success of each planner.
