---
title: "Send triggers to CyKit"
excerpt: "A simple way to send triggers to CyKit----socket + psychopy.<br/><img src='/images/socket-cykit-psy.png'>"
collection: portfolio
---

[CyKit](https://github.com/CymatiCorp/CyKit) is a very useful tools to get EEG data from Emotive devices. If we need to use PsychoPy to conduct experiments and obtain the corresponding triggers, we can use a socket to send and receive simple information. I write a simple code for it in the experiment on emotion. Experiment codes send "2" to CyKit when the film begins, and send "3" to CyKit when the film ends. The trigger will be written to the last column of the csv data file.
[Code](https://github.com/Sxinyue/CyKit)

![这是图片](/images/socket-cykit-psy.png)