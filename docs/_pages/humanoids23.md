---
layout: page
title: Humanoids 23
usemathjax: true
---
# Combining Shape Completion and Grasp Prediction for Fast and Versatile Grasping with a Multi-Fingered Hand

This site complements our paper [**Combining Shape Completion and Grasp Prediction for Fast and Versatile Grasping with a Multi-Fingered Hand**](){:target="_blank"} by
[Matthias Humt](https://scholar.google.com/citations?hl=en&user=kduGd8wAAAAJ){:target="_blank"}, [Dominik Winkelbauer](https://scholar.google.com/citations?hl=en&user=kduGd8wAAAAJ){:target="_blank"}, [Ulrich Hillenbrand](https://rmc.dlr.de/rm/de/staff/ulrich.hillenbrand/){:target="_blank"} and [Berthold Bäuml](https://scholar.google.com/citations?hl=en&user=SuOUxjUAAAAJ){:target="_blank"}.


<p align="center">
<img src="/grasping/assets/imgs/humanoids23/front.png" alt="drawing" width="400"/>
</p>


# Abstract

Grasping objects with limited or no prior knowl-
edge about them is a highly relevant skill in assistive robotics.
Still, in this general setting, it has remained an open problem,
especially when it comes to only partial observability and
versatile grasping with multi-fingered hands. We present a
novel, fast, and high fidelity deep learning pipeline consisting
of a shape completion module that is based on a single depth
image, and followed by a grasp predictor that is based on
the predicted object shape. The shape completion network is
based on VQDIF and predicts spatial occupancy values at
arbitrary query points. As grasp predictor, we use our two-
stage architecture that first generates hand poses using an au-
toregressive model and then regresses finger joint configurations
per pose. Critical factors turn out to be sufficient data realism
and augmentation, as well as special attention to difficult cases
during training. Experiments on a physical robot platform
demonstrate successful grasping of a wide range of household
objects based on a depth image from a single viewpoint. The
whole pipeline is fast, taking only about 1 s for completing the
object’s shape (0.7 s) and generating 1000 grasps (0.3 s).

Cite this paper as:

    @inproceedings{Humt2023,
        author = {Matthias Humt and Dominik Winkelbauer and Ulrich Hillenbrand and Berthold B{\"a}uml},
        booktitle = {IEEE-RAS International Conference on Humanoid Robots},
        title = {Combining Shape Completion and Grasp Prediction for Fast and Versatile Grasping with a Multi-Fingered Hand},
        year = {2023}}
        
