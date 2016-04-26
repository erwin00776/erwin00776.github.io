---
layout: post
title:  "Install Geforce Drivers and CUDA on Ubuntu 15.04"
date:   2016-04-26 18:13:17 +0800
categories: Installation CUDA
---

机器配置
i5-6500 + Geforce 9xx
Ubuntu 15.04 + CUDA 7.5

唯一难题
Ubuntu booting into console mode:
No need to change "/etc/default/grub" file or execute "sudo update-grub"

JUST execute "sudo systemctl set-default multi-user.target"
switch back to Graphical:
"sudo systemctl set-default graphical.target"

Reference: http://www.ruanyifeng.com/blog/2016/03/systemd-tutorial-commands.html

... ...
(TBC)
