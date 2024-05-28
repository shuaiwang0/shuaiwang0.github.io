---
title: "Robust Pose Estimation for Spherical Panorama"
collection: publications
permalink: /publication/Robust Pose Estimation for Spherical Panorama
#excerpt: 'This paper is the master's thesis.'
date: 2024-05-17
#venue: 'GitHub Journal of Bugs'
slidesurl: 'http://shuaiwang0.github.io/files/Robust-Pose-Estimation-for-Spherical-panorama-slides.pdf'
paperurl: 'http://shuaiwang0.github.io/files/Robust-Pose-Estimation-for-Spherical-panorama.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Spherical panoramas have emerged as a critical component in various domains, including computer vision, robotics, and immersive experiences. Their applications span Virtual Reality (VR), Augmented Reality (AR), Mixed Reality (MR), Virtual Tourism (VT), and robot navigation. In virtual travel scenarios, akin to navigating cities via Google Street View, the demand for seamless transitions from outdoor to indoor environments has surged. Achieving accurate pose estimation becomes paramount for enabling smooth scene-to-scene navigation.
This research tackles the inherent challenges posed by diverse panoramic scenes. Single keypoint detection and matching algorithms often encounter limitations, such as insufficient matching points and susceptibility to high noise levels. To address these issues, we propose an innovative algorithm that synergistically combines multiple keypoint detection and matching methods. By doing so, we mitigate the scarcity of matching points and enhance robustness.
Furthermore, we address noise influence by transforming the matching points onto a unit sphere and subsequently grouping them. This grouping strategy effectively reduces outlier rates within specific data clusters. Notably, our approach operates in scenarios where traditional single-view methods struggle due to weak textures, varying lighting conditions, and limited overlap.
In addition, we introduce a novel reprojection error function for evaluating the essential matrix. Unlike conventional threshold-based approaches, our function directly computes the reprojection error using camera coordinates, eliminating the need for manual parameter tuning.
Extensive testing across a diverse dataset of over 300 high-resolution spherical panoramas validates the stability and accuracy of our method. Even in challenging scenarios, such as scenes with minimal overlap or high error rates due to incorrect matches, our approach consistently delivers reliable results.
Finally, we extensively test our approach on over 400 pairs of high-resolution spherical panoramas across more than 10 series. Our method consistently delivers accurate results, even in challenging scenarios such as weak textures, varying lighting conditions, and limited overlap or high error rates due to incorrect matches.
