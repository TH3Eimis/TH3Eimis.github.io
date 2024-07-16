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

<h>Role: Developer</h>
<hr>
- Utilized TMinterface to directly interact with Trackmania, allowing the plugin to read game data and send control inputs. TMinterface details: [https://donadigo.com/tminterface/](https://donadigo.com/tminterface/)
<hr>
- Established a socket connection on localhost port 8000 to facilitate real-time communication between the game plugin and Python code.
<img class="img-fluid" src="../img/tmai/port.png" style="max-width: 600px; width: 100%; height: auto;">
<hr>
- Designed the system to read game state changes, trigger the execution of agents and collect performance data.
<img class="img-fluid" src="../img/tmai/state.png" style="max-width: 600px; width: 100%; height: auto;">
<hr>
- Implemented a reward system that evaluates agents based on track completion time, medals earned average speed, and crash count, driving the evolutionary process.
<img class="img-fluid" src="../img/tmai/fitness.png" style="max-width: 600px; width: 100%; height: auto;">
<hr>
- Developed agent "vision" by capturing screenshots of the Trackmania tab, applying preprocessing, and cropping around a region of interest (ROI).
<img class="img-fluid" src="../img/tmai/roi.png" style="max-width: 600px; width: 100%; height: auto;">
<hr>
- Enabled agents to use edge and curve prediction for navigation, allowing them to recognize borders and navigate effectively.
<img class="img-fluid" src="../img/tmai/edge.png" style="max-width: 600px; width: 100%; height: auto;">
<hr>
- Conducted extensive testing to fine-tune the algorithm and improve the overall performance and reliability of the agents.

<hr>
Source: <a href="https://github.com/TH3Eimis/TMAI/tree/main"><i class="large github icon ">TMAI Repository</i></a>
 
