---
title: "2D Simulator for WebTigerPython"
author: "Kai Zürcher"
semester: "FS2025"
type: "Bachelor's Thesis"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
pdf: "theses/pdfs/FS2025_Kai-Zürcher_2D-Simulator-for-WebTigerPython.pdf"
date: 2025-10-01T13:47:17+02:00
---
![screenshot](/theses/screenshots/FS2025_KaiZürcher.png)
This thesis adds a microcomputer as well as a robotics simulator to WebTigerPython, a web-based integrated development environment (IDE) used for teaching Python programming, often in combination with microcomputers and robotic extensions. The simulator is not meant to replace the physical hardware, rather, it aims to reduce limitations such as hardware unavailability, compatibility issues, and testing delays by providing a virtual testing environment.

This thesis integrated existing simulators for the micro:bit and the Calliope mini 3 into WebTigerPython. Then, a robotics simulator was built upon these microcomputer simulators using Phaser 3. Unfortunately, the pre-existing simulators had no pin simulation, which is essential for the robotics simulation. Thus, a workaround was devised to bridge the missing pin simulation by parsing the code before execution.

The simulator models realistic movement and sensors for the Maqueen Lite, Maqueen Plus V2, and the Calli:bot. To enable meaningful sensor simulation, an interactive environment editor was also added to the robotics simulator.