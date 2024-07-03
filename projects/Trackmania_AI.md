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
summary: "A genetic algorithm designed to optimise agents' decisions to real-time data retrieved from Trackmania nations forever"
---

<hr>
<p>An agent "vision" consists of a screenshot of the Trackmania Tab to which some preprocessing is applied and the image is cropped around an ROI (region of interest) </p>
<img class="img-fluid" src="../img/tmai_edge.png">
<p>Agents use edge/curve prediction to navigate their surroundings, allowing them to recognise borders and navigate around.</p>
<p>The program retrieves the in-game data using TMInterface (https://donadigo.com/tminterface/) a tool used to create and run TMNF plugins, this allowed me to create a plugin that was directly able to read the game data and then communicate with a socket connection running on the main python code</p>
<hr>

Source: <a href="https://github.com/TH3Eimis/TMAI/tree/main"><i class="large github icon "></i>TMAI Repository</a>
 
