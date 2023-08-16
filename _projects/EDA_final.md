---
layout: page
title: Learning Arithmetic Operations from Gate-Level Circuit
description: C++
img: assets/img/ICCAD/cover.png
importance: 5
category: ICS/HDL
---

    In collaboration with 張家翔、陳宥辰. 
    This is the final project of Introduction to Electronic Design Automation (Spring 2022)
    It received the top score among 25+ teams.


<h4><strong>Introduction</strong></h4>
Reverse engineering, which aims to reconstruct high-level description of a given gate-level netlist, is essential for maintaining design security and detecting malicious third-party hard IP cores. In this work, we implemented an efficient engineering solver and proposed a method for determining if-else conditions using the Quine-Mccluskey procedure. Our design solves netlists consisting of general operations efficiently using equivalence checking. Our design derives the high-level description of the netlist by the following steps: (1) Converting the netlist into a graph. (2) Performing equivalence checking between the netlist and the output function candidates to form a two dimensional boolean table. (3) Applying the Quine-Mccluskey procedure to find the minimum cover of the table. (4) Finding the control signals according to the cover and solving its high-level logic. This design reaches maximum re-duction for 8 test cases provided by CAD contest out of 20 while maintaining extremely low runtime.

<h4><strong>Presentation Slide</strong></h4>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <!-- <embed src="../../assets/img/FPGA/Final Project Demo.pdf" type="application/pdf" width="100%" height="600px" /> -->
        {% include video.html path="../../assets/img/ICCAD/Final Presentation.pdf" width="800" height="600" title="example image" class="rounded z-depth-1"%}
    </div>
</div>