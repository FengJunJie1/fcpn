# FCPN tool
*FCPN* stands for "*Fuzzy Continuous Petri Nets*". The purpose of FCPN is to offer functions for modeling FCPN models and simulating them.
<br>
![Latest version](https://img.shields.io/badge/Latest%20version-1.0.0-blue.svg)
![Programming language](https://img.shields.io/badge/Programming%20language-C++-red.svg)
![Operating system](https://img.shields.io/badge/Operating%20system-Windows_Linux-yellow.svg)
<br>
*Authors*: Fei Liu, Wujie Sun, Yexuan Sun, Yuchen Zhou, Shijing Zhu, and Zhijie Zhang.
## News
2018-08-31 The first version of FCPN is finished and internally used.<br>
2018-12-05 New stable version of FCPN is released.<br>
2018-12-22 Linux beta version of FCPN is released.
## Table of Contents
- [Background and Introduction](#background-and-introduction)
- [Features](#features)
- [Download and Get Started](#download-and-get-started)
- [Manual](#manual)
- [FAQs](#faqs)
- [Contact Us](#contact-us)
## Background and Introduction
Petri nets provide a formal and graphical representation of systems based on their
firm mathematical foundation for the analysis of system properties. This software
provides fuzzy continuous Petri net modeling and simulation functions
for researchers in the field of systems biology.
<br>
This software includes three main functions: continuous Petri nets modeling, fuzzy modeling,
and hybrid simulation. 
## Features
* Features for modeling
  * Concise and efficient interface design.
    * Drawing of the Petri net graph as usual.
    * Flexible user-defined functions.
    * Multiple fuzzy logic choices.
    * Simple and fast fuzzy logic settings.
    * Rich shortcut settings, such as undo, redo, save, print, etc.
* Features for simulation
  * Highly automated simulation process.
    * Diversified export of simulation results.
    * Custom simulation result drawing.
## Download and Get Started.
Operating environment:
<br>
The software is developed with C++ and QT in the windows operational systems. Currently, we only offer the Windows and Linux verions, but we are also devoting to offer the Mac version as soon as possible.
<br>
**************************
Download:
* Windows version (64bit)
  * Please download the zip file [FCPN.zip](https://github.com/liufei2016/fcpn/raw/master/FCPN.zip). Then unzip it and click the `FCPN.exe` to run the software.
  * Or you can choose to download [Install_FCPN.exe](https://github.com/liufei2016/fcpn/raw/master/Install_FCPN.exe) and install it. Run `FCPN.exe` after installation.
* Linux
  * Ubuntu 18.10 (64bit): [FCPN_Linux.tar.xz](https://github.com/liufei2016/fcpn/raw/master/FCPN_Linux.tar.xz).
after download, extract the archive with "tar xzfv snoopy-stable-linux*.tgz"
`chmod +x FCPN.sh`
`./FCPN.sh`
to use the software.
* Mac OS X version
  * To be released.
## Manual
Manual can be found at [Manual.pdf](https://github.com/wjsunscut/fcpn/raw/master/Manual.pdf). The examples in the manual can be downloaded from [Examples.zip](https://github.com/wjsunscut/fcpn/raw/master/Examples/Examples.zip).
## FAQs
Q: How does a node name in FCPN look like?
<br>
**A: At first all names have to be unique in a net. It can contain any of the following elements:
<br>
• letters a-z and A-Z
<br>
• numbers 0-9
<br>
• underscore _
<br>
The name has to start with a letter or underscore and followed by any combination of all symbols above. Otherwise compiler errors might occur.**
<br>
**************************
Q: What does the function MassAction() mean?
<br>
**A: MassAction() is a macro that creates the rate function for a transition out of its preplaces and takes a parameter as argument, which represents a mass action law.
<br>
For example, assume that t0 has two preplaces p0 and p1, and the parameter k is defined. Now you can specify the rate function of t0 to obey mass action kinetics as k\*p0\*p1 or MassAction(k).
<br>
The results are the same. MassAction() takes care of the structure. If you change the preplaces, the rate function is automatically adapted.**

## Contact us
FCPN is under active development. If you have any questions, please feel free to contact us.
<br>
**Email**: `liuf_2001@163.com`
<br>
**Address**: `University Town Campus of South China University of Technology, Guangzhou, Guangdong, China`
