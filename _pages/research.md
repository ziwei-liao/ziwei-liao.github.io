---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

---
# Publications
Please see my [Google Scholar Page](https://scholar.google.com/citations?user=IhfB2iQAAAAJ&hl=en).

<!-- ### Journal & Conference -->
<!-- **Liao, Z.**, Wang, W., Qi, X. & Zhang, X.(2020). RGB-D Object SLAM using Quadrics for Indoor Environments. Sensors, 20. [[pdf]](https://www.mdpi.com/1424-8220/20/18/5150/pdf) -->

<!-- **Liao, Z.**, Shi, J., Qi, X., Zhang, X., Wang, W., He, Y., Wei, R., & Liu, X. (2019). Coarse-To-Fine Visual Localization Using Semantic Compact Map. 2020 3rd International Conference on Control and Robots, ICCR 2020, Tokyo, Japan. (accepted) [[pdf]](https://arxiv.org/pdf/1910.04936.pdf) -->

<!-- Zhang, X., Wang, W., Qi, X., **Liao, Z.**, & Wei, R. (2019). Point-Plane SLAM Using Supposed Planes for Indoor Environments. Sensors, 19. [[pdf]](https://www.mdpi.com/1424-8220/19/17/3795/pdf) -->

<!-- Qi, X.; Wang, W.; **Liao, Z.**; Zhang, X.; Yang, D.; Wei, R. Object Semantic Grid Mapping with 2D LiDAR and RGB-D Camera for Domestic Robot Navigation. Appl. Sci. 2020, 10, 5782. [[pdf]](https://www.mdpi.com/2076-3417/10/17/5782) -->

<!-- ### Preprint -->
<!-- Zhang, X., **Liao, Z.**, Qi, X., & Wang, W. (2020). Stereo Plane SLAM Based on Intersecting Lines. ArXiv, abs/2008.08218. Submitted to RA-L/ICRA 2021. [[pdf]](https://arxiv.org/pdf/2008.08218.pdf) -->

<!-- **Liao, Z.**, Shi, J., Qi, X., Zhang, X., Wang, W., He, Y., Wei, R., & Liu, X. (2019). Coarse-To-Fine Visual Localization Using Semantic Compact Map. ArXiv, abs/1910.04936. (Preprint) [[pdf]](https://arxiv.org/pdf/1910.04936.pdf) -->

<!-- **Liao, Z.**, Wang, W., Qi, X., Zhang, X., Xue, L., Jiao, J., & Wei, R. (2020). Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments. ArXiv, abs/2004.05303. (Preprint) -->

<!-- ### Patent -->
<!-- **Liao, Z.**, Positioning method, device, electronic equipment, readable storage medium, CN111383286A, 2020 -->

# Projects
## 1. RGB-D Object SLAM using Quadrics for Indoor Environments
**[Sep 2019 - June 2021] The Robotics Institute of Beihang University, supervised by Prof. Wei Wang**

<center><img src="/images/research/object-slam-4.png" width="70%" /></center>
<!-- ![](./pics/object-slam-2.png) -->

* Proposed an object-level semantic SLAM algorithm based on RGB-D and monocular images, which uses a quadric surface as an object model to compactly represent the object's position, orientation, and shape.
* Introduced the support relationships between objects and the structures to help optimize 3D objects parameters.

### Publication

**Liao, Z.**, Hu, Y., Zhang, J., Qi, X., Zhang, X., & Wang, W. (2022). SO-SLAM: Semantic Object SLAM with Scale Proportional and Symmetrical Texture Constraints. IEEE Robotics and Automation Letters. [[pdf]](https://ieeexplore.ieee.org/document/9705562/)

**Liao, Z.**, Wang, W., Qi, X. & Zhang, X.(2020). RGB-D Object SLAM using Quadrics for Indoor Environments. Sensors, 20. [[pdf]](https://www.mdpi.com/1424-8220/20/18/5150/pdf)

### Video Demo 
This is a video demo of an early version. We recommend seeing the publication for the detail.
<iframe width="315" height="177.2" src="https://www.youtube.com/embed/u9zRBp4TPIs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- video size : 420 236.25 -->
<!-- 3/4 video size : 315 177.2 -->

## 2. Point-Plane SLAM Using Supposed Planes for Indoor Environments
**[Sep 2018 - Aug 2020] The Robotics Institute of Beihang University, supervised by Prof. Wei Wang**

This is a co-author project with my colleagues.

<!-- <img src="./pics/point-plane-slam.png" width = 50% height = 35% align=right /> -->
<!-- <center><img src="./pics/point-plane-slam.png" width="70%" height="70%" /></center> -->
<!-- ![](./pics/point-plane-slam.png) -->
<center><img src="/images/research/point-plane-slam.png" width="70%" /></center>

### Publication
Zhang, X., Wang, W., Qi, X., & **Liao, Z**. (2020, August). Stereo plane slam based on intersecting lines. In 2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) (pp. 6566-6572). IEEE. [[pdf]](https://ieeexplore.ieee.org/document/9635961/)

Zhang, X.; Wang, W.; Qi, X.; **Liao, Z.**; Wei, R. Point-Plane SLAM Using Supposed Planes for Indoor Environments. Sensors 2019, 19, 3795. [[pdf]](https://www.mdpi.com/1424-8220/19/17/3795)

## 3. Coarse-to-fine Visual Localization using Semantic Compact Map
**[Oct  2018 – Jul 2019] Research Intern of the SLAM Group in Megvii (Face++) Technology Co., Ltd.**

<!-- <center><img src="./pics/coarse-to-fine.png" width="50%" height="50%" /></center> -->
<!-- ![](./pics/coarse-to-fine.png) -->
<center><img src="/images/research/coarse-to-fine.png" width="50%" /></center>

* Reproduced and evaluated the algorithm proposed in the paper Long-term Visual Localization using Semantically Segmented Images [ICRA2018], which is a semantic localization algorithm based on a particle filter for vehicles. 
* Proposed a coarse-to-fine localization system with pole-like objects extracted from semantically segmented images
* Introduced a localization method decoupling translation from rotation using a monocular camera as a protractor to estimate the poses precisely.


### Publications
**Liao, Z.**, Shi, J., Qi, X., Zhang, X., Wang, W., He, Y., Wei, R., & Liu, X. (2019). Coarse-To-Fine Visual Localization Using Semantic Compact Map. 2020 3rd International Conference on Control and Robots, ICCR 2020, Tokyo, Japan. (accepted) [[pdf]](https://arxiv.org/pdf/1910.04936.pdf)

**Liao, Z.**, Positioning method, device, electronic equipment, readable storage medium, CN111383286A, 2020 (Chinese Patent)

### Video Demo
<iframe width="315" height="177.2" src="https://www.youtube.com/embed/XbTc1YNPajc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## 4. Navigation with Floor Map for Domestic Robots
**[Sep 2017 - Feb 2018] Intelligent Robot Laboratory of Tsukuba University, supervised by Prof. Akihisa Ohya**

<!-- <center><img src="./pics/floor-map.png" width="70%" height="70%" /></center> -->
<!-- ![](./pics/floor-map.png) -->
<center><img src="/images/research/floor-map.png" width="70%" /></center>

* Designed a navigation and mapping system for domestic logistic robots to travel from the entry of a floor to the destination room described by room number, such as A311, when entering a building for the first time. 
* Proposed using the floor map for humans as prior for the robots, which commonly exists at the entry of building floors.
* Used a monocular camera with an OCR recognition algorithm to check the destination room accurately. 



### Video Demo

<iframe width="315" height="177.2" src="https://www.youtube.com/embed/ktOwdE69A_I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Robots

I am a big fan of robots and my university lifes are full of activities related to robotics competitions and electronics design projects. E.g., joined the Beihang Robot Team for the Robocon National Robotics Competition (2016-2018); designed a rotorcraft with a master-slave mechanical arm; and had fun with some robots during my master project. I was once the president of Beihang Robot Association (2015-2016).

<center><img src="/images/research/robots.png" width="70%" /></center>

<!-- ## Robocon National Robotics Competition

**[Sep 2017 - Feb 2018] Beihang University, Beihang Robot Team**

## A Rotorcraft with a Master-slave Mechanical Arm 

## As Beihang Robot Association --> 


<!-- ---

### Last Update
Feb 24, 2022

Sep 23, 2020 -->