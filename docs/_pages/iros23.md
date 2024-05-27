---
permalink: /iros23
layout: page
title: IROS23
usemathjax: true
---
## Learning-based Real-time Torque Prediction for Grasping Unknown Objects with a Multi-Fingered Hand

[Dominik Winkelbauer](https://scholar.google.com/citations?user=kduGd8wAAAAJ){:target="_blank"} &ensp; 
[Berthold Bäuml](https://scholar.google.com/citations?user=fjvpDsEAAAAJ){:target="_blank"} &ensp; 
[Rudolph Triebel](https://scholar.google.com/citations?user=SuOUxjUAAAAJ){:target="_blank"}


<p align="center">
<img src="/grasping/assets/imgs/iros23/front.png" alt="drawing" width="400"/>
</p>

[Full Paper](https://elib.dlr.de/197492/){:target="_blank"}

## Abstract

When grasping objects with a multi-finger hand, it is
crucial for the grasp stability to apply the correct
torques at each joint so that external forces are
countered. Most current systems use simple heuristics
instead of modeling the required torque correctly. Instead,
we propose a learning-based approach that is able to
predict torques for grasps on unknown objects in real-time.
The neural network, trained end-to-end using supervised
learning, is shown to predict torques that are more
efficient, and the objects are held with less involuntary
movement compared to all tested heuristic baselines.
Specifically, for 90 % of the grasps the translational
deviation of the object is below 2.9 mm and the rotational
below 3.1°. To generate training data, we formulate the
analytical computation of torques as an optimization
problem and handle the indeterminacy of multi-contacts
using an elastic model. We further show that the network
generalizes to predict torques for unknown objects on the
real robot system with an inference time of 1.5 ms. 

Cite this paper as:

    @inproceedings{Winkelbauer2023,
        author = {Dominik Winkelbauer and Berthold B{\"a}uml and Rudolph Triebel},
        booktitle = {IEEE International Conference on Intelligent Robots and Systems},
        title = {Learning-Based Real-Time Torque Prediction for Grasping Unknown Objects with a Multi-Fingered Hand},
        year = {2023}}
        
