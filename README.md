# EvOcc: Accurate Semantic Occupancy for Automated Driving Using Evidence Theory" (CVPR 2025)

We present *EvOcc*, a novel framework for evidential semantic occupancy mapping.
It consists of two parts: (1) an evidential approach for calculating the ground-truth 3D semantic occupancy maps from noisy LIDAR measurements, and (2) a method for training image-based occupancy estimation models through a new loss formulation.
In contrast to state-of-the-art semantic occupancy maps, our approach explicitly models the uncertainty introduced by unobserved spaces or contradicting measurements, and we show that using it results in significantly stronger models.
Evaluated as ray-based mIoU, our evidential semantic occupancy mapping approach improves over the baselines by at least 15.8%for the ground truth and 5.5% for the trained model.
Overall, we make a significant contribution towards more detailed and uncertainty-aware 3D environment understanding and safe operation in autonomous driving.
Code will be available soon!

![method overview.](overview.png)
