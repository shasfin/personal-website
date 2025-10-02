---
title: "Implementing the Oxocard for WebTigerPython"
author: "Josh Anderegg"
semester: "FS2024"
type: "Bachelor's Thesis"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
pdf: "theses/pdfs/FS2024_Josh-Anderegg_Implementing-the-Oxocard-for-WebTigerPython.pdf"
date: 2025-10-01T13:12:27+02:00
---
![screenshot](/theses/screenshots/FS2024_JoshAnderegg.png)
WebTigerPython is a web based Python IDE that teaches programming to students of all ages. This thesis explores the integration of Oxocards, a series of educational devices, into WebTigerPython, enabling them to be programmed directly from the platform. Since Oxocards do not natively support Python, an alternative method for code execution on these devices was developed.

The proposed solution leverages the MQTT messaging protocol to enable communication between the IDE and the Oxocards, allowing instructions to be sent and executed on device. This approach was rigorously tested, demonstrating both its strengths and limitations.

The final implementation effectively abstracts away the underlying complexity, making it seem to the user as if the Python code is running directly on the Oxocards.