---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

---
# Main Projects
## 1. Object-level SLAM for Indoor Environments
**[Sep 2019 - Current] The Robotics Institute of Beihang University**

<!-- <center><img src="./pics/object-slam-2.png" width="70%" /></center> -->
![](./pics/object-slam-2.png)

* Proposed an object-level semantic SLAM algorithm based on RGB-D data, which uses a quadric surface as an object model to compactly represent the object's position, orientation, and shape.
* Introduced the support relationships between objects and the structure planes to estimate 3D objects parameters.
* Introduced a nonparametric pose graph to solve data associations in the back end, and innovatively applied it to the quadric surface model.
* Evaluated the algorithm on two public datasets and an author-collected mobile robot dataset and obtained obvious improvements on the localization accuracy and mapping effects compared with two state-of-art object SLAM algorithms.

### Publication & Preprint

[1] **Liao, Z.**, Wang, W., Qi, X. & Zhang, X.(2020). RGB-D Object SLAM using Quadrics for Indoor Environments. Sensors. [[pdf]](https://www.mdpi.com/1424-8220/20/18/5150/pdf)

[2] (an ealier version of [1]) **Liao, Z.**, Wang, W., Qi, X., Zhang, X., Xue, L., Jiao, J., & Wei, R. (2020). Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments. ArXiv. [[pdf]](https://arxiv.org/abs/2004.05303)

### Codes
We have released the early version codes on [Github](https://github.com/XunshanMan/Object-oriented-SLAM).

### Video Demo 
This is a video demo of the early version.
<iframe width="420" height="236.25" src="https://www.youtube.com/embed/u9zRBp4TPIs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## 2. Coarse-to-fine Visual Localization using Semantic Compact Map
**[Oct  2018 – Jul 2019] Research Intern of the SLAM Group in Megvii (Face++) Technology Co., Ltd.**

<!-- <center><img src="./pics/coarse-to-fine.png" width="50%" height="50%" /></center> -->
![](./pics/coarse-to-fine.png)

* Proposed a coarse-to-fine localization system with pole-like objects extracted from semantically segmented images.
* Proposed a localization method decoupling translation from rotation using a monocular camera as a protractor to estimate the vehicle poses accurately. 
* Achieved comparable accuracy with SIFT feature-based methods with a significant small map size about 2.7 kb/km. 

### Patent & Preprint
[1] **Liao, Z.**, Positioning method, device, electronic equipment and readable storage medium, CN111383286A
(2020) (in Chinese)

[2] **Liao, Z.**, Shi, J., Qi, X., Zhang, X., Wang, W., He, Y., Wei, R., & Liu, X. (2019). Coarse-To-Fine Visual Localization Using Semantic Compact Map. ArXiv.  [[pdf]](https://arxiv.org/abs/1910.04936)

### Video Demo
<iframe width="420" height="236.25" src="https://www.youtube.com/embed/XbTc1YNPajc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## 3. Navigation with Floor Map for Domestic Robots
**[Sep 2017 - Feb 2018] Intelligent Robot Laboratory of Tsukuba University**

<!-- <center><img src="./pics/floor-map.png" width="70%" height="70%" /></center> -->
![](./pics/floor-map.png)

* Designed a navigation and mapping system for domestic logistic robots to travel from the entry of a floor to the destination room described by room number, such as A311, which enters an unknown building at the first time. 
* Proposed aligning the floor map for human, which commonly exists at the entry of building floors, with a grid map maintained by laser sensor and wheeled odometry of robots, then planning a path using the semantic information on the floor map, e.g. room numbers and positions, feasible corridors.
* Used a monocular camera with OCR recognition algorithm to check the destination room accurately. 


### Video Demo

<iframe width="420" height="236.25" src="https://www.youtube.com/embed/ktOwdE69A_I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



# Co-author Projects 

These projects are conducted with my labratory colleges in the Robotics Institue of Beihang University.

## 1. Object Semantic Grid Mapping
<!-- <img src="./pics/semantic-mapping.png" width = 50% height = 35% align=right /> -->
<!-- <center><img src="./pics/semantic-mapping.png" width="50%" height="50%" /></center> -->
![](./pics/semantic-mapping.png)

### Abstract 
Occupied grid maps are sufficient for mobile robots to complete metric navigation tasks in domestic environments. However, they lack semantic information to endow the robots with the ability of social goal selection and human-friendly operation modes. In this paper, we propose an object semantic grid mapping system with 2D Light Detection and Ranging (LiDAR) and RGB-D sensors to solve this problem. At first, we use a laser-based Simultaneous Localization and Mapping (SLAM) to generate an occupied grid map and obtain a robot trajectory. Then, we employ object detection to get an object’s semantics of color images and use joint interpolation to refine camera poses. Based on object detection, depth images, and interpolated poses, we build a point cloud with object instances. To generate object-oriented minimum bounding rectangles, we propose a method for extracting the dominant directions of the room. Furthermore, we build object goal spaces to help the robots select navigation goals conveniently and socially. We have used the Robot@Home dataset to verify the system; the verification results show that our system is effective. 


### Publication

Qi, X.; Wang, W.; **Liao, Z.**; Zhang, X.; Yang, D.; Wei, R. Object Semantic Grid Mapping with 2D LiDAR and RGB-D Camera for Domestic Robot Navigation. Appl. Sci. 2020, 10, 5782. [[pdf]](https://www.mdpi.com/2076-3417/10/17/5782)


## 2. Point-Plane SLAM

<!-- <img src="./pics/point-plane-slam.png" width = 50% height = 35% align=right /> -->
<!-- <center><img src="./pics/point-plane-slam.png" width="70%" height="70%" /></center> -->
![](./pics/point-plane-slam.png)

### Abstract

Simultaneous localization and mapping (SLAM) is a fundamental problem for various applications. For indoor environments, planes are predominant features that are less affected by measurement noise. In this paper, we propose a novel point-plane SLAM system using RGB-D cameras. First, we extract feature points from RGB images and planes from depth images. Then plane correspondences in the global map can be found using their contours. Considering the limited size of real planes, we exploit constraints of plane edges. In general, a plane edge is an intersecting line of two perpendicular planes. Therefore, instead of line-based constraints, we calculate and generate supposed perpendicular planes from edge lines, resulting in more plane observations and constraints to reduce estimation errors. To exploit the orthogonal structure in indoor environments, we also add structural (parallel or perpendicular) constraints of planes. Finally, we construct a factor graph using all of these features. The cost functions are minimized to estimate camera poses and global map. We test our proposed system on public RGB-D benchmarks, demonstrating its robust and accurate pose estimation results, compared with other state-of-the-art SLAM systems. 


### Publication
Zhang, X.; Wang, W.; Qi, X.; **Liao, Z.**; Wei, R. Point-Plane SLAM Using Supposed Planes for Indoor Environments. Sensors 2019, 19, 3795. [[pdf]](https://www.mdpi.com/1424-8220/19/17/3795)