---
layout: project
type: project
image: img/tmai/tm_pic.png
title: "Trackmania AI"
date: 2024
published: true
labels:
  - Python
  - Angelscript
  - TMInterface
  - Socket Programming
summary: 'Trackmania AI (TMAI) is a project that integrates with the Trackmania game to develop and train AI agents. Utilizing TMinterface for real-time data interaction and performance tracking, the system features advanced agent "vision," edge and curve prediction, and a reward system for optimizing gameplay.'
---

**Project Description:**
A sophisticated AI system developed to interact with Trackmania, designed to read game data, send control inputs, and optimize agent performance through real-time communication and advanced image processing.

**Key Features:**
- **TMinterface Integration:** Utilized TMinterface to directly interact with Trackmania, allowing the plugin to read game data and send control inputs. TMinterface details: [https://donadigo.com/tminterface/](https://donadigo.com/tminterface/)
- **Socket Connection:** Established a socket connection on localhost port 8000 to facilitate real-time communication between the game plugin and Python code. [Figure 1]
- **Game State Monitoring:** Designed the system to read game state changes, trigger the execution of agents, and collect performance data. [Figure 2]
- **Reward System:** Implemented a reward system that evaluates agents based on track completion time, medals earned, average speed, and crash count, driving the evolutionary process. [Figure 3]
- **Agent Vision:** Developed agent "vision" by capturing screenshots of the Trackmania tab, applying preprocessing, and cropping around a region of interest (ROI). [Figure 4]
- **Edge and Curve Prediction:** Enabled agents to use edge and curve prediction for navigation, allowing them to recognize borders and navigate effectively. [Figure 5]
- **Extensive Testing:** Conducted extensive testing to fine-tune the algorithm and improve the overall performance and reliability of the agents.

**Technologies Used:**
- Python
- OpenCV
- Socket Programming

**Project Duration:**
- December 2023 - April 2024

**Role and Responsibilities:**
- Integrated TMinterface to interact with Trackmania.
- Established and managed the socket connection for real-time communication.
- Developed the reward system for agent evaluation.
- Implemented image preprocessing and agent vision.
- Conducted extensive testing and optimization.

**Challenges Faced:**
Integrating real-time communication and developing an effective reward system was challenging. Resolved these by ensuring an optimized socket connection as well as fine-tuning the reward metrics.

**Achievements and Outcomes:**
- Improved agent performance significantly with faster track completion times and fewer crashes.
- Successfully demonstrated the effectiveness of using image processing for game agent navigation.

**Links:**
- [Project Repository](https://github.com/TH3Eimis/TMAI/tree/main)

**Screenshots:**
<p align="center">
  <img src="../img/tmai/port.png" alt="Socket Connection" width="300" />
  <br>Figure 1: Socket Connection
</p>
<p align="center">
  <img src="../img/tmai/state.png" alt="Game State Monitoring" width="300" />
  <br>Figure 2: Game State Monitoring
</p>
<p align="center">
  <img src="../img/tmai/fitness.png" alt="Reward System" width="300" />
  <br>Figure 3: Reward System
</p>
<p align="center">
  <img src="../img/tmai/roi.png" alt="Agent Vision" width="300" />
  <br>Figure 4: Agent Vision
</p>
<p align="center">
  <img src="../img/tmai/edge.png" alt="Edge and Curve Prediction" width="300" />
  <br>Figure 5: Edge and Curve Prediction
</p>

<hr>
Source: <a href="https://github.com/TH3Eimis/TMAI/tree/main"><i class="large github icon ">TMAI Repository</i></a>



