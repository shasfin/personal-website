---
title: "Implementing GPanel: A Coordinate Graphics Library for WebTigerPython"
author: "Mark Csurgay"
semester: "FS2024"
type: "Bachelor's Thesis"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
pdf: "theses/pdfs/FS2024_Mark-Csurgay_Implementing-GPanel-A-coordinate-graphics-library-for-WebTigerPython.pdf"
date: 2025-10-01T12:54:26+02:00
---
WebTigerPython is an innovative online Python programming environment that introduces and teaches programming to students of various ages. This thesis dives into multiple approaches to enable JavaScript execution in Python code, facilitating the use of PixiJS, a widely adopted JavaScript library, for rendering graphics and shapes to the browser. The overarching objective is to identify the most suitable approach to implement GPanel, a coordinate graphics library, in WebTigerPython.

The merits, limitations, and performance metrics are weighted for each approach to ascertain the most promising strategy for the final implementation.

The final approach allows for executing JavaScript functions efficiently and cleanly, making this new method more performant than the approach used in the already existing GTurtle enactment. It executes any code written in a separate thread, allowing for the website interface to continue functioning while the code runs in the background.