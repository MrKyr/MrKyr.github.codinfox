---
layout: post
title: Backup Dot Files
category: [Coding]
tags: [linux]
---

Backup & gzip all the hiden files from your [linux](http://kernel.org "kernel.org") home directory.

### Code:

```
$ tar cpvzf ~/BACKUPS/dotfiles.tgz ./.[aA-zZ]* \
  --exclude=.somefile --exclude=.somedirectory
```
    
*BACKUPS=* your backup folder

*dotfiles=* choose your own filename

*--exclude=* whatever you `don't` want to backup


***\* Use This Code at Your Own Risk!***
