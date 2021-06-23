# SFND 2D Feature Tracking

<img src="images/keypoints.png" width="820" height="248" />

I have implemented all the features required.

UDACITY_PR2.ods file contains performance metrics.

The first table contains following items for each detector:
-Total features detected
-Rectangle associated features detected
-Time consumed for detecting the features

Mean detection time is calcuted by using the 10 images.
Top-3 scores are marked with different colors: Green, Yellow, Red

Following 9 tables contains the number of total matched keypoints for each image pair.

The last but not the least table summarizes the total time takes for the computation of feature detection, description and matching. Top-3 scores are marked with different colors. The score marked with green is the fastest one.

The last table is the recommendation table. Here I have selected the features according to their execution time and the descriptors' power to extract features that can be matched. 

Sheet2 contains mean and variance neighborhood for the features. Detectors like SHITOMASI HARRIS and FAST has constant neighborhood size.
-SHITOMASI: 4
-HARRIS: 6
-FAST: 7

Other detectors like BRISK, ORB, AKAZE, SIFT has changing neighborhood size. So all the neighborhood sizes are collected and mean and standard deviance is calculated from collected sets. Below the mean and standard deviance for the feature detectors are given:
BRISK 22.25;14.75
ORB 55.73;24.27
AKAZE 7.84;3.62
SIFT: 5.67;6.74


