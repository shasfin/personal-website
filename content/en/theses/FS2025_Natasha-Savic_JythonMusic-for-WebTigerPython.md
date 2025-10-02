---
title: "JythonMusic for WebTigerPython"
author: "Natasha Savic"
semester: "FS2025"
type: "Bachelor's Thesis"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
pdf: "theses/pdfs/FS2025_Natasha-Savic_JythonMusic-for-WebTigerPython.pdf"
date: 2025-10-01T13:54:36+02:00
---
![screenshot](/theses/screenshots/FS2025_NatashaSavic.png)
WebTigerPython is an online Python IDE supporting many functionalities including Turtle Graphics, GPanel, and Robotics. This thesis augmented its feature set through the addition of a music library, allowing users to generate and edit music programmatically as well as export their creations as MIDI files. The library was based on JythonMusic’s music library, which is already in active circulation and contains a structured approach to music making. Additionally, the created library added support for live recording via external MIDI controllers.

In order to reach this goal, JythonMusic’s functionalities were implemented using Web Audio API and Tone.js for sound playback and Mido library to parse data into the MIDI file format for file export. Web MIDI API assisted with the MIDI device input and live performance recording features.

As a result, WebTigerPython now contains its very own music library mimicking JythonMusic. Users can create, modify and playback musical material, upload and listen to .wav and .aif audio files and change their sound trajectory, download generated material as MIDI files, upload and edit MIDI files, make use of metronomes, and record live performances on MIDI instruments, all of which can simply be done from within WebTigerPython’s code editor.
These additional features broaden the spectrum of WebTigerPython’s use cases by adding new possibilities for creative and musical outlet while programming in and outside the classroom.