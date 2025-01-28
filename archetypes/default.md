---
title: "{{ .TranslationBaseName | humanize | title }}"
date: "{{ dateFormat "2006-01-00" .Date }}"
Lastmod: "{{ dateFormat "2006-01-00" .Date }}"
draft: true
thumbnail: images/default.jpg
archives:
  - {{ dateFormat "2006-01" .Date }}
tags:
  - 
---
