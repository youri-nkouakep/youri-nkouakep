<h1 align="center">Youmbi Nkouakep Youri Thibault</h1>

<p align="center">AI · Computer vision · Robotics and autonomous systems</p>

<p align="center">
  <a href="https://www.linkedin.com/in/youri-nkouakep"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:yourinkouakep@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

I'm in the final year of a master's in AI and Connected Objects at Université Ibn Tofail (Morocco), and currently on exchange at UTBM (France) in the robotics and autonomous systems track, computer vision specialization. At UTBM I work on real robots like the TurtleBot, and I'm preparing the ROS 2 certification from The Construct.

I build projects end to end, from raw data or sensor input to something that runs, and I measure them: each repo has its numbers, its tests, and a section on what doesn't work yet.

**I'm looking for a 6-month end-of-studies internship** in AI, computer vision, data science or robotics.

## Projects

**[SmartRecruit](https://github.com/youri-nkouakep/SmartRecruit)** · AI resume screening, full-stack web app<br>
Reads scanned or digital resumes (OCR and layout analysis, field F1 0.95 on degraded scans), sorts them into job families with a fine-tuned DistilBERT, ranks candidates for an offer with hybrid search and re-ranking (MRR 0.92), and explains each match with a local LLM that must cite the resume. A counterfactual audit checks whether a candidate's name changes the result.<br>
`PyTorch` `Transformers` `FAISS` `Tesseract` `OpenCV` `FastAPI` `React` `TypeScript`

**[TicTacToe Vision](https://github.com/youri-nkouakep/tictactoe-vision)** · Computer vision in C++<br>
Play tic-tac-toe on paper against an engine that never loses. The camera finds the board from any 2 of its 4 ArUco markers, a small CNN trained only on synthetic photos reads each cell, and the reply is drawn back on the image. 98.9 % of hard boards read correctly, 47 ms per frame on CPU.<br>
`C++17` `OpenCV` `PyTorch` `ONNX` `CMake`

**[PatrolBot](https://github.com/youri-nkouakep/PatrolBot)** · Autonomous delivery robot<br>
A TurtleBot3 receives a mission through a REST API, drives to the address with Nav2, checks a delivery code at the door and returns to base. An 8-state mission FSM handles every failure, and the robot gets itself unstuck when odometry shows it isn't moving. Simulated in a custom Gazebo city; still being improved.<br>
`ROS 2 Humble` `Nav2` `Gazebo` `Python` `FastAPI`

**[3D Perception with Deep Learning](https://github.com/youri-nkouakep/3D-perception-with-deep-learning)** · *in progress*<br>
From a single object to a full street scene in three steps. Step 1 is done: PointNet on ModelNet40 reaches 88.6 % accuracy (89.2 % in the paper), trained in 5 hours on a laptop CPU. Next: monocular depth estimation on NYU Depth v2, then 3D object detection in KITTI LiDAR scans.<br>
`PyTorch` `Point clouds` `pytest`

**[MédiPredict](https://github.com/youri-nkouakep/Medipredict)** · Machine learning and MLOps<br>
Chronic disease risk screening on 280k patient records, team project where I led the modeling and the app. XGBoost reaches an AUC of 0.940 with good calibration and a SHAP explanation per patient. Testing on a source never seen in training shows the real-world AUC is closer to 0.71–0.81, and the README explains why. MLflow tracking, CI with a model quality gate, drift monitoring.<br>
`XGBoost` `PyTorch` `SHAP` `MLflow` `FastAPI` `MySQL` `Docker`

**[parking-control](https://github.com/youri-nkouakep/parking-control)** · Autonomous vehicle control · *in progress*<br>
My part of the UTBM team for the UTAC Challenge: steering and speed control of an autonomous Renault Zoé for the parking event. Pure Pursuit with GPS/odometry pose filtering gives 5.5 cm RMS lateral error in a 90° turn (simulation). Next: Hybrid A* planning and MPC.<br>
`ROS Noetic` `Python` `Unity simulator`

**[Customer Segmentation](https://github.com/youri-nkouakep/customer-segmentation)** · Data science · [live demo](https://youri-customer-segmentation.streamlit.app/)<br>
RFM segmentation of 4,338 retail customers (K-means, hierarchical clustering and GMM compared, with a stability check) and their 6-month value with BG/NBD and Gamma-Gamma models written from the original papers. Champions are 16 % of customers and 64 % of revenue.<br>
`scikit-learn` `SciPy` `pandas` `Streamlit`

## Skills

| | |
|---|---|
| **Machine learning** | PyTorch, scikit-learn, XGBoost, LightGBM, SHAP, model calibration, bootstrap confidence intervals |
| **NLP and LLMs** | Transformer fine-tuning, sentence embeddings, FAISS, BM25, re-ranking, RAG with local LLMs |
| **Computer vision** | OpenCV, CNNs, homography and ArUco, OCR (Tesseract), ONNX deployment, point clouds (PointNet) |
| **Robotics** | ROS 2, ROS 1, Nav2, Gazebo, path tracking (Pure Pursuit), state machines, TurtleBot |
| **Data** | pandas, NumPy, SciPy, SQL (MySQL), Streamlit dashboards |
| **Engineering** | Python, C++17, TypeScript, FastAPI, React, Docker, GitHub Actions, MLflow, CMake, pytest, Linux |

## Right now

- Monocular depth estimation, step 2 of the 3D perception project
- Hybrid A* and MPC for the UTAC Challenge vehicle
- ROS 2 certification

<p align="center"><sub>yourinkouakep@gmail.com · <a href="https://www.linkedin.com/in/youri-nkouakep">LinkedIn</a></sub></p>
