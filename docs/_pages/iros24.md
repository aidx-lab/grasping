---
permalink: /iros24
layout: page
title: IROS 2024
usemathjax: true
---
## A Learning-based Controller for Multi-Contact Grasps on Unknown Objects with a Dexterous Hand

[Dominik Winkelbauer](https://scholar.google.com/citations?user=kduGd8wAAAAJ){:target="_blank"} &ensp; 
[Rudolph Triebel](https://scholar.google.com/citations?user=SuOUxjUAAAAJ){:target="_blank"} &ensp; 
[Berthold Bäuml](https://scholar.google.com/citations?user=fjvpDsEAAAAJ){:target="_blank"}

<p align="center">
<video src="/grasping/assets/imgs/iros24/video.mp4" \controls="controls" muted="muted" class="d-block rounded-bottom-2 width-fit" width="746" height="420">

  </video>
</p>

[Full Paper](https://arxiv.org/abs/2409.12339){:target="_blank"}

## Abstract

Existing grasp controllers usually either only support finger-tip grasps or need explicit configuration of the inner forces.
We propose a novel grasp controller that supports arbitrary grasp types, including power grasps with multi-contacts, while operating self-contained on before unseen objects. 
No detailed contact information is needed, but only a rough 3D model, e.g., reconstructed from a single depth image.
First, the external wrench being applied to the object is estimated by using the measured torques at the joints.
Then, the torques necessary to counteract the estimated wrench while keeping the object at its initial pose are predicted. 
The torques are commanded via desired joint angles to an underlying joint-level impedance controller.
To reach real-time performance, we propose a learning-based approach that is based on a wrench estimator- and a torque predictor neural network.
Both networks are trained in a supervised fashion using data generated via the analytical formulation of the controller.
In an extensive simulation-based evaluation, we show that our controller is able to keep 83.1%
 of the tested grasps stable when applying external wrenches with up to 10N.
At the same time, we outperform the two tested baselines by being more efficient and inducing less involuntary object movement.
Finally, we show that the controller also works on the real DLR-Hand II reaching a cycle time of 6ms.

Cite this paper as:

    @inproceedings{Winkelbauer2024,
        author = {Dominik Winkelbauer and Rudolph Triebel and Berthold B{\"a}uml},
        booktitle = {IEEE International Conference on Intelligent Robots and Systems},
        title = {A Learning-based Controller for Multi-Contact Grasps on Unknown Objects with a Dexterous Hand},
        year = {2024}}
        
