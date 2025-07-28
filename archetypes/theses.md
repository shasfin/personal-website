---
title: "{{ replace (index (split .Name "_") 2) "-" " " | title}}"
author: "{{ replace (index (split .Name "_") 1) "-" " "}}"
semester: "{{ replace (index (split .Name "_") 0) "-" " "}}"
supervisor: "Clemens Bachmann, Alexandra Maximova"
pdf: "static/theses/{{ .Name }}.pdf"
date: {{ .Date }}
---
Please describe shortly the thesis