---
weight: 0
images:
- '{{ printf "/images/%s.jpg" .File.ContentBaseName }}'
title: Femme Brulee
date: {{ .Date | time.Format ":date_long"}}
hideExif: true
tags:
- femme
- archive
---
