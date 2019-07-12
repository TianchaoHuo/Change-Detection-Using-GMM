# Change-Detection-Using-GMM

## Overview
Change detection is one of the most commonly used methods for detecting moving objects in a computer vision system. It detects moving objects in an image sequence by comparing the background model with the current frame. Traditional moving target detection algorithms have problems such as dynamic background changes caused by illumination changes, noise and shadow sensitivity. <!--more-->
In this project, a method based on Gaussian Mixture Model (GMM) is introduced for the challenge of object detection, which modeling each pixel of each frame as a mixture of Gaussians and using an on-line approximation to update the model. Based on whether the Gaussian distribution that represents it most effectively is considered part of the background model, each pixel is classified. This report is targeted to utilizes the python to implement the GMM algorithm to segment background for several videos
</br>
Repo:

## Objective:
1. Detecting the moving object in videos recorded by a stationary camera
2. Segmentation between foreground and background
3. Adaptive in working conditions
4. Not costly develop

## Dataset
PETS 2009 (ftp://pets.rdg.ac.uk)


## Step
This implementataion is based on the python 3 and open-cv package.
Hence, you need to install the related implementation environment.


## Result
Visually demo is shown in this blog: https://tianchaohuo.github.io/2019/07/12/Change-detection-using-GMM/



## Summary
- Pros
1. Be adaptive to different scenes
2. Be capable to segment videos
3. Good trade-off between quality and execution time
- Cons
1. Arbitrarily set the parameters
2. Assume each pixel is independent of its neighbors.



## References
[1] C. Stauffer and W. E. L. Grimson, "Adaptive background mixture models for real-time tracking," in 1999, . DOI: 10.1109/CVPR.1999.784637.</br>
[2] H. Shih-Shinh, https://www.youtube.com/watch?v=g_ve2txPkSc, 2018.</br>
[3] Swapnil Das, https://github.com/swapnil96
