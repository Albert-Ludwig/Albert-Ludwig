<div class="cv-header" style="text-align: center;">
  <h1>Haoran (Johnson) Ji</h1>
  <p>
    Toronto, ON |
    (+1) 647-564-1191 |
    <a href="mailto:johnsonji0602@gmail.com">johnsonji0602@gmail.com</a> |
    <a href="http://www.linkedin.com/in/haoran-ji-7ab3a9311">LinkedIn</a>
  </p>
</div>

## EDUCATION

**McMaster University**

- B. Eng in Mechatronics Engineering
- Sep 2023 – Apr 2027 (Expected)
- CGPA: 3.94/4.0

## RESEARCH INTERESTS

Mathematical foundations of robotics, particularly geometric methods for robot motion, control theory, and optimization, with an emphasis on the system-level design and control of autonomous robotic systems.

## INDUSTRIAL & RESEARCH EXPERIENCES

### Undergraduate Research Assistant in Autonomous Robotics & Convex Optimization (ARCO) Lab

- **_McMaster University, Autonomous Robotics & Convex Optimization (ARCO) Lab_**
- _Sep 2026 - now, Hamilton, ON, Canada_
- _Supervisor: Dr. Matthew Giamou_

_WELL-E: Gaussian Process-Based Informative Path Planning for Environmental Reconstruction_

- Developing a 3D Gaussian Process–Greedy Recursive Growth (GP–GRG) framework for informative robotic sampling, planning sampling locations and paths to improve environmental-field reconstruction from limited measurements.
- Benchmarking Gaussian process kernels to evaluate their effects on reconstruction accuracy and uncertainty estimates within the informative path-planning framework.
- Planning ROS 2 Nav2 integration for navigation and motion control, with subsequent deployment on a Bunker Mini for environmental data collection and field testing on the McMaster University campus.

### Autonomous Robotics & Systems Research CO-OP (Rising Stars Program)

- **_Autonomous Systems Laboratory, University of Waterloo_**
- _May 2026 – August 2026, Waterloo, ON, Canada_
- _Supervisor: Prof. Stephen L. Smith_

_Diffusion-Based Social Navigation for a Clearpath Jackal_

- Implemented an end-to-end autonomous point-to-point navigation system for a Clearpath Jackal by extending and integrating an existing diffusion-based social-navigation policy into a modular ROS 2 Humble stack; the robot accepted a target pose, continuously generated and executed obstacle-avoiding motion commands from live odometry, LiDAR, occupancy-map, and pedestrian observations, and navigated to the goal without manual teleoperation.
- Implemented the policy-to-control interface and integrated acados trajectory projection to convert policy outputs into constrained linear and angular velocity commands, with watchdog, stale-data, emergency-stop, and LiDAR collision safeguards.
- Built dynamic pedestrian scenarios in HuNavSim and Gazebo and RViz diagnostics to evaluate goal reaching, pedestrian avoidance, path efficiency, oscillation, and overshoot; tuned control timing and limits from closed-loop tests.
- Ported the full stack from ROS 2 Jazzy and Ubuntu 24.04 to ROS 2 Humble and Ubuntu 22.04, and created reproducible GPU-enabled Docker/WSL launch, configuration, and recovery workflows for simulation and hardware experiments.
- Deployed the end-to-end pipeline on a physical Clearpath Jackal at Waterloo RoboHub, integrating saved-map localization, RGB-D person detection, live LiDAR, TF, and the hardware velocity-command interface; validated goal reaching by stopping 0.249 m from the target within a 0.25 m tolerance.

Second author of SoGuDiff, an arXiv preprint on diffusion-based social navigation and real-robot deployment (arXiv:2609.30560, 2026).

### Automation Engineering Intern

- **_B&R Industrial Automation (ABB)_**
- _May 2025 – August 2025, Shanghai, China_
- Contributed to the design and implementation of a six-axis robotic-arm control system in Automation Studio and SceneView, including kinematic modeling, joint-motion control, and task-level coordination; developed a MappView HMI for real-time state visualization, parameter tuning, motion triggering, and system monitoring.
- Developed a Python application for real-time OPC UA data acquisition and analysis, integrating live visualization, curve fitting, and diagnostic charts to support industrial-system monitoring and performance evaluation.
- Built a domain-specific LLM question-answering assistant using Dify, Python, and retrieval-augmented generation (RAG); implemented knowledge-base preprocessing, indexing, and retrieval, and integrated nonlinear curve-fitting and data-modeling functions.

### Undergrad RA in Image Processing

- **_McMaster University, Undergraduate Research Assistant_**
- _February 2024 – June 2024, Hamilton, ON, Canada_
- _Supervisor: Dr. Jun Chen_

Machine-Learning-Based RAW Image Deblurring

- Investigated Python-based machine-learning methods for RAW image deblurring, focusing on compensating for motion blur and image degradation while preserving sensor-level information.
- Developed preprocessing pipelines for RAW data, including normalization, noise handling, and format conversion for model training.
- Evaluated reconstruction quality using quantitative image-quality metrics, visualized experimental results, and contributed to iterative model refinement.

## PUBLICATIONS

**Christian Schaible, Haoran Ji, Yash Vardhan Pant, and Stephen L. Smith.**\
“SoGuDiff: Socially Guided Diffusion for Steerable, Norm-Grounded Robot Navigation.”\
*Submitted to IEEE Robotics and Automation Letters (RA-L), currently under review, 2026.*\
[arXiv:2609.30560](https://arxiv.org/abs/2609.30560?utm_source=chatgpt.com)

## SELECTED PROJECTS

### STM32F4 Line-Following Mobile Robot

_MECHTRON 2TA4 — Embedded Systems Design I | Jan.–Apr. 2025_

- Designed and assembled an STM32F4-based mobile robot, integrating the mechanical chassis, optical reflectance sensing, DC motor actuation, and onboard power subsystem.

- Developed C++ firmware and PWM-based feedback control to convert sensor measurements into steering and motor-speed commands for autonomous traversal of curved and sharp-turn track segments.

### Pacemaker Controller-Monitor System

_MECHTRON 3K04 — Software Development | Sep.–Dec. 2025_

- Led a five-member team through task allocation, schedule coordination, system integration, testing, and final demonstration of a pacemaker controller-monitor prototype.

- Developed a multithreaded Python/Tkinter Device Controller-Monitor for real-time electrogram visualization and parameter validation, and implemented checksum-validated UART communication with an NXP K64F controller in Simulink.

## TECHNICAL SKILLS

- **Control & Optimization:** acados, constrained trajectory projection, closed-loop motion control, kinematic modeling, genetic programming, Simulink
- **Robotics & Autonomous Systems:** ROS 2 (Humble, Jazzy), Clearpath Jackal, autonomous point-to-point navigation, obstacle avoidance, Gazebo, RViz, HuNavSim
- **Programming & Systems:** Python, C++, Docker, WSL 2, Ubuntu/Linux, Git
- **Machine Learning & Perception:** PyTorch, diffusion-model inference, RGB-D person detection, RAW image processing
- **Embedded & Industrial Automation:** STM32F4, NXP K64F, UART, PWM, OPC UA, Automation Studio, SceneView, MappView
