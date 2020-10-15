---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

---
# Publications

### Journal
**Liao, Z.**, Wang, W., Qi, X. & Zhang, X.(2020). RGB-D Object SLAM using Quadrics for Indoor Environments. Sensors, 20. [[pdf]](https://www.mdpi.com/1424-8220/20/18/5150/pdf)

Zhang, X., Wang, W., Qi, X., **Liao, Z.**, & Wei, R. (2019). Point-Plane SLAM Using Supposed Planes for Indoor Environments. Sensors, 19. [[pdf]](https://www.mdpi.com/1424-8220/19/17/3795/pdf)

<!-- Qi, X.; Wang, W.; **Liao, Z.**; Zhang, X.; Yang, D.; Wei, R. Object Semantic Grid Mapping with 2D LiDAR and RGB-D Camera for Domestic Robot Navigation. Appl. Sci. 2020, 10, 5782. [[pdf]](https://www.mdpi.com/2076-3417/10/17/5782) -->

### Preprint
Zhang, X., **Liao, Z.**, Qi, X., & Wang, W. (2020). Stereo Plane SLAM Based on Intersecting Lines. ArXiv, abs/2008.08218. Submitted to RA-L/ICRA 2021. [[pdf]](https://arxiv.org/pdf/2008.08218.pdf)

**Liao, Z.**, Shi, J., Qi, X., Zhang, X., Wang, W., He, Y., Wei, R., & Liu, X. (2019). Coarse-To-Fine Visual Localization Using Semantic Compact Map. ArXiv, abs/1910.04936. (Preprint) [[pdf]](https://arxiv.org/pdf/1910.04936.pdf)

<!-- **Liao, Z.**, Wang, W., Qi, X., Zhang, X., Xue, L., Jiao, J., & Wei, R. (2020). Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments. ArXiv, abs/2004.05303. (Preprint) -->

### Patent
**Liao, Z.**, Positioning method, device, electronic equipment, readable storage medium, CN111383286A, 2020 (Chinese Patent)

# Projects
## 1. RGB-D Object SLAM using Quadrics for Indoor Environments
**[Sep 2019 - Current] The Robotics Institute of Beihang University, supervised by Prof. Wei Wang**

<center><img src="/images/research/object-slam-3.png" width="70%" /></center>
<!-- ![](./pics/object-slam-2.png) -->

* Proposed an object-level semantic SLAM algorithm based on RGB-D data, which uses a quadric surface as an object model to compactly represent the object's position, orientation, and shape.
* Introduced the support relationships between objects and the structures to help optimize 3D objects parameters.
* Introduced a nonparametric pose graph to solve data associations in the back end, and innovatively applied it to the quadric surface model.

### Publication

**Liao, Z.**, Wang, W., Qi, X. & Zhang, X.(2020). RGB-D Object SLAM using Quadrics for Indoor Environments. Sensors, 20. [[pdf]](https://www.mdpi.com/1424-8220/20/18/5150/pdf)

### Video Demo 
This is a video demo of an early version. We recommend seeing the publication for the detail.
<iframe width="315" height="177.2" src="https://www.youtube.com/embed/u9zRBp4TPIs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- video size : 420 236.25 -->
<!-- 3/4 video size : 315 177.2 -->


## 2. Coarse-to-fine Visual Localization using Semantic Compact Map
**[Oct  2018 – Jul 2019] Research Intern of the SLAM Group in Megvii (Face++) Technology Co., Ltd.**

<!-- <center><img src="./pics/coarse-to-fine.png" width="50%" height="50%" /></center> -->
<!-- ![](./pics/coarse-to-fine.png) -->
<center><img src="/images/research/coarse-to-fine.png" width="50%" /></center>

* Reproduced and evaluated the algorithm proposed in the paper Long-term Visual Localization using Semantically Segmented Images [ICRA2018], which is a semantic localization algorithm based on a particle filter for vehicles. 
* Proposed a coarse-to-fine localization system with pole-like objects extracted from semantically segmented images
* Introduced a localization method decoupling translation from rotation using a monocular camera as a protractor to estimate the poses precisely.
* Achieved comparable accuracy with SIFT feature-based methods with a significant small map size of 2.7 kb/km.


### Preprint & Patent
**Liao, Z.**, Shi, J., Qi, X., Zhang, X., Wang, W., He, Y., Wei, R., & Liu, X. (2019). Coarse-To-Fine Visual Localization Using Semantic Compact Map. ArXiv, abs/1910.04936. (Preprint) [[pdf]](https://arxiv.org/pdf/1910.04936.pdf)

[2] **Liao, Z.**, Positioning method, device, electronic equipment, readable storage medium, CN111383286A, 2020 (Chinese Patent)

### Video Demo
<iframe width="315" height="177.2" src="https://www.youtube.com/embed/XbTc1YNPajc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## 3. Navigation with Floor Map for Domestic Robots
**[Sep 2017 - Feb 2018] Intelligent Robot Laboratory of Tsukuba University, supervised by Prof. Akihisa Ohya**

<!-- <center><img src="./pics/floor-map.png" width="70%" height="70%" /></center> -->
<!-- ![](./pics/floor-map.png) -->
<center><img src="/images/research/floor-map.png" width="70%" /></center>

* Designed a navigation and mapping system for domestic logistic robots to travel from the entry of a floor to the destination room described by room number, such as A311, when entering a building for the first time. 
* Proposed using the floor map for humans as prior for the robots, which commonly exists at the entry of building floors.
* Built a grid map by a laser sensor and a wheeled odometry of the robots, aligned it with the floor map, and then navigated the robots with the semantic information on the floor map, e.g., room numbers and positions.
* Used a monocular camera with an OCR recognition algorithm to check the destination room accurately. 



### Video Demo

<iframe width="315" height="177.2" src="https://www.youtube.com/embed/ktOwdE69A_I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## 4. Point-Plane SLAM Using Supposed Planes for Indoor Environments
**[Sep 2018 - Aug 2020] The Robotics Institute of Beihang University, supervised by Prof. Wei Wang**

This is a co-author project with my colleagues.

<!-- <img src="./pics/point-plane-slam.png" width = 50% height = 35% align=right /> -->
<!-- <center><img src="./pics/point-plane-slam.png" width="70%" height="70%" /></center> -->
<!-- ![](./pics/point-plane-slam.png) -->
<center><img src="/images/research/point-plane-slam.png" width="70%" /></center>

### Publication
Zhang, X.; Wang, W.; Qi, X.; **Liao, Z.**; Wei, R. Point-Plane SLAM Using Supposed Planes for Indoor Environments. Sensors 2019, 19, 3795. [[pdf]](https://www.mdpi.com/1424-8220/19/17/3795)

Zhang, X., **Liao, Z.**, Qi, X., & Wang, W. (2020). Stereo Plane SLAM Based on Intersecting Lines. ArXiv, abs/2008.08218. Submitted to RA-L/ICRA 2021. [[pdf]](https://arxiv.org/pdf/2008.08218.pdf)

<!-- ---

### Last Update

Sep 23, 2020 -->