---
title: "CDPC Manager"
collection: project
custom: 'true'
# custom_remark: "Course Project under the guidance of Dr. Murala"
permalink: /projects/
excerpt: "Designed and constructed a Django-based website for the college’s Career Development and Placement Cell (CDPC) competition. In this website, implemented features such as Institute ID-based authentication, multi-level user roles, and advanced filtering. View the code [here](https://github.com/abhay3141/CDPC_Manager)"
date: 2022-06-13
venue: 'NA'
---

<style>

/* Style the counter cards */
.card {
<!--   box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */ -->
  padding: 16px;
<!--   text-align: center; -->
<!--   background-color: #f1f1f1; -->
}

a:link {
  text-decoration: none;
}
</style>

In this project, we implement an algorithm to recover the 3D trajectory of a camera through feature-based sparse SLAM (Simultaneous Localization and Mapping) using a single camera, also known as MonoSLAM. The keypoints are extracted using ORB. Subsequently, feature matching involves calculating the distances between all point pairs through a brute-force approach, followed by the estimation of 2 nearest neighbors using knn clustering and the elimination of points/pairs through a ratio test. Essential matrix estimation is then carried out using the 8-point algorithm, converting image coordinates to camera coordinates, and employing thresholding and RANSAC to eliminate outliers. The subsequent steps involve pose estimation, where the pose of the current frame is estimated using the essential matrix, and world coordinate computation, achieved by triangulation using two projection matrices as input.  

Code [here](https://github.com/neeleshverma/Monocular-slam)