---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
tags:
url: "{{ dateFormat "2006/01/02" .Date}}/{{ .Name }}"
---
