---
title: "Visualising Databases in WebTigerPython"
author: "Selin Barash"
semester: "FS2025"
type: "Practical Work"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
date: 2025-10-01T13:56:24+02:00
---
![screenshot](/theses/screenshots/FS2025_SelinBarash.png)
This thesis extends the WebTigerPython environment, a browser-based Python IDE for beginners, by integrating persistent database support and interactive table visualization. The project adapts the existing Python implementation of the `database1` library (from Einfach Informatik: Programmieren 7–9) for use in the web environment by providing a JavaScript backend built on SQLite. Persistence across sessions and browser tabs is achieved through IndexedDB storage. In addition, the IDE was enhanced with multi-level visualization of relational tables. At the highest level, users see all defined tables as schematic rectangles, with optional datatype annotations and links between them. Individual tables can be expanded to display scrollable data previews alongside other tables or opened in full-screen mode for detailed inspection. Separate databases are managed in distinct visualization tabs, allowing flexible exploration of complex data structures. Together, these contributions enable a richer, more transparent interaction with databases in WebTigerPython, making it more suitable for both teaching and exploratory learning.