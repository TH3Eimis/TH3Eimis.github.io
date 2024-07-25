---
layout: project
type: project
image: img/tmnf_img.png
title: "Trackmania AI"
date: 2024
published: true
labels:
  - Python
  - Angelscript
  - TMInterface
  - Socket Programming
summary: "Developed a genetic algorithm to control agents attempting to complete a Trackmania map. The project focused on optimizing performance based on various metrics such as time taken, medal achieved, average speed, and crash count."
---

# Trackmania AI

**Project Description:**
A sophisticated AI system developed to interact with Trackmania, designed to read game data, send control inputs, and optimize agent performance through real-time communication and advanced image processing.

**Key Features:**
- **TMinterface Integration:** Utilized TMinterface to directly interact with Trackmania, allowing the plugin to read game data and send control inputs. TMinterface details: [https://donadigo.com/tminterface/](https://donadigo.com/tminterface/)
- **Socket Connection:** Established a socket connection on localhost port 8000 to facilitate real-time communication between the game plugin and Python code.
  <img class="img-fluid" src="../img/tmai/port.png" style="max-width: 200px; width: 100%; height: auto;">
- **Game State Monitoring:** Designed the system to read game state changes, trigger the execution of agents, and collect performance data.
  <img class="img-fluid" src="../img/tmai/state.png" style="max-width: 200px; width: 100%; height: auto;">
- **Reward System:** Implemented a reward system that evaluates agents based on track completion time, medals earned, average speed, and crash count, driving the evolutionary process.
  <img class="img-fluid" src="../img/tmai/fitness.png" style="max-width: 200px; width: 100%; height: auto;">
- **Agent Vision:** Developed agent "vision" by capturing screenshots of the Trackmania tab, applying preprocessing, and cropping around a region of interest (ROI).
  <img class="img-fluid" src="../img/tmai/roi.png" style="max-width: 200px; width: 100%; height: auto;">
- **Edge and Curve Prediction:** Enabled agents to use edge and curve prediction for navigation, allowing them to recognize borders and navigate effectively.
  <img class="img-fluid" src="../img/tmai/edge.png" style="max-width: 200px; width: 100%; height: auto;">
- **Extensive Testing:** Conducted extensive testing to fine-tune the algorithm and improve the overall performance and reliability of the agents.

**Technologies Used:**
- Python
- OpenCV
- Socket Programming

**Project Duration:**
- Start Date to End Date (e.g., January 2023 - March 2023)

**Role and Responsibilities:**
- Integrated TMinterface to interact with Trackmania.
- Established and managed the socket connection for real-time communication.
- Developed the reward system for agent evaluation.
- Implemented image preprocessing and agent vision.
- Conducted extensive testing and optimization.

**Challenges Faced:**
Integrating real-time communication and developing an effective reward system were challenging. Resolved these by optimizing the socket connection and fine-tuning the reward metrics.

**Achievements and Outcomes:**
- Improved agent performance significantly with faster track completion times and fewer crashes.
- Successfully demonstrated the effectiveness of using image processing for game agent navigation.

**Links:**
- [Project Repository](#)
- [Live Demo](#) (if applicable)
- [Project Documentation](#) (if applicable)

**Screenshots:**
![Socket Connection](../img/tmai/port.png)
![Game State Monitoring](../img/tmai/state.png)
![Reward System](../img/tmai/fitness.png)
![Agent Vision](../img/tmai/roi.png)
![Edge and Curve Prediction](../img/tmai/edge.png)

**Testimonials:**
_"The AI system's ability to navigate complex tracks and improve over time is impressive."_ - User Feedback
<hr>
Source: <a href="https://github.com/TH3Eimis/TMAI/tree/main"><i class="large github icon ">TMAI Repository</i></a>



