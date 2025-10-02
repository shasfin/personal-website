---
title: "Building a Debugger for WebTigerPython"
author: "Theo Stijve"
semester: "FS2024"
type: "Bachelor's Thesis"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
pdf: "theses/pdfs/FS2024_Theo-Stijve_Building-a-debugger-for-WebTigerPython.pdf"
date: 2025-10-01T13:34:10+02:00
---
![screenshot](/theses/screenshots/FS2024_TheoStijve.png)
This thesis presents the design and implementation of a debugger for WebTigerPython, a web-based Python programming environment developed by the Center for Informatics Education at ETH Zürich. Aimed at enhancing the learning experience for programming students, the debugger addresses a significant gap in WebTigerPython, which, despite its potential as an educational tool, lacked debugging capabilities essential for effective learning and code troubleshooting.

Building upon Python's `bdb` and `dis` modules, the debugger provides key functionalities such as step-by-step code execution, breakpoint handling, and comprehensive visualization of the program's memory state, including mutable variables, references and their interrelationships. The design emphasizes simplicity and user-friendliness to accommodate beginners, drawing inspiration from similar educational tools like WebTigerJython, Python Tutor and Thonny.

The implementation involves modifying program execution to allow users to pause and inspect code at critical points, facilitating a deeper understanding of program behavior. Memory state capture is achieved using introspection tools, and the visualization interface leverages web technologies like `Vue.js` and `LeaderLineNew` to present data in an accessible manner.

Evaluation through performance testing indicates that the debugger introduces a significant though acceptable overhead for typical educational use cases. A user study further demonstrates that the debugger effectively aids students in understanding and correcting coding errors for which they already have the conceptual basis, and provides a helpful visual support for teachers otherwise, thereby improving learning outcomes. Participants reported high usability and found the tool intuitive for exploring code execution and memory state.

The contributions of this work extend beyond the functional debugger to include insights into the challenges of integrating debugging tools into educational programming environments. Future work involves enhancing the debugger's capabilities, such as improved support for complex data structures and additional visualization features, to further enrich the learning experience in WebTigerPython.