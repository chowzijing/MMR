# MMR
Multi-Scale Self-Supervised Correspondence Learning with Motion Enhancement

## Updates
* An [Unofficial implementation](https://github.com/ZhouZihan-jf/MMR) based on Pyotrch has been released.

## Abstract
We propose MMR, a self-supervised object tracking framework that can capture high-value pixel information from unlabeled videos. It makes the model focus more on moving targets rather than the background with motion information, thus improving tracking performance for moving objects.First, we fuse optical flow into frame, extract feature with motion information, then send it to the target attention module. This helps the model concentrate more on the high-value pixels with moving target during the tracking process. Second, compared to previous self-supervised target tracking work based on reconstruction, we expand the pixel correspondence region and design a multi-scale, multi-round similarity calculation algorithm to improve the model's robustness and accuracy. Third, we introduced a negative sample reconstruction loss function and integrated it with the smooth L1 loss function. Simultaneously, we constructed a weight map based on the value information distribution to make the model assess the reconstruction results more accurately.Representations learned via MMR surpasses self-supervised state-of-the-art on label propagation tasks including objects, semantic parts, and keypoints.

## Other Related Work
[Locality-Aware Inter-and Intra-Video Reconstruction for
Self-Supervised Correspondence Learning](https://github.com/lingorX/LIIR)
