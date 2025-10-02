---
title: "Centralized Documentation for TigerJython and WebTigerPython"
author: "Andri Hunkeler"
semester: "FS2024"
type: "Bachelor's Thesis"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
pdf: "theses/pdfs/FS2024_Andri-Hunkeler_Centralized-documentation-for-TigerJython-and-WebTigerPython.pdf"
date: 2025-10-01T13:04:57+02:00
---
![screenshot](/theses/screenshots/FS2024_AndriHunkeler.jpg)
This thesis is about the development of a centralized documentation for TigerJython and WebtigerPython, a solution to streamline the documentation which currently exists in multiple different versions. The main goal was to build a tool which allows for the easy distribution of the information, as well as making maintenance and additions to it simpler.

To make this happen Andri Hunkeler used a MySQL database which is made accessible through FastAPI, a Python based API framework. The user interface is written in TypeScript, utilizing Vue as the base JavaScript framework and extending its capabilities by adding Vuetify and Vueform. 
    
Some of the key features of the documentation include multi-language support, flexible sorting of all parts of the information, tags for fine grained categorization and aids to keep the different languages consistent. 

In the end, the solution provides a consistent documentation for all users and a streamlined process for maintaining it. It can be integrated in the currently existing versions of the documentation, as well as future endeavors such as the integrated documentation in WebTigerPython.