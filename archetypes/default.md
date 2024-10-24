---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: '{{ .Date | time.Format "2006-01-02" }}'
type: posts
draft: true
categories:
- default
tags:
- default
---
