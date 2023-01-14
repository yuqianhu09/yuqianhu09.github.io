---
title: "DeFall: Environment-Independent Passive Fall Detection Using WiFi"
collection: projects
permalink: /projects/2018-DeFall
venue: "Electrical & Computer Engineering, University of Maryland, Collge Park"
date: 2019
location: "Collge Park, MD"
---

<img src="https://yuqianhu09.github.io/images/2018_defall_flowchart.PNG" width="560">

Abstract
---------
Fall is recognized as one of the most frequent accidents among elderly people. Many solutions, either wearable or noncontact, have been proposed for fall detection (FD) recently. Among them, WiFi-based noncontact approaches are gaining popularity due to the ubiquity and noninvasiveness. The existing works, however, usually rely on labor-intensive and time-consuming training before it can achieve a reasonable performance. In addition, the trained models often contain environment-specific information and, thus, cannot be generalized well for new environments. In this article, we propose DeFall, a WiFi-based passive FD system that is independent of the environment and free of prior training in new environments. Unlike previous works, our key insight is to probe the physiological features inherently associated with human falls, i.e., the distinctive patterns of speed and acceleration during a fall. DeFall consists of an offline template-generating stage and an online decision-making stage, both taking the speed estimates as input. In the offline stage, augmented dynamic time-warping (DTW) algorithms are performed to generate a representative template of the speed and acceleration patterns for a typical human fall. In the online phase, we compare the patterns of the real-time speed/acceleration estimates against the template to detect falls. To evaluate the performance of DeFall, we built a prototype using commercial WiFi devices and conducted experiments under different settings. The results demonstrate that DeFall achieves a detection rate above 95% with a false alarm rate lower than 1.50% under both line-of-sight (LOS) and non-LOS (NLOS) scenarios with one single pair of transceivers. Extensive comparison study verifies that DeFall can be generalized well to new environments without any new training.

<img src="https://yuqianhu09.github.io/images/2018_defall_flowchart.PNG" width="700">

Publications
---------
1. **Yuqian Hu**, Feng Zhang, Chenshu Wu, Beibei Wang and K. J. Ray Liu, "DeFall: Environment-Independent Passive Fall Detection Using WiFi," in IEEE Internet of Things Journal. [[IEEE Xplore]](https://ieeexplore.ieee.org/document/9552243)
2.  **Yuqian Hu**, Feng Zhang, Chenshu Wu, Beibei Wang and K. J. Ray Liu, "A WiFi-Based Passive Fall Detection System," ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2020. [[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/9054753) 

