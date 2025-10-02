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
WebTigerPython ist eine webbasierte Python-IDE für Lernende aller Altersstufen. Diese Arbeit untersucht die Integration von Oxocards, programmierbaren Platinen, in WebTigerPython. Da Oxocards Python nicht nativ unterstützen, wurde ein alternativer Ausführungsweg entwickelt.

Die Lösung nutzt das MQTT-Protokoll, um Anweisungen zwischen IDE und Oxocards zu übertragen. Tests zeigten sowohl Vorteile als auch Grenzen. Die Implementierung abstrahiert die Komplexität, sodass die Nutzer*innen die Programme wie native Python-Ausführung erleben.