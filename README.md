<h1 align="center">Salvador Pérez Lago</h1>
<h3 align="center">AI Engineer · Computer Vision · Robotics</h3>

<p align="center">
  <a href="mailto:salva.perez.lago@gmail.com">salva.perez.lago@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/salvador-pérez-lago-a866352b2/">LinkedIn</a> &nbsp;·&nbsp;
  A Pobra do Caramiñal, Spain
</p>

---

AI and Computer Vision Engineer with a BSc in Robotics (USC) and an MSc in AI (UNIR). Currently building end-to-end deep learning pipelines for industrial food processing at **Marexi Marine Technology** — pushing foreign object detection from 60% to 85% accuracy on high-speed conveyor belts using CNNs, semantic segmentation and ONNX inference.

My background bridges software and hardware: from writing Arduino firmware for multi-sensor data acquisition to training LSTM/GRU networks, from full quadrotor dynamics models to gesture-controlled robots over IP cameras.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat&logo=ros&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878A?style=flat&logo=arduino&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Languages:** Python · C++ · C#  
**Deep Learning:** TensorFlow · PyTorch · Keras · ONNX · CNN · RNN/LSTM/GRU · NLP  
**Computer Vision:** OpenCV · MediaPipe · Matrox Imaging Library  
**Robotics:** ROS · ROS2 · RAPID · KRL  
**Data:** Pandas · NumPy · Scikit-Learn · Seaborn · Plotly  
**Industrial:** Beckhoff TwinCAT · Siemens · Omron PLC · HMI/SCADA  

---

## Projects

### Thesis Projects

| Project | Description | Stack |
|---|---|---|
| [Skin Lesion Segmentation](https://github.com/salvalago23/tfe_salvador_perez_lago) | MSc thesis. Comparative study of 6 segmentation architectures (U-Net, Attention U-Net, Residual U-Net, U-Net++, DeepLabV3+, TransUNet) on ISIC 2018. Includes a full-stack FastAPI web app for clinical use with automated ABCD dermoscopic analysis. | PyTorch · FastAPI · Albumentations |
| [Offline RL with Uncertainty](https://github.com/salvalago23/tfg_salvador_perez_gr) | BSc thesis. Model-based offline RL: neural network ensembles estimate per-state uncertainty so agents (Q-Learning, DQN, DDQN) learn to avoid undemonstrated regions of a grid environment. | PyTorch · DQN · DDQN |
| [GPS Dead Reckoning](https://github.com/salvalago23/gps_quanvia) | MSc internship (Quanvia). Arduino firmware collecting 5 sensors → LSTM/GRU models predict GPS position deltas → Kalman filter fuses predictions with real GPS. 11 real-world trajectories. Includes a synthetic data simulator. | Arduino · TensorFlow · Kalman |

### Robotics & Control

| Project | Description | Stack |
|---|---|---|
| [Gesture Robot Control](https://github.com/salvalago23/gesture-robot-control) | Hand gesture UI via IP camera controls a ROS robot: manual, automatic route, freestyle and draw-route modes. Multi-threaded with TFLite classifier. | Python · MediaPipe · ROS |
| [Mecanum Robot Simulator](https://github.com/salvalago23/mecanum-robot) | Inverse kinematics and proportional controller for an omnidirectional Mecanum-wheeled robot with real-time Matplotlib animation. | Python · NumPy |
| [Drone Autopilot PD](https://github.com/salvalago23/drone-autopilot-pd) | Full quadrotor dynamics model (rotation matrices, Euler rates, rotor forces) with nested PD loops for position and attitude control. | Python · NumPy |
| [EKF Localisation](https://github.com/salvalago23/ekf-localisation) | Extended Kalman Filter for robot localisation from scratch: prediction + multi-landmark update with Kronecker product handling. | Python · NumPy |
| [RRT* 3D Path Planning](https://github.com/salvalago23/rrt-star-3d) | 3D drone path planner using RRT* (with rewiring) around volumetric obstacles, visualised in real-time 3D Matplotlib. | Python · NumPy |
| [Flocking Swarm C++](https://github.com/salvalago23/flocking-swarm) | Reynolds' flocking model (alignment, separation, cohesion) for 80 robots in C++14 with experimentally tuned weights. GTK+ visualisation. | C++14 · GTK+ |
| [Genetic Algorithm ROS](https://github.com/salvalago23/genetic-algorithm-ros) | GA evolving neural robot controllers in Gazebo: 6 parallel simulation threads, diversity-preserving mutation mechanism. | Python · ROS · Gazebo |

### Computer Vision

| Project | Description | Stack |
|---|---|---|
| [Classroom Attention Monitor](https://github.com/salvalago23/classroom-attention-cv) | Real-time gaze direction, eye state and hand gesture detection running in two parallel threads with a "virtual teacher" FSM. | Python · OpenCV · MediaPipe · TFLite |
| [Traffic Counting CV](https://github.com/salvalago23/traffic-counting-cv) | Vehicle tracking and bidirectional counting in traffic video: MOG2 background subtraction, Canny night mode, centroid tracker, 9-line crossing detection. | Python · OpenCV |
| [DLT Camera Calibration](https://github.com/salvalago23/dlt-camera-calibration) | Direct Linear Transform calibration: builds 12×12 matrix from 3D-2D correspondences, SVD for projection matrix P, QR factorisation into K/R/t. | Python · NumPy |

### AI & Machine Learning

| Project | Description | Stack |
|---|---|---|
| [CIFAR-10 CNN](https://github.com/salvalago23/cifar10-cnn) | CNN reaching 88.57% accuracy on CIFAR-10. Full ablation study: batch norm, dropout, data augmentation, LR scheduling, optimizer comparison. Modern tf.data pipeline. | TensorFlow · Keras |
| [Amazon Warehouse A*](https://github.com/salvalago23/amazon-warehouse-astar) | A* with rotation-aware costs for a 16×16 warehouse robot. Six progressive versions from basic to multi-order with timing statistics. | Python |
| [PDDL AI Planning](https://github.com/salvalago23/pddl-ai-planning) | ROSPlan integration with custom PDDL domain for Turtlebot task planning. Also includes a planetary rover domain (9 actions, communication chain). | PDDL · ROS |
| [Clustering Industrial Sensors](https://github.com/salvalago23/clustering-industrial-sensors) | K-Means / DBSCAN / Agglomerative on industrial machinery sensor data. DBSCAN grid search with heatmap, polar cluster profiles with Plotly. | Scikit-Learn · Plotly |
| [Transformer from Scratch](https://github.com/salvalago23/transformer-from-scratch) | Manual TransformerBlock (MultiHeadAttention + LayerNorm + FFN) vs dense baseline on Newsgroups20 (15k texts, 20 classes). | TensorFlow · Keras |

---

## Education

| Degree | Institution | Years |
|---|---|---|
| MSc Artificial Intelligence | Universidad Internacional de La Rioja (UNIR) | 2024 – 2026 |
| BSc Robotics | Universidade de Santiago de Compostela | 2020 – 2024 |
| Higher Vocational Training — Industrial Automation & Robotics | IES Macías O Namorado | 2018 – 2020 |

---

<p align="center">
  <a href="mailto:salva.perez.lago@gmail.com">salva.perez.lago@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/salvador-pérez-lago-a866352b2/">LinkedIn</a>
</p>
