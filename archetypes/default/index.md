---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
#longform: false # Deduced if content is more than 140 characters, this parameter can be used to override.
#summary: Lorem ipsum...
#tags:
# - example
#resources:
#- name: cover
#  src: relative/from/here.jpg
---