---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
categories: ["{{ now.Format "2006-01"}}"]
tags: ["{{ now.Format "2006-01"}}"]
images: ["/images/profile.jpeg"]
---

