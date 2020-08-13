---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

---

## Object-level SLAM for Indoor Environments
[Sep 2019 - Current] The Robotics Institute of Beihang University  
* Proposed an object-level semantic SLAM algorithm based on RGB-D data, which uses a quadric surface as an object model to compactly represent the object's position, orientation, and shape.
* Introduced the support relationships between objects and the structure planes to estimate 3D objects parameters.
* Introduced a nonparametric pose graph to solve data associations in the back end, and innovatively applied it to the quadric surface model.
* Evaluated the algorithm on two public datasets and an author-collected mobile robot dataset and obtained obvious improvements on the localization accuracy and mapping effects compared with two state-of-art object SLAM algorithms.

### Publications

[1] Liao, Z., Wang, W., Qi, X. & Zhang, X.(2020). RGB-D Object SLAM using Quadrics for Indoor Environments. Submitted to Sensors.

[2] (an ealier version of [1]) Liao, Z., Wang, W., Qi, X., Zhang, X., Xue, L., Jiao, J., & Wei, R. (2020). Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments. ArXiv. [[pdf]](https://arxiv.org/abs/2004.05303)

### Codes
We have released our core codes on [Github](https://github.com/XunshanMan/Object-oriented-SLAM).

### Video Demo
<iframe width="420" height="236.25" src="https://www.youtube.com/embed/u9zRBp4TPIs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Coarse-to-fine Visual Localization using Semantic Compact Map
[Oct  2018 – Jul 2019] Research Intern of the SLAM Group in Megvii (Face++) Technology Co., Ltd.
* Proposed a coarse-to-fine localization system with pole-like objects extracted from semantically segmented images.
* Proposed a localization method decoupling translation from rotation using a monocular camera as a protractor to estimate the vehicle poses accurately. 
* Achieved comparable accuracy with SIFT feature-based methods with a significant small map size about 2.7 kb/km. 

### Publications
**Liao, Z.**, Shi, J., Qi, X., Zhang, X., Wang, W., He, Y., Wei, R., & Liu, X. (2019). Coarse-To-Fine Visual Localization Using Semantic Compact Map. ArXiv. Submitted to ACCV 2020. [[pdf]](https://arxiv.org/abs/1910.04936)

### Videos
<iframe width="420" height="236.25" src="https://www.youtube.com/embed/XbTc1YNPajc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Navigation with Floor Map for Domestic Robots
[Sep 2017 - Feb 2018] Intelligent Robot Laboratory of Tsukuba University 
* Designed a navigation and mapping system for domestic logistic robots to travel from the entry of a floor to the destination room described by room number, such as A311, which enters an unknown building at the first time. 
* Proposed aligning the floor map for human, which commonly exists at the entry of building floors, with a grid map maintained by laser sensor and wheeled odometry of robots, then planning a path using the semantic information on the floor map, e.g. room numbers and positions, feasible corridors.
* Used a monocular camera with OCR recognition algorithm to check the destination room accurately. 


### Videos

<iframe width="420" height="236.25" src="https://www.youtube.com/embed/ktOwdE69A_I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>