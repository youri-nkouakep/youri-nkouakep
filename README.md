<h1 align="center">Youmbi Nkouakep Youri Thibault</h1>
<p align="center">
  <b>AI & Robotics Engineering Student</b> · Computer Vision · Autonomous Systems · Data
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/youri-nkouakep"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:yourinkouakep@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 👋 About me

I'm Youri, a final-year master's student in AI and Connected Objects at Université Ibn Tofail (Morocco), currently on exchange at UTBM in France, in the robotics and autonomous systems track with a focus on computer vision.

What I enjoy most is taking an idea all the way to something that runs: a robot that delivers a parcel in Gazebo, a webcam that reads a tic-tac-toe board drawn on paper, an app that screens resumes. I try to measure everything I build, and to be honest in my READMEs about where it still fails.

- At UTBM I work on real robots (TurtleBot) with ROS 2, and I'm preparing the ROS 2 certification from The Construct
- **I'm looking for a 6-month end-of-studies internship** in AI, computer vision, data science or robotics

---

### 🚀 Projects

| Project | What it does | Stack | Status |
|---|---|---|---|
| [**SmartRecruit**](https://github.com/youri-nkouakep/SmartRecruit) | Full-stack resume screening app. Reads scanned resumes with OCR and layout analysis (F1 0.95), classifies them with a fine-tuned DistilBERT, ranks candidates with hybrid search (MRR 0.92), and explains each match with a local LLM that has to cite the resume. Includes a bias audit on names | PyTorch · Transformers · FAISS · OpenCV · FastAPI · React | 🟢 Done |
| [**3D Perception**](https://github.com/youri-nkouakep/3D-perception-with-deep-learning) | From one object to a full street scene, in three steps, all trained on a laptop CPU. PointNet classifies point clouds (88.6 % on ModelNet40, 89.2 % in the paper), a U-Net estimates depth from a single photo (AbsRel 0.204 on NYU, better than Eigen et al. with 150x less data), and a light PointPillars finds cars in KITTI LiDAR scans (66.6 % AP BEV, 38.5 % AP 3D) | PyTorch · Point clouds · LiDAR · U-Net | 🟢 Done |
| [**RoboAgents**](https://github.com/youri-nkouakep/RoboAgents) | Give a delivery robot an order in plain French ("bring this parcel to the office, then come back"). A multi-agent system around an LLM understands the order, plans the steps, has a rule-based critic check the plan against the map, and turns it into ROS 2 / Nav2 goals for PatrolBot. The LLM only handles place names, never coordinates, and runs locally with Ollama or through any OpenAI-compatible API | LLM agents · Ollama · pydantic · ROS 2 · Nav2 | 🟡 In progress (step 1/3) |
| [**TicTacToe Vision**](https://github.com/youri-nkouakep/tictactoe-vision) | Play on paper against an AI that never loses. The board is found from any 2 of its 4 ArUco markers, a CNN trained on synthetic photos reads the cells in C++ via ONNX. 98.9 % of hard boards read correctly, 47 ms per frame | C++ · OpenCV · PyTorch · ONNX · CMake | 🟢 Done |
| [**PatrolBot**](https://github.com/youri-nkouakep/PatrolBot) | Autonomous delivery robot. Missions arrive through a REST API, Nav2 drives the robot, an 8-state FSM handles the delivery code and every failure, and the robot unsticks itself | ROS 2 · Nav2 · Gazebo · FastAPI | 🟡 Improving |
| [**MédiPredict**](https://github.com/youri-nkouakep/Medipredict) | Chronic disease risk on 280k records. XGBoost (AUC 0.940, calibrated), SHAP explanation for each patient, a generalization test that shows the real-world limits, and MLOps (MLflow, CI quality gate, drift monitoring) | XGBoost · SHAP · MLflow · FastAPI · Docker | 🟢 Done |
| [**parking-control**](https://github.com/youri-nkouakep/parking-control) | My part of the UTAC Challenge team: controlling an autonomous Renault Zoé. Pure Pursuit gives 5.5 cm RMS lateral error in a 90° turn (simulation). Next: Hybrid A\* and MPC | ROS · Python | 🟡 In progress |
| [**Customer Segmentation**](https://github.com/youri-nkouakep/customer-segmentation) | RFM segmentation of 4,338 customers (K-means vs CAH vs GMM) and 6-month lifetime value with BG/NBD and Gamma-Gamma. [Live demo](https://youri-customer-segmentation.streamlit.app/) | scikit-learn · SciPy · Streamlit | 🟢 Live |

---

### 🧰 Tech stack

**Robotics** &nbsp;
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=flat-square&logoColor=white)

**AI, NLP & Vision** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Point clouds / LiDAR](https://img.shields.io/badge/Point_clouds_%2F_LiDAR-2b6c8f?style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![LLM agents / RAG](https://img.shields.io/badge/LLM_agents_%2F_RAG-1f4632?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract_OCR-3c7558?style=flat-square)

**Data & ML** &nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Web & backend** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Tools** &nbsp;
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

---

### 🎯 What I'm working on now

- Hybrid A\* planning and MPC for the UTAC Challenge vehicle
- RoboAgents: connecting the LLM agents to PatrolBot in Gazebo, then a benchmark of several LLMs
- New features for PatrolBot
- The ROS 2 certification and the MathWorks Onramps (MATLAB, Machine Learning, Deep Learning)

<p align="center"><i>Hiring an intern in AI, vision or robotics? I'd be glad to talk: yourinkouakep@gmail.com</i></p>
