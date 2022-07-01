---
title: "Power Capping Nvidia GPUs"
date: 2022-07-01
tags: [gpu, nvidia]
draft: False
---
## May be some day you might need to decrease or increase the power cap on your GPUs
To query the current power limit
```bash
nvidia-smi -q | grep 'Power Limit'
```
Note: Make sure your GPU is working on a persistence mode
To change the power cap
```bash
nvidia-smi -p1 200
```
replace 200 with the value you want to change to.