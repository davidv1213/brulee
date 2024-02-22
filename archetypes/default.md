---
weight: 0
images:
- '{{ printf "/images/%s.jpg" .File.ContentBaseName }}'
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date | time.Format ":date_long"}}
hideExif: true
tags:
- archive
---
