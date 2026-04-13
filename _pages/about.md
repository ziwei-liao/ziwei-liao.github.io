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
Hello, I am Ziwei, an Applied Scientist at [Wayve AI](https://wayve.ai/) based in London, UK. My current work focuses on world models ([GAIA](https://wayve.ai/thinking/gaia-3/)) for representing real-world environments and developing embodied AI systems that operate in the physical world.

> My long-term research goal is to develop general, scalable, and safe robots that operate in the real world and integrate into human society to help solve real-world tasks.

I received my Ph.D. (2021–2025) from the [Toronto Robotics and AI Lab](https://www.trailab.utias.utoronto.ca/) at the University of Toronto, supervised by [Prof. Steven L. Waslander](https://www.trailab.utias.utoronto.ca/stevenwaslander). During this time, I was also affiliated with the [Institute for Aerospace Studies (UTIAS)](https://www.utias.utoronto.ca/), the [UofT Robotics Institute](https://robotics.utoronto.ca/), and the [Vector Institute](https://vectorinstitute.ai/).

I have collaborated with researchers at [Niantic Labs](https://nianticlabs.com/) (London, UK, 2024), [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/) (2023), and [Megvii Research](https://en.megvii.com/) (Face++, 2021) as a research intern.

I earned my M.Sci. (2021) and B.E. (2018) degrees from the Robotics Institute at [Beihang University](https://ev.buaa.edu.cn/) in Beijing, China. In 2017, I was a visiting research assistant at the [Intelligent Robot Laboratory](https://www.roboken.iit.tsukuba.ac.jp/en/) at the University of Tsukuba, Japan.

> Please refer to my [[CV]](/files/ZiweiLiao_CV.pdf) for more details.

## Research Interests
My research focuses on the intersection of computer vision, generative models, and robotics. Please see my [Google Scholar](https://scholar.google.com/citations?user=IhfB2iQAAAAJ&hl=en) for a full list of publications.

I am interested in building world models that enable machines to perceive, understand, and interact with real-world 3D environments. More specifically:

* **World Representations for Objects and Scenes**: Gaussian splatting and implicit representations (e.g., NeRF, SDF).

* **Self-Supervised Generative Learning**: Learning 3D representations from large-scale image and video data using diffusion models.

* **Learning for Ill-Posed 3D Perception**: Developing methods for 3D reconstruction and perception from sparse-view images, leveraging generative models as priors, and quantifying uncertainty.

> If you are interested in these topics, feel free to reach out for discussion or potential collaboration.

## News
**[09/2025]** I joined [Wayve](https://wayve.ai/) as an Applied Scientist, working on world models. We announced [GAIA 3](https://wayve.ai/thinking/gaia-3/), scaling world models for safety and evaluation.

**[12/2024]** [A paper](https://nianticspatial.github.io/completesplat/) on 3D Gaussian splatting with diffusion models, in collaboration with [Niantic Labs](https://nianticlabs.com/), is available on arXiv.

**[09/2024]** [A paper](http://arxiv.org/abs/2311.10983) on general object-level mapping with a 3D diffusion model was accepted as a **Spotlight presentation at CoRL 2024**, held in Munich, Germany.

**[02/2024]** [A paper](http://arxiv.org/abs/2311.10983) on 3D human pose estimation with transformers was accepted to **CVPR 2024**, in collaboration with Microsoft Research Asia, held in Seattle, USA.

**[01/2024]** [A paper](https://arxiv.org/abs/2309.09118) on object-level mapping (3D pose and shape) with uncertainty was accepted to **ICRA 2024**, held in Yokohama, Japan.

**[10/2023]** [A paper](https://arxiv.org/abs/2306.11739) on 3D object reconstruction with uncertainty was accepted to **WACV 2024**, held in Hawaii, USA.

**[02/2022]** [A paper](https://arxiv.org/pdf/2109.04884.pdf) on monocular object-level SLAM with quadrics (SO-SLAM) was accepted to **IEEE RA-L** and presented at **ICRA 2022**.

<!-- **[09/2021]** I joined the [Toronto Robotics and AI Lab](https://www.trailab.utias.utoronto.ca/) at the University of Toronto to pursue a Ph.D. in computer vision and robotics. -->

...


## Academic Service
I have served as a reviewer for:

* **Journals**: The International Journal of Robotics Research (IJRR), IEEE Robotics and Automation Letters (RA-L)
* **Conferences**: CVPR (2023–2024), ECCV (2024), NeurIPS (2024), ICLR (2025), ICML (2025), ICRA (2023–2024), WACV (2024–2025)

<!-- ## Publications
Please refer to the page [Research](https://ziwei-liao.github.io/research/) or [My Google Scholar](https://scholar.google.com/citations?user=IhfB2iQAAAAJ&hl=en) for more details.  -->


## Selected Publications
Please see my [Google Scholar page](https://scholar.google.com/citations?user=IhfB2iQAAAAJ&hl=en) for the latest updates.

---

### 3D with Generative Models

<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/paper_teaser/completesplat.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Complete Gaussian Splats from a Single Image with Denoising Diffusion Models</strong><br><strong>Ziwei Liao</strong>, Mohamed Sayed, Steven L. Waslander, Sara Vicente, Daniyar Turmukhambetov, Michael Firman<br>ArXiv 2025<br><a href="https://arxiv.org/abs/2508.21542">[PDF]</a> <a href="https://nianticspatial.github.io/completesplat/">[Website]</a></p>
    </td>
  </tr>
  
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/paper_teaser/gom.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Toward General Object-level Mapping from Sparse Views with 3D Diffusion Priors</strong><br><strong>Ziwei Liao</strong>, Binbin Xu, Steven L. Waslander<br>CoRL 2024 (Spotlight)<br><a href="https://openreview.net/forum?id=rEteJcq61j">[PDF]</a> <a href="https://github.com/TRAILab/GeneralObjectMapping">[Code]</a></p>
    </td>
  </tr>
  
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
      <img src="/images/research/paper_teaser/mapping.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Uncertainty-aware 3D Object-Level Mapping with Deep Shape Priors</strong><br><strong>Ziwei Liao</strong>*, Jun Yang*, Jingxing Qian*, Angela P. Schoellig, Steven L. Waslander<br>ICRA 2024<br><a href="https://arxiv.org/pdf/2309.09118.pdf">[PDF]</a> <a href="https://github.com/TRAILab/UncertainShapePose">[Code]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/3d_recon.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Multi-view 3D Object Reconstruction and Uncertainty Modelling with Neural Shape Prior</strong><br><strong>Ziwei Liao</strong>, Steven L. Waslander<br>WACV 2024<br><a href="https://arxiv.org/pdf/2306.11739.pdf">[PDF]</a></p>
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
      <p style="font-size:17px;"><strong>Multiple View Transformers for 3D Human Pose Estimation</strong><br><strong>Ziwei Liao</strong>*, Jialiang Zhu*, Chunyu Wang, Han Hu, Steven Waslander<br>CVPR 2024<br><a href="http://arxiv.org/abs/2311.10983">[PDF]</a> <a href="https://github.com/XunshanMan/MVGFormer">[Code]</a></p>
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
      <p style="font-size:17px;"><strong>SO-SLAM: Semantic Object SLAM with Scale Proportional and Symmetrical Texture Constraints</strong><br><strong>Ziwei Liao</strong>, Yutong Hu, Jiadong Zhang, Xianyu Qi, Xiaoyu Zhang, Wei Wang<br>RA-L & ICRA22<br><a href="https://ieeexplore.ieee.org/document/9705562/">[IEEE]</a> <a href="https://arxiv.org/abs/2109.04884">[arXiv]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/rgbd.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>RGB-D Object SLAM using Quadrics for Indoor Environments</strong><br><strong>Ziwei Liao</strong>, Wei Wang, Xianyu Qi, Xiaoyu Zhang<br>Sensors, 2020<br><a href="https://www.mdpi.com/1424-8220/20/18/5150/pdf">[PDF]</a> <a href="https://www.youtube.com/embed/u9zRBp4TPIs">[Video]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/arxiv.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments</strong><br><strong>Ziwei Liao</strong>, Wei Wang, Xianyu Qi, Xiaoyu Zhang, Lin Xue, Jianzhen Jiao, Ran Wei<br>ArXiv, 2020<br><a href="https://arxiv.org/pdf/2004.05303">[PDF]</a> <a href="https://github.com/XunshanMan/Object-oriented-SLAM">[Code]</a> <a href="https://www.youtube.com/watch?v=u9zRBp4TPIs">[Video]</a></p>
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
      <p style="font-size:17px;"><strong>Stereo plane slam based on intersecting lines</strong><br>Xiaoyu Zhang, Wei Wang, Xianyu Qi, <strong>Ziwei Liao</strong><br>IROS 2021<br><a href="https://ieeexplore.ieee.org/document/9635961/">[IEEE]</a> <a href="https://arxiv.org/abs/2008.08218">[arXiv]</a> <a href="https://github.com/fishmarch/Stereo-Plane-SLAM">[Code]</a>
      </p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/plane.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Point-Plane SLAM Using Supposed Planes for Indoor Environments</strong><br>Xiaoyu Zhang, Wei Wang, Xianyu Qi, <strong>Ziwei Liao</strong>, Ran Wei<br>Sensors, 2019<br><a href="https://www.mdpi.com/1424-8220/19/17/3795">[PDF]</a> <a href="https://github.com/fishmarch/SP-SLAM">[Code]</a>
      </p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/coarse-to-fine.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Coarse-To-Fine Visual Localization Using Semantic Compact Map</strong><br><strong>Ziwei Liao</strong>, Jieqi Shi, Xianyu Qi, Xiaoyu Zhang, Wei Wang, Yijia He, Ran Wei, Xiao Liu<br>2020 3rd International Conference on Control and Robots (Best Session Presentation)<br><a href="https://arxiv.org/pdf/1910.04936.pdf">[PDF]</a> <a href="https://www.youtube.com/embed/XbTc1YNPajc">[Video]</a></p>
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
      <p style="font-size:17px;"><strong>Semantic Navigation for Indoor Robots with Corridor Map Prior</strong><br><strong>Ziwei Liao</strong>, Akihisa Ohya<br>Research Project at Tsukuba University, Japan, 2017<br><a href=" https://www.youtube.com/embed/ktOwdE69A_I">[Video]</a></p>
    </td>
  </tr>
  <tr>
    <td style="border: 0;" width="300px">
      <!-- Add your image here -->
        <img src="/images/research/paper_teaser/navigation.png" alt="alternative text" width="400"/>
    </td>
    <td style="border: 0;">
      <p style="font-size:17px;"><strong>Object Semantic Grid Mapping with 2D LiDAR and RGB-D Camera for Domestic Robot Navigation</strong><br>Xianyu Qi, Wei Wang, <strong>Ziwei Liao</strong>, Xiaoyu Zhang, Dongsheng Yang, Ran Wei<br>Applied Sciences, 2020<br><a href="https://www.mdpi.com/2076-3417/10/2/672">[PDF]</a></p>
    </td>
  </tr>
</table>

## Hands-On Experience with Real-World Robots

<table style="border: 0;">
  <tr>
    <td style="border: 0;" width="700px">
      <img src="/images/research/robots.png" width="100%"/>
    </td>
  </tr>
</table>

I have been deeply interested in robotics throughout my studies.

I served as Vice Captain of the Robotics Team at Beihang University, where I participated in the RoboCon National Robotics Competition (2016–2018). I also designed a rotorcraft equipped with a master-slave robotic arm (2015). During my bachelor’s and master’s studies (2018, 2021), I worked with a variety of robotic systems on research projects. In addition, I served as President of the Robotics Student Association at Beihang University (2015–2016).