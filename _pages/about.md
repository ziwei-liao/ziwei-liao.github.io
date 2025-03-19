---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Biography
Hello, I am Ziwei, currently a 4th-year Ph.D. candidate in computer vision and robotics from the University of Toronto. I studied at the [Toronto Robotics and AI Lab](https://www.trailab.utias.utoronto.ca/) supervised by [Prof. Steven L. Waslander](https://www.trailab.utias.utoronto.ca/stevenwaslander). I am affiliated with the [Institute for Aerospace Study (UTIAS)](https://www.utias.utoronto.ca/), [UToronto Robotics Institute](https://robotics.utoronto.ca/) and the [Vector Institute](https://vectorinstitute.ai/).

<!-- Starting in June 2024, I joined [Niantic Labs](https://nianticlabs.com/), in London, UK, as a research intern. Niantic developed the AR game Pokémon GO and is a leading tech company in 3D mapping.  -->
I was fortunate to cooperated with researchers at [Niantic Labs](https://nianticlabs.com/) in London, UK, in 2024, [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/) (MSRA) in 2023, and [Megvii Research](https://en.megvii.com/) (Face++) in 2021 as a research intern. 

In 2021 and 2018, I received both my M.Sci. and B.E. at the Robotics Institute of [Beihang University](https://ev.buaa.edu.cn/), Beijing, China, supervised by Prof. Wang Wei. In 2017, I visited the [Intelligent Robot Laboratory](https://www.roboken.iit.tsukuba.ac.jp/en/) at Tsukuba University, Japan as a research assistant supervised by Prof. Akihisa Ohya.


Please refer to my [[CV]](/files/ZiweiLiao_CV.pdf) for more details.

<span style="color:red;">
I will graduate before August 2025 and am actively seeking job opportunities in World Models/Generative AI, Embodied AI/Robotics, AR/XR, and other related fields. Please feel free to contact me via email. Thank you!
</span>

## Research Interests

<!-- My long-term goal is to make robots and machines perceive, understand, and interact with 3D environments to help humans in the real world. My past research focuses on 3D vision and learning, including: -->

My research focuses on the intersection of 3D vision, generative models, and computer graphics. I am interested in building a world model, which is essential for enabling machines to perceive, understand, and interact with real-world 3D environments. It has broad applications in physical embodied AI, including robotics and augmented reality. More specifically:

* **3D Representations for Objects and Scenes**: Gaussian Splattings and Implicit representations (e.g., NeRF, SDF), with applications in Simultaneous Localization and Mapping (SLAM), objects reconstruction, and pose estimation.

* **3D Generative Modellings**: Learning to generate 3D representations from images using diffusion models; Solving ill-posed inverse problems by leveraging generative models as priors and quantifying uncertainty.

* **Learning for 3D Perception Tasks**: Developing multi-view learning architectures (e.g., Transformers) for 3D perception tasks such as human pose estimation, while enhancing generalization capabilities.


If you are interested in any of these topics, please don't hesitate to reach out to me for discussion and potential collaboration.


## News

**[3/2025]** A paper on 3D Gaussian Splatting with Diffusion Models, in collaboration with Niantic Labs, has been submitted for review and will be released on arXiv soon.

**[12/2024]** I joined [Niantic Labs](https://nianticlabs.com/) as a research intern in London, UK, in June 2024. I had a wonderful time there and completed the internship in December 2024.

**[9/2024]** [A paper](http://arxiv.org/abs/2311.10983
) on general object-level mapping with a 3D diffusion model has been accepted as a **Spotlight presentation at CoRL 24**, held in Munich, Germany.

**[2/2024]** [A paper](http://arxiv.org/abs/2311.10983
) for 3D human pose estimation with transformers is accepted by **CVPR 24**, cooperated with Microsoft Research Asia, held in Seattle, USA.

**[1/2024]** [A paper](https://arxiv.org/abs/2309.09118) for object-level mapping (3D pose & shape) with uncertainty is accepted by **ICRA 24**, held in Yokohama, Japan.

<!-- **[1/2024]** Enjoyed a nice time and met a lot of researchers during WACV 2024 in Hawaii, USA! -->

<!-- **[11/2023]** A paper for 3D Human Pose Estimation with Transformers is available on [[ArXiv]](http://arxiv.org/abs/2311.10983
), cooperated with Microsoft Research Asia. -->

**[10/2023]** [A paper](https://arxiv.org/abs/2306.11739) for 3D object reconstruction with uncertainty was accepted by **WACV 2024**, held in Hawaii, USA.

<!-- **[9/2023]** A paper for object-level mapping (3D pose & shape) with uncertainty is submitted to **ICRA 24**. [[ArXiv]](https://arxiv.org/abs/2309.09118) -->

**[2/2022]** [A paper](https://arxiv.org/pdf/2109.04884.pdf) for monocular object-level SLAM with quadrics (SO-SLAM) was accepted by **IEEE RA-L** and presented at **ICRA 2022**. 

**[9/2021]** I joined the [Toronto Robotics and AI Lab](https://www.trailab.utias.utoronto.ca/) at the University of Toronto to pursue a Ph.D. in computer vision and robotics. 

<!-- **[7/2021]** A paper for plane-based SLAM was accepted by **IROS 2021**.  -->

<!-- **[6/2021]** I sucessfully graduated from Beihang University and received my master degree. 

**[11/2020]** One paper accepted by ICCR 2020, Tokyo, Japan, and awarded the **Best Session Paper**.

**[09/2020]** I was granted the National Scholarship (Top 5%). -->


...



## Academic Service

I am serving as a reviewer for:

* Journal: The International Journal of Robotics Research
(IJRR), IEEE Robotics and Automation Letters (RA-L) 
* Conference: CVPR 2023-2024; ECCV 2024; NeurIPS 2024; ICLR 2025; ICML 2025; ICRA 2023-2024; WACV 2024-2025.


<!-- ## Publications
Please refer to the page [Research](https://ziwei-liao.github.io/research/) or [My Google Scholar](https://scholar.google.com/citations?user=IhfB2iQAAAAJ&hl=en) for more details.  -->


## Selected Publications
Please see my [Google Scholar Page](https://scholar.google.com/citations?user=IhfB2iQAAAAJ&hl=en) for the latest updates.

---


### 3D with Generative Models

<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/paper_teaser/gom.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Toward General Object-level Mapping from Sparse Views with 3D Diffusion Priors</strong><br><strong>Ziwei Liao</strong>, Binbin Xu, Steven L. Waslander<br>CoRL 2024 (Spotlight)<br><a href="https://openreview.net/forum?id=rEteJcq61j">[PDF]</a> <a href="https://github.com/TRAILab/GeneralObjectMapping">[Code]</a></p>
    </td>
  </tr>
  
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/paper_teaser/mapping.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Uncertainty-aware 3D Object-Level Mapping with Deep Shape Priors</strong><br><strong>Ziwei Liao</strong>*, Jun Yang*, Jingxing Qian*, Angela P. Schoellig, Steven L. Waslander<br>ICRA 2024<br><a href="https://arxiv.org/pdf/2309.09118.pdf">[PDF]</a> <a href="https://github.com/TRAILab/UncertainShapePose">[Code]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/3d_recon.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Multi-view 3D Object Reconstruction and Uncertainty Modelling with Neural Shape Prior</strong><br><strong>Ziwei Liao</strong>, Steven L. Waslander<br>WACV 2024<br><a href="https://arxiv.org/pdf/2306.11739.pdf">[PDF]</a></p>
    </td>
  </tr>
</table>


### 3D Human Pose

<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/paper_teaser/humanpose.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Multiple View Transformers for 3D Human Pose Estimation</strong><br><strong>Ziwei Liao</strong>*, Jialiang Zhu*, Chunyu Wang, Han Hu, Steven Waslander<br>CVPR 2024<br><a href="http://arxiv.org/abs/2311.10983">[PDF]</a> <a href="https://github.com/XunshanMan/MVGFormer">[Code]</a></p>
    </td>
  </tr>
</table>

### 3D Object-level SLAM

<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/soslam.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>SO-SLAM: Semantic Object SLAM with Scale Proportional and Symmetrical Texture Constraints</strong><br><strong>Ziwei Liao</strong>, Yutong Hu, Jiadong Zhang, Xianyu Qi, Xiaoyu Zhang, Wei Wang<br>RA-L & ICRA22<br><a href="https://ieeexplore.ieee.org/document/9705562/">[IEEE]</a> <a href="https://arxiv.org/abs/2109.04884">[arXiv]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/rgbd.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>RGB-D Object SLAM using Quadrics for Indoor Environments</strong><br><strong>Ziwei Liao</strong>, Wei Wang, Xianyu Qi, Xiaoyu Zhang<br>Sensors, 2020<br><a href="https://www.mdpi.com/1424-8220/20/18/5150/pdf">[PDF]</a> <a href="https://www.youtube.com/embed/u9zRBp4TPIs">[Video]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/arxiv.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments</strong><br><strong>Ziwei Liao</strong>, Wei Wang, Xianyu Qi, Xiaoyu Zhang, Lin Xue, Jianzhen Jiao, Ran Wei<br>ArXiv, 2020<br><a href="https://arxiv.org/pdf/2004.05303">[PDF]</a> <a href="https://github.com/XunshanMan/Object-oriented-SLAM">[Code]</a> <a href="https://www.youtube.com/watch?v=u9zRBp4TPIs">[Video]</a></p>
    </td>
  </tr>
</table>

### Mapping, Localization, SLAM

<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/paper_teaser/stereo.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Stereo plane slam based on intersecting lines</strong><br>Xiaoyu Zhang, Wei Wang, Xianyu Qi, <strong>Ziwei Liao</strong><br>IROS 2021<br><a href="https://ieeexplore.ieee.org/document/9635961/">[IEEE]</a> <a href="https://arxiv.org/abs/2008.08218">[arXiv]</a> <a href="https://github.com/fishmarch/Stereo-Plane-SLAM">[Code]</a>
      </p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/plane.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Point-Plane SLAM Using Supposed Planes for Indoor Environments</strong><br>Xiaoyu Zhang, Wei Wang, Xianyu Qi, <strong>Ziwei Liao</strong>, Ran Wei<br>Sensors, 2019<br><a href="https://www.mdpi.com/1424-8220/19/17/3795">[PDF]</a> <a href="https://github.com/fishmarch/SP-SLAM">[Code]</a>
      </p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/coarse-to-fine.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Coarse-To-Fine Visual Localization Using Semantic Compact Map</strong><br><strong>Ziwei Liao</strong>, Jieqi Shi, Xianyu Qi, Xiaoyu Zhang, Wei Wang, Yijia He, Ran Wei, Xiao Liu<br>2020 3rd International Conference on Control and Robots (Best Session Presentation)<br><a href="https://arxiv.org/pdf/1910.04936.pdf">[PDF]</a> <a href="https://www.youtube.com/embed/XbTc1YNPajc">[Video]</a></p>
    </td>
  </tr>
</table>

### Robots Navigation


<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/floor-map.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Semantic Navigation for Indoor Robots with Corridor Map Prior</strong><br><strong>Ziwei Liao</strong>, Akihisa Ohya<br>Research Project at Tsukuba University, Japan, 2017<br><a href=" https://www.youtube.com/embed/ktOwdE69A_I">[Video]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/navigation.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:20px;"><strong>Object Semantic Grid Mapping with 2D LiDAR and RGB-D Camera for Domestic Robot Navigation</strong><br>Xianyu Qi, Wei Wang, <strong>Ziwei Liao</strong>, Xiaoyu Zhang, Dongsheng Yang, Ran Wei<br>Applied Sciences, 2020<br><a href="https://www.mdpi.com/2076-3417/10/2/672">[PDF]</a></p>
    </td>
  </tr>
</table>


## Hands-On Experience with Real-World Robots

<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="700px">
      <!-- Left side empty -->
      <img src="/images/research/robots.png" width="100%"/>
    </td>
  </tr>
</table>
I have been a huge enthusiast of robotics throughout my college years.
I was the vice captain of the Robot Team at Beihang University, participating in the Robocon National Robotics Competition (2016-2018). 
I designed a rotorcraft equipped with a master-slave mechanical arm (2015). 
I had the opportunity to work with various robots during both my bachelor's and master's projects (2018, 2021). 
I served as the president of the Robotics Student Association at Beihang University (2015-2016).
