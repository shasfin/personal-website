---
title: "{{ replace (index (split .Name "_") 2) "-" " " | title}}"
author: "{{ replace (index (split .Name "_") 1) "-" " "}}"
semester: "{{ replace (index (split .Name "_") 0) "-" " "}}"
type: "Bachelor's Thesis"
supervisor: "Clemens Bachmann, Alexandra Maximova"
professor: "Dennis Komm"
pdf: "theses/pdfs/{{ .Name }}.pdf"
date: {{ .Date }}
---
Please describe shortly the thesis