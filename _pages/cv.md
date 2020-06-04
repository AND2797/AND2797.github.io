---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S  in Computational Design & Manufacturing, Carnegie Mellon University, 2020
  * 10-601 : [Machine Learning](http://www.cs.cmu.edu/~mgormley/courses/10601/) 
  * 15-513 : [Computer Systems](https://www.cs.cmu.edu/afs/cs/academic/class/15213-f19/www/syllabus/syllabus.pdf)
  * 16-720 : [Computer Vision](http://ci2cv.net/16720b/)
  * 16-831 : [Statistical Techniques in Robotics](https://AND2797.github.io/files/1.1_Logistics.pdf)
* B.S. in Mechanical Engineering, Vellore Institute of Technology, 2019

Work experience
======
* **Research Assistant** _June 2020_*
   * [_Integrated Design Innovation Group, CMU_](https://www.cmu.edu/me/idig/)
      * Working on fine-grained image classification and learning mid-level latent representations for identifying shape grammar in             products.
      * Exploring multi-attention models, discriminative filter banks, recurrant neural networks and weakly supervised learning models.
      * **Supported by Summer Graduate Research Fellowship Grant.**
* **Research Assistant** _September 2019_*
   * [_Computational Engineering & Robotics Laboratory, CMU_](http://www.andrew.cmu.edu/user/shimada/)
      * Leading the development of a robotic perception module using stereo-cameras for automatic localization of architectural               installations (windows, frames) in a construction site.
      * Utilizing structure from motion, multi-view geometry and active light stereopsis. 
* **Intern** _May 2018_
  * [_Defence Research & Development Organization_](https://www.drdo.gov.in/labs-and-establishments/laser-science-technology-centre-lastec)
    * Worked on the design of a dual-axis self stabilized gimbal for a vehicle mounted laser for remote ordinance disposal.
    * Designed in SolidWorks and FEM validation for vibration and stresses using ANSYS
* **Intern** _June 2017_
  * [_Aeronautical Development Agency_](https://www.ada.gov.in/)
    * Developed an algorithm based on multivariable regression to predict structural failure in fighter aircraft based on
      data from previous sorties using MATLAB.
    * Modelled the output (strain) in terms of variables like G-Force, Yaw, Roll and Pitch angles and rates.
    * Achieved close to 96% accuracy on th e test data set.
  
Skills
======
* Python (NumPy, OpenCV, PyTorch, SciPy)
* C (Linux / Unix) 
* C++
* Git version control

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
