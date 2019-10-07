---
title: "{{ .TranslationBaseName | replaceRE "[0-9][0-9][0-9][0-9]-[0-9][0-9]-[0-9][0-9]-" "" | humanize }}"
date: {{ delimit (findRE "[0-9][0-9][0-9][0-9]-[0-9][0-9]-[0-9][0-9]" .TranslationBaseName 1) "" }}T10:30:00{{ dateFormat "-07:00" .Date }}
draft: false
categories:
- Accessibility
- Art and Science
- Business and Leadership
- Careers
- Code
- CSS
- Design and UX
- HTML
- JavaScript
- Technology
- Web Performance
- WordPress
- Vanilla Framework Demos
---

