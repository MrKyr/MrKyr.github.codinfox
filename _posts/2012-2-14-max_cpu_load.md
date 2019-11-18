---
layout: post
title: Max Cpu Load
category: [Coding]
tags: [linux]
---

Bash command line to show system's max cpu load. 

### Code:

```
$ echo -n `ps -eo pcpu,pid -o comm= \
  | sort -k1 -n -r | head -1 | awk '{ print $1 } '`"%"
```

***\* Use This Code at Your Own Risk!***
