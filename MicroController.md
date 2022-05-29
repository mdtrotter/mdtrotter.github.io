# [MicroCorruption](https://microcorruption.com/)

## Overview

Microcorruption is an always online embedded systems, reverse engineering CTF. Each exercise presents an in-browser debugger. Your job is to find the password input to unlock the building that the embedded system controls.

![](MicroController_Pics/MC01.png)

The embedded system architecture, assembly language, and many other details can be found in this manual:  
[Embedded System Manual](ti.com/lit/ug/slau049f/slau049f.pdf)

## Tutorial

We won't be doing a deep dive into the Tutorial exercise, but I'll give a highlight of how to navigate the debugger, test your input and solve an exercise. I do recommend doing the tutorial even if you're familiar with RE CTFs.

First is the disassembly window. This window colors the current instruction pointed to by the PC (Program Counter register) red. You can also set breakpoints by clicking on an instruction and ensuring a blue background is produced behind the instruction.

![](MicroController_Pics/MC02.png)

## New Orleans
