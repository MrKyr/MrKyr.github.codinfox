---
layout: post
author: kyr
title: Backup Dot Files
description: Backup & gzip all the hiden files from your [linux](http://kernel.org "kernel.org") home directory.
category: [Coding]
tags: [linux]
---

### Code:

```sh
$ tar cpvzf ~/BACKUPS/dotfiles.tgz ./.[aA-zZ]* \
  --exclude=.somefile --exclude=.somedirectory
```
    
*BACKUPS=* your backup folder

*dotfiles=* choose your own filename

*--exclude=* whatever you `don't` want to backup


***\* Use This Code at Your Own Risk!***
